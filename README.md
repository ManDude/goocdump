This is a repository that contains the GOOL files in the _Crash Bandicoot_ decompiled into the _gooc_ format, to be used with [gooc](https://github.com/mandude/gooc).

There is a folder for each of the three games, within each folder contains a list of "versions" (regions or pre-release builds), each of which may contain the appropriate __.gooc__ files for the game & version. The main game folder may also contain the gooc files, if they are set up such that the region directives appropriately describe each of the three regions (NTSC-U, PAL, NTSC-J). 

There may be a script file included for compiling all of the scripts into appropriate GOOL executable files, as there are many files and even more different ways to compile them properly.

The compiled result of these files __is NOT byte-perfect__. It is, however, _functionally identical_.

The names of most structures have been deduced based on patterns seen in actual named structures. States, spawns, graphics and variables do not have names when compiled, and were deduced. In Crash 2 and onwards, entities have names in them.

A list of GOOL executables per-game and where they can be found is located [here](https://wiki.cbhacks.com/w/User:Mddass/List_of_GOOL_Executables).

For information on how the _gooc_ language works, please refer to the manual that comes with the gooc program.
