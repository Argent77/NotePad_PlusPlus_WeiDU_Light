WeiDU Syntax Highlighters 'Light' for Notepad++
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Author: Argent77
Version: 1.6

The main purpose of the light version is to reduce the processor load, and hence 
the time needed for Notepad++ to apply the color schemes to the script files. 
Therefore it contains only the bare minimum of keywords. Identifiers and special 
filenames have been removed completely. The set of keywords of translation files 
(WeiDU_Light_TRA.xml) has been left unchanged, as it is already lightweight 
compared to the other highlighters.
Alternatively you can install the full version of the WeiDU Syntax Highlighters 
for Notepad++, found somewhere in the download section of the Spellhold Studios 
website.

If you want to install both the full and the light package of the WeiDU Syntax 
Highlighters, the order of installation determines which version is applied 
automatically when opening a script file in Notepad++. The editor applies the 
first highlighting scheme found in the list of user-defined languages matching 
the file type.

Highlighters included:
- WeiDU_Light_TP2.xml: WeiDU script files (*.tp2,*.tph,*.tpa,*.tpp)
- WeiDU_Light_BAF.xml: Script text files (*.baf)
- WeiDU_Light_D.xml: WeiDU dialog files (*.d)
- WeiDU_Light_TRA.xml: WeiDU translation files (*.tra)
The syntax highlighter files work in Notepad++ 6.3 and higher.

Installing the syntax highlighters:
1. Select Language->Define your language... in your Notepad++ menu.
2. (optional) If you already have an older version installed, you should 
   remove it by selecting the appropriate language from the drop-down menu 
   and click the "Remove" button to avoid duplicate entries.
3. Click the "Import..." button and select the respective XML file.
4. Repeat step 2 and 3 for all syntax highlighters you need.
5. Restart Notepad++ to make the changes visible. You should now see the new 
   entries in the Language menu.

Have fun!


History:
v1.7
  - added double quote string delimiter support to WeiDU_Light_TRA
  - added colored text delimiter to WeiDU_TRA
v1.6
  - added several new object specifiers
  - added new script actions and triggers introduced in game engine v2.0
  - added new keywords introduced in WeiDU 240
v1.5
  - added new keywords and function names introduced in WeiDU 239
  - added fixed versions of misspelled EigthNearestEnemyOfType and 
    EigthNearestMyGroupOfType object specifiers
  - moved CREATE from patch to action category
v1.4
  - added several undocumented TP2 keywords
v1.3
  - removed variable delimiters (%)
  - added new keywords introduced in WeiDU 237
  - added new script actions, triggers and objects introduced in IWD:EE
v1.2
  - added tokens, triggers, actions and keywords introduced in BG:EE and BG2:EE
v1.1
  - added new keywords introduced in WeiDU 232
v1.0
  - Initial release
