**Introduction**

You find a strange mirror that always shows a hand that is moving. The hand appears to be alive, and after a lot of questions of "yes" and "no" answer, you know that the hand is trying to teach you a program that is written in HPL (Hand Programming Language).
This language works with a memory of an indefinite size of bytes, with all values initialized to 0. This language haves 7 instructions:
πΒ : moves the memory pointer to the next cell
πΒ : moves the memory pointer to the previous cell
πΒ : increment the memory cell at the current position
πΒ : decreases the memory cell at the current position.
π€Β : if the memory cell at the current position is 0, jump just after the correspondingΒ π€
π€Β : if the memory cell at the current position is not 0, jump just after the correspondingΒ π€
πΒ : Display the current character represented by the ASCII code defined by the current position.

Notes:
* As memory cells are bytes, from 0 to 255 value, if you decrease 0 you'll get 255, if you increment 255 you'll get 0.
* Loops ofΒ π€Β andΒ π€Β can be nested.

Tests
The hand shows you two small programs and their outputs:

This program display "Hello"
ππ€πππππππππππ€πππππ€πππππππππ€πππππππππππππππππ

This program (with nested loops) display "Hello World!"
ππππππππππ€πππππππππππππ€ππππππππ€ππ€ππππππππππ€ππ€ππππππππππππ€πππ€ππππππππππππππππππππππππππ€ππ€ππππ€πππ€πππππππππππππππππππππππππππππππππππππππππππππ

Challenge
The file "input.hand" is the code of the program
Good luck!
