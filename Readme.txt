-To compile and run the game you need Visual Studio or the Gnu Compiler Collection. 
-The process is easy, just open up Developer Command Prompt
and navigate to the program directory using (cd command).

-Execute:
cl connect4.c

-Execute:
connect4

The program is now running. You should be able to see the main screen. Follow the instructions and have fun playing!

There is a connect4lite.c file, which is using only the standart libary, without <time.h>. 
Im including that file, if time.h is not premmited to be used for the coursework.

To get more matrix vibes execute:
color 02

Basic description of the features:

1. Start a Game
Starts with Player 0 which corresponds to '0' as a playing piece. Just input a desired column number.
Button 9 is used as a back (undo) button. If you undo by mistake you can redo, but you can redo, only if you have
pressed undo the last move.
2. Load a Game
That option accesses the savegame.txt file, which is used to save all the games you played.
Pick a game number and it will load the sequence of moves. With enter you step through the next move.
At any time you can resume playing with pressing 's'
3. Enable stats for nerds
Hello nerd!
That enables monitoring the time (or clock ticks) needed for execution of the used algorithms.

If you experience any difficulty or you found a bug, feel free to drop me an email:
kisimovvalentin@gmail.com

Thank you for you time!
