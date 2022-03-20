# SudokuBoardGame

Application contains logic and GUI allowing for full game experience.
In addition, after appropriate configuration, user is able to persist
his current state of the game (including all moves done with the ability to undo)
to the postgres/apache relational database or serialize it to the file.
Ofcourse, the deserialization process and reading from the database is also available.
Project includes internationalization - you can choose between polish and english
versions of the menu and logging. 