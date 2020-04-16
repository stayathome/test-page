IniEd
=====

TC Lister-plugin for viewing and editing settings files (`*.ini, *.inf, *.reg`).
Compared to text editors offers the convenience of editing and high speed opening large files.


**Download:** [wlx_inied_2.0.7z](https://stayathome.github.io/files/wlx_inied_2.0.7z)

[Discussion (rusian)](http://forum.wincmd.ru/viewtopic.php?t=184)

_Minimal requirements:_ Total Commander 5.51


Manual Installation
-------------------
1. Unpack IniEd.wlx into a plugins' directory (f.e., c:\wincmd\plugins).
2. Select "Configuration -> Options" point in the TC menu.
3. Open "View/Edit" page.
4. Press "Configure internal viewer" button, then "LS-plugins" button.
5. Press "Add" button and choose IniEd.wlx. Press "Ok".
6. Enjoy! ;-)

_Note._ To use the plugin with other file types (`*.url, *.log`), you can edit the corresponding 
`_detect` line in the wincmd.ini file and add the extension you want.

Hotkeys
-------

Hotkeys           | Action
------------------|------------------------------------------------
Tab or Ctrl+Tab   | Switch between the Section and String panels
Ctrl+Tab          | Toggle key/value selection while string editing
Enter             | Edit string parameter
F1                | About plugin...
F2 or Shift+Enter | Rename string
