# KTLT
Timeline is 2023.1, for course [ET2031](https://tailieuhust.com/tai-lieu-ky-thuat-lap-trinh-hust/). A friend and I had a plan of making Sudoku in the original map 9x9. If possible, we wanted it to have a seperate UI, other than the Terminal. This source code should allow you running Sudoku in your chosen terminal.

# How to play 
What do you mean by this. It is f*king Sudoku. The Vanilla one of course.
The gist of it is that, in a map like 9x9, the player wins when there is no single column, row or diagonal that contains two of the same number

Eg:
```bash
Bad:  1 2 3 3 5 6 7 8 9
      .................
Good: 1 2 3 4 5 6 7 8 9
      .................
```
# Requirements
- Uses Linux or Windows (OSC for boarder side)
- Have g++, clang++ in their newest version.
# Installing session
- For Linux, use your good ol' git clone. Then paste the following into your console screen
```bash
cd path/to/desired/directory
g++ -ofast -pthread ./src/*.cpp -lncursesw -o "game name"
```
- For Windows, git clone is available. But I am still working on the syntax for this goober Power Shell.
# Running this junk
- For Linux:
```bash
./"game name"
```
- For Windows:
# Instruction
- Prerequisite: knowing how to play Sudoku, can open your console, compatible Ascii code (I think so)
- If you want to make a new game, use the # Installing session
- If you want to continue an unfinished game, move to the directory (default is this whole folder), and invoke Bash with
```bash
./"game name"
```
(You can alternatively just open your file manager, drag the game file onto the console. Like how Google Drive does it.)
# Demos and bugs
<img align="left" width="700" height="500" src="https://github.com/SaxoCatto/KTLT/blob/main/Bug_encoding.png">
<img align="left" width="400" height="400" src="https://github.com/SaxoCatto/KTLT/blob/main/FINAL_in_console.png">

