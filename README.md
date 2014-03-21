RobotFactory
============
A puzzle-solving game that provides animation of deterministic finite automata. 

The general idea is that Robots emerge from a source tunnel and follow conveyor belts that are placed by the player. 

Each Robot carries a sequential tape containing red and blue marks.

When the Robot encounters a switch (also placed by the player), it moves in one of three directions depending on
whether the current mark is red, blue, or the tape has reached the end. After taking one of those directions, the tape is
advanced one position to the next mark. Each Robot (and tape) represents a test case for a particular Goal that is stated
in a message bar just under the Menu Bar. The Goal states conditions under which the Robot should be accepted by
moving it to a sink tunnel. A Robot is rejected by directing it onto any blank cell on the game board. Goals are
expressed in terms of features of the tape, such as “contains at least two consecutive reds, followed by one and only one
blue.” The Goal statements, test tapes, and outcomes will be expressed in text files that are loaded from the File menu.

A screenshot of the implementation is given below.
![alt tag](https://raw.github.com/krahulreddyiiit/RobotFactory/master/misc.jpg)
