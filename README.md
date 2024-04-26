# SnakeGame
A simple, console-based Snake game implemented in Java. Players control a snake to eat food while avoiding collisions with walls and the snake's own body.
Gameplay screenshot
![image](https://github.com/KhushiAgarwal15/SnakeGame/assets/91818423/217a8ac0-8805-442f-ac7e-fa33ed7bfb0a)

##Features
•The SnakeGame class extends JPanel and implements the ActionListener and KeyListener interfaces.
•The paintComponent method is overridden to handle the drawing of the game components on the JPanel.
•The move method updates the positions of the snake and checks for collisions with food or the borders of the board.
•Key events are handled in the keyPressed method to change the snake's direction based on user input.
•The actionPerformed method is called by the game loop timer to update the game state and repaint the panel.
•The collision method checks if two tiles are at the same position.

##To install the Snake Game locally from GitHub, follow these steps:
•Clone the repository: Run git clone https://github.com/KhushiAgarwal15/SnakeGame in your terminal or Git GUI client to create a local copy of the repository on your machine.
•Navigate to the directory: Use cd <repository-folder> to move into the cloned repository's folder.
•Compile the Java files: Run javac *.java to compile all Java files in the repository.
•Run the game: Execute java App to start the Snake Game. This will launch the game window, allowing you to play.
