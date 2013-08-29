# modx-parse-lesscss

Parses a LessCSS-File with MODX Evo 1.x<br>
See http://leafo.net/lessphp/ for futher info

## Requirements

- MODX Evolution 1.x
- A copy of lessphp.inc.php v0.3.9 in `/assets/libs/`

## Installation

- Create a new plugin named "ParseLessCSS"
- Copy the content of parselesscss.plugin.txt into the content of the plugin
- Check the **OnWebPageComplete** event in the "events" tab.
- Copy the following in the "configuration" tab: `&fileIn=LESS File;text; &fileOut=CSS File;text; &minify=Minify?;list;yes,no;yes`

## Configuration
- LESS File: should be the LESS file with the relative path and slash infront, e.g. `/assets/templates/website/styles.less`
- CSS File: should be the CSS file that LessCSS generates. e.g. `/asstes/templates/website/styles.css`
- Minify?: Choose **yes** if you want the plugin to minify the generated CSS file

