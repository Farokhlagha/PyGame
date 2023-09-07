Snake Game manual and AI
Hi, the snake game developed by python.

This project inclode two type of game, manual and artificial intellgent. The manual version is in main.py and AI in main_ai.py.

This is version one and at this version of game, you have to eat fruit, as you know!

The apple has one score and pear has two score but eating the shit decrease one score.

You can move snake by navigation keys.

_game

You will lose if:

1- your score decrease to zero by eating shit.

_gameover_cross

2- your snake collision with itself.

_gameover_cross

3- your snake collision with edge of the game.

_gameover_out

Artificial Intelligent
Algorithm: The snake check if the path to pear is free, else check if the path to apple is free, else continues on its way. For check the path, algorithm create rectangle from snake head to target, if path is free this rectangle is blue else is red. Rectangle plot if self.debug is true. If in next step snake collision fance, snake change direction to pear and if in next step snake collision itself, snake change direction to free space.