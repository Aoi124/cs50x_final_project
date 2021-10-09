# Breakout clone
## Description of Project
This is my final project for Harvard CS50x course. This project is to develop our own software by using the programming knowledge we have learned in class. I learned Python for the first time in the class, and I would like to learn more about it in the future, so I made a game using Python this time. I didn't have enough knowledge to make this game, so I read several reference books before making the game.

### Video Demo: https://youtu.be/GTHPe0lHj0o

### About This Game
The breakout game is the game which we reflect a moving ball by bar. The speed of the ball will change depending on the angle at which it is hit. If we break all block by ball, it is game clear. However, when you drop a ball, it is game over. In my game, if you be game over or game clear it will make a reset button and you can do 1 more time. The difficult part of this game is to guess the movement of the ball and try not to drop it. Reflections on the blocks make it difficult to guess the ball's movement. It will be a very exhilarating feeling when you break all the blocks.
These data are written in `block.py`.

## Pygame
This game is made by pygame. Pygame is one of library of python with many useful tool.
For example:
1. We can display window for game.
2. We can move or display graphic.
3. We can investigate what keyboard or mouse type.
4. We can make a sound.

You can also use pygame to make Invader games or Mario-like games. I'm planning to try it later.

## How to install pygame
This library can be use by any people if you install. If you want to use pygame, please access the following URL.

https://www.pygame.org/wiki/GettingStarted

`pip install pygame`

> Pygame requires Python. If you don't already have Python, you can download it from python.org. Use python 3.7.7 or greater, because it is much friendlier to newbies, and additionally runs faster. The best way to install pygame is with the pip tool (which is what python uses to install packages). Note, this comes with python in recent versions. We use the --user flag to tell it to install into the home directory, rather than globally.

## How to play this game
1. Clone or download this project.
2. Run the `block.py` file to play the game.
3. You can use the mouse or your finger to control the bar, so try to bounce the ball well and remove all the blocks.
4. If you can't clear the game no matter how many times you try, you may want to open the file and try resizing the ball.

`ballimg = pgtransform.scale(ballimg,(40,40))`

Changing this number will change the size of the ball.

## Requirement
- Python 3.9.7 and above
- Pygame module

## Note / Dear CS50 Learner
I install pygame in CS50 IDE, but it doesn’t work. I did in ~/project/. However, there is an error says “No available video device”. I use the reddit to solve problem but I can solve so I use IDLE to make this game.

If you know how to move pygame in CS50 IDE, please tell me in the comment.

