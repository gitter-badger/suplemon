suplemon
========

Command line text editor with multicursor support. The goal is to replicate sublimetext style functionality in the terminal.

#Goals:
 1. [X] Create a command line text editor with built in multi cursor support. Damn it's amazing!
 2. [ ] Usability should be as good and easy as nano.
 3. [ ] Multi cursor and multi selection should be comparable to sublimetext.
 4. [X] Develop suplemon with suplemon!!!

#Usage:

    python main.py [filename]

#Keyboard shortcuts:
 * Alt + Arrow Keys
   > Add new curors in arrow direction
 
 * ESC
   > Revert to a single cursor
   
 * Ctrl + X
   > Delete line(s)
   
 * Ctrl + F
   > Find text.
   
 * Ctrl + D
   > Add a new cursor at the next occurance.
 
 * F1
   > Save current file
   
 * F2
   > Reload current file
 
 * Alt + Page Up
   > Move line(s) up
 
 * Alt + Page Down
   > Move line(s) down
   
# To-Do
 * Nano-like menu and keyboard shortcuts
 * Proper status bar information
 * Jump to end of whitespace with home key 
 * Command line for getting input
 * Line number toggling
 * Loading multiple files and switching between them
 * Config and storing open cursor positions for restoring later
 * Syntax higlighting
 * Editor plugins
 * ...