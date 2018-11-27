![screenshot](https://raw.githubusercontent.com/jeffThompson/DarkArduinoTheme/master/screenshot.png)

Dark Arduino Theme (Fork)
================

Revised for Arduino version 1.8.5+, not tested with earlier versions.

**Changes**
* Line highlight made darker than normal background rather than lighter to increase contrast in the work area.
* Selection colour was very bright making underlying text almost unreadable, so made it much darker green instead.
- kuro68k 2018/11/27


### INSTALLATION  

* Mac users should look in `~/Applications/Arduino.app/Contents/Java/lib` and replace the `theme` folder inside (making a copy of the original in case want to revert back).  
* Windows is located in `C:\Program Files (x86)\Arduino\lib`.  
* Linux will be in `/usr/share/arduino/lib/`  

### CREATING YOUR OWN MODS
The newest version of the Arduino IDE makes creating custom themes trickier: you now need to edit the `theme.txt` file, an XML file inside the `syntax` folder, and the button files. Unfortunately, not all items in the `theme.txt` file actually work, so if you can't get an item to change, try another one of the files.

\- \- \-

Released under [Creative Commons BY-NC-SA license](http://creativecommons.org/licenses/by-nc-sa/3.0/) - feel free to use but [please let me know](http://www.jeffreythompson.org).
