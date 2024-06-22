# Tictactoe
Your Java code implements a simple Tic-Tac-Toe game using Swing for the GUI. Here's a breakdown of its functionality:

# Introduction
The game checks for win conditions after each move.
It displays the winner or if the game ends in a tie.

Tic-Tc-Toe is a Java-based project designed to help users play tic tac toe game through an intuitive Graphical User Interface (GUI). The game is played on a 3x3 grid. Players take turns clicking buttons to place their respective marks (X or O).

# Features
 1. Graphical User Interface (GUI)
Utilizes Java Swing (JFrame, JPanel, JButton, JLabel) for interactive elements.
Provides a visually appealing 3x3 grid for gameplay.

 2. Turn-based Gameplay:
Alternates turn between Player X and Player O.
Displays whose turn it is (X or O) using a JLabel at the top.

 3. Interactive Buttons:
Clicking on a button places the current player's mark (X or O).
Buttons change color and text based on the player's turn.

 4. Win Condition Detection:
Checks after each move for win conditions:
Three marks in a row (horizontal, vertical, diagonal).
Declares the winner and disables further button clicks upon winning.

 5. Tie Detection:
Checks if all buttons are filled without a winner.
Declares a tie game and disables further button clicks.

 6. Initialization:
Randomly determines which player starts first (X or O) using Random class.

 7. Outcome Display:
Updates a JLabel with messages indicating the game's current status:
"X Turn" or "O Turn" for player turns.
"X wins", "O wins", or "Tie" for game outcomes.

# Getting Started
Follow these steps to set up and run the Tic-Tac-Toe project:
1. Clone the Repository: Clone the GitHub repository to your local machine using the following command:
sh Copy code
git clone https://github.com/Amandeepkaur1804/Tictactoe.git
2. Open the Project: Use an Integrated Development Environment (IDE) that supports Java to open the project.
3. Run the Application: Locate the main Java file (TicTacToe.java) and run the application. This will launch the Tic-Tac-Toe GUI.

# Contribution
I want you to know that contributions to this project are welcome and encouraged. To contribute:
1. Fork the repository on GitHub.
2. Create a new branch with a descriptive name for your feature or bug fix.
3. Make your changes and improvements to the code.
4. Test your changes thoroughly.
5. Create a pull request to merge your changes into the main repository.

Happy playing!

Initialization of game 
![Screenshot (60)](https://github.com/Amandeepkaur1804/Tictactoe/assets/107187322/23c09c9c-dc0d-46cb-9c8e-82d7fefd730b)

Gameplay while in progress 
![Screenshot (61)](https://github.com/Amandeepkaur1804/Tictactoe/assets/107187322/7626d176-b310-4e39-a485-7d51b6e15ec0)

Result display
![Screenshot (62)](https://github.com/Amandeepkaur1804/Tictactoe/assets/107187322/f0b64b7c-2f3d-49e6-b577-547c01c4e0fa)

