# Snake Game manual and AI
Move snake by navigation keys.

![snake](https://raw.githubusercontent.com/Farokhlagha/PyGame/main/PyGame15_Snake/pictures/snake.png)

You will lose when your score decrease to zero by eating shit.

Game over when snake collision with itself or snake collision with edge of the game.

Artificial Intelligent
Algorithm:

 The snake check if the path to pear is free, else check if the path to apple is free, else continues on its way. For check the path, algorithm create rectangle from snake head to target, if path is free this rectangle is blue else is red. Rectangle plot if self.debug is true. If in next step snake collision fance, snake change direction to pear and if in next step snake collision itself, snake change direction to free space.