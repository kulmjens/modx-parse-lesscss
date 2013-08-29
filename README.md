modx-parse-lesscss
==================

Parses a LessCSS-Files in MODX

To install create a new plugin in MODX and copy the content of parselesscss.plugin.txt into the plugin.
Check the OnWebPageComplete-Event in the "Events" tab.
Copy the following line in the "configuration" tab:
&fileIn=LESS File;text; &fileOut=CSS File;text; &minify=Minify?;list;yes,no;yes

Requires MODX Evolution 1.x and a copy of lessphp.inc.php v0.3.9 in the folder "libs" under "assets" a.k.a. "/assets/libs/lessphp.inc.php"
