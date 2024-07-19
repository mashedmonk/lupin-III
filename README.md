# Lupin III - Umi ni Kieta Hihou Translation
- File: `Lupin Disc 1 [J].iso`
- Hash: `7097C62BB0DAD853EEDD17FAB86E333937FC207D`

- File: `Lupin Disc 2 [J].iso`
- Hash: `A99FDE5437736922DF221A4F709D4564163B6002`

![Title screen](https://github.com/DOL-Translations/lupin-III/assets/81663474/0924f239-467f-48b3-a74c-0692e0fa7790)

This is the English translation for Lupin III: Umi ni Kieta Hihou - a game for the GameCube, a visual novel created and published by Asmik Ace.

The original translation was done be Peter Lemon around 8 years ago (From the time of writing this) which can be found here: https://github.com/PeterLemon/GC

All lines have been trasnlated, but chapter 6-8 was done through machine translation. If a proper translation is done, we'll add that to it. 

![Pause menu](https://github.com/radianthero/lupin-III/assets/90285213/f1fa0723-183f-44c3-ad59-b561784078a0)

![Radnom scene](https://github.com/radianthero/lupin-III/assets/90285213/06c6d445-185e-4e2b-81de-a2ac48577027)

# Instructions on patching: If you want the most up to date translation, follow the steps below

- Download/clone the repository
- (Optional) Edit the directory in `compile.bat` marked `C:\Users\bob\Documents\GitHub\lupin-III\src\common\fs\COMMON` to point to your local download of the repository. 
- Once both these files are edited, you'll have to add Discs 1/2 into the `input` folder. It HAS to be renamed correctly, with the names and hashes listed above in the files section. You don't need to have both files in the folder at the same time, one or the other will work. 
- Lastly, back in the `tools` folder, run the `compile.bat` file, and assuming you did all the steps correctly, it'll compile properly.
- That's it! After a few seconds, your translated English ISO will be in the `output` folder. 

# If you just want to use the latest release, go to the release page, download the xDelta patch and use a patcher

Some examples would be <https://hack64.net/tools/patcher.php> for online patching or <https://www.romhacking.net/utilities/598/> for offline patching. 

Special thanks to Peter Lemon for starting the whole thing, and thanks to Drgn for helping me setup the whole project, along with gbaXL for assisting in new tools to make this easier.

# When you pause and go to history, it won't display the words properly. Add this Gameshark code to fix this. 

`C20095B8 00000002
7CE0FA14 3A400000
60000000 00000000
C200A878 00000005
B003003A 3A4000FF
387D0000 38950000
3E208000 62318934
7E2903A6 4E800421
60000000 00000000
C200A88C 00000001
60000000 00000000
C200A860 00000007
B003003A 2C1200FF
41820014 3E208000
6231A87C 7E2903A6
4E800420 387D0000
38950000 3E208000
62318934 7E2903A6
4E800421 00000000
C2008968 00000001
60000000 00000000`

# Current road map for the team (No specific order):

Add support for History fix on disc (currently only available as a Gameshark code)

Look into adding new fonts.

Translate submenus (graphics). Every menu option is actually a pre-made image, and not dynamic with the text, so someone would have to make new assets (Currently being worked on)

Grammar, spacing, etc fixes to text. Sometimes the characters will say the next line after getting rid of the previous line, so the sentence doesn't slow perfectly.