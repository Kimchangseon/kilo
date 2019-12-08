Kilo
===

Kilo is a small text editor in less than 1K lines of code (counted with cloc).

Usage: kilo `<filename>`

Keys:

    CTRL-S: Save
    CTRL-Q: Quit
    CTRL-F: Find string in file (ESC to exit search, arrows to navigate)

Add Keys :

    CTRL-J : Move Cursor Start point
    CTRL-K : Movew Cursor End point
    CTRL-E : Delete a row

Kilo does not depend on any library (not even curses). It uses fairly standard
VT100 (and similar terminals) escape sequences. The project is in alpha
stage and was written in just a few hours taking code from my other two
projects, load81 and linenoise.

People are encouraged to use it as a starting point to write other editors
or command line interfaces that are more advanced than the usual REPL
style CLI.

Kilo was written by Salvatore Sanfilippo aka antirez and is released
under the BSD 2 clause license.

Team Member
1. Kimchangseon -> B589014 김창선

2. mkp0312 -> B589020 박민규

3. zurijj -> B589062 장주영
