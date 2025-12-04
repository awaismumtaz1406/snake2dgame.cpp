Snake Game in C++

This is a simple 2D Snake Game written in a single C++ source file named snake2dgame.cpp. The game runs in the console and uses basic logic for movement, food generation and collision detection.

Features

Single-file C++ implementation

Keyboard control for movement

Food appears at random positions

Score increases when the snake eats food

Game over on hitting the wall or the snake’s body

File Included
snake2dgame.cpp

How to Compile and Run

Open your terminal in the folder that contains snake2dgame.cpp, then run:

g++ snake2dgame.cpp -o snake
./snake


For Windows (MinGW):

g++ snake2dgame.cpp -o snake.exe
snake.exe

How to Play

Use arrow keys or WASD to move the snake

Eat food to increase your score

Avoid hitting walls or your own tail

The game ends on collision

Requirements

A C++ compiler (g++, clang++, or MSVC)

Console environment (no external libraries needed)

Possible Improvements

Add difficulty levels

Add a high score file

Add colors for better visuals

Add pause and resume controls

License

Free to use and modify for learning.
