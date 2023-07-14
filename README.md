# Python Cross Game

This is a Python game where you control a turtle trying to cross a busy road. The objective is to successfully navigate the turtle across the road without colliding with any cars. As the levels progress, the game becomes more challenging with an increased number of cars on the road. If you manage to reach level 10 without any collisions, you win the game.

## Game Controls

- Use the **Up Arrow** key to move the turtle upwards.
- Use the **Down Arrow** key to move the turtle downwards.

## How to Run the Game

Make sure you have Python installed on your system. To run the game, follow these steps:

1. Clone the game repository or download the source code files.
2. Open a terminal or command prompt and navigate to the game directory.
3. Run the following command to start the game:

   ```bash
   python main.py
   ```

4. The game window will appear, and you can start playing.

## Game Features

- **Level Progression:** The game starts at level 1, and as you successfully cross the road without collisions, the level increases. With each level, the number of cars on the road increases, making it more challenging.
- **Collision Detection:** The game has collision detection in place, so if the turtle collides with any cars, the game is over.
- **Game Over and Winning:** If the turtle collides with a car, the game is over, and you lose. However, if you manage to reach level 10 without any collisions, you win the game.
- **Graphics and Animation:** The game utilizes the Turtle graphics module to create a visually appealing game environment with moving cars and a responsive turtle character.

## File Structure

The game's source code is organized into the following files:

- `main.py`: The main script to run the game.
- `cross_turtle.py`: Contains the class that represents the player-controlled turtle character.
- `car.py`: Defines the `Car` class that represents the moving cars on the road.
- `scoreboard.py`: Contains the class that displays the level and acknowledges Game Over condition.

## Dependencies

The game has the following dependencies:

- Python 3.x
- Turtle graphics module (included in the Python standard library)

## License

This game is released under the [MIT License](LICENSE).

Have fun playing and enjoy the Python road crossing game!
