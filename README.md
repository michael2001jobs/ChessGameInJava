# ChessGameInJava

# How to run

Clone this repository:

git clone https://github.com/michael2001jobs/ChessGameInJava.git


Open the project in your favorite IDE or editor.

Compile and run the main class:

/src/application/Program.java


The game runs directly in the console.

# How to play

The chessboard is displayed as text (ASCII).

To play, enter the source square and the target square using chess notation (example: e2 → e4).

When you select a piece, the console highlights the possible moves, using a boolean matrix that makes it easier to visualize moves even in the terminal.

The game continues until checkmate, when the winner is displayed.

# Technologies

Java 21

No external libraries (pure Java)

# About the project

This was my first project in Java.

Developed with the guidance of my teacher, focusing on:

Package structuring (boardgame, chess, application)

Use of abstraction, inheritance, polymorphism, and custom exceptions

Practical application of Object-Oriented Programming

Even though it’s simple, I’m happy with the result, and there’s plenty of room for improvement (such as adding a graphical interface or new features).

# Interesting detail

The project uses a boolean matrix to indicate the possible moves of each piece.
This allows highlighting valid moves directly in the console, improving gameplay even without a graphical interface.