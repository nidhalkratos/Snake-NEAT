# Snake-NEAT
Integrating Neural Evolution In Augmented Topologies in a snake game to make it a self learner.

![alt text][logo]

[logo]: https://github.com/nidhalkratos/Snake-NEAT/blob/master/screen_shot_1.jpg "ScreenShot 1"

# Requirements
This projects requires pygame python library as well as python-neat library

# Running
To run this game you need to execute the game file inside the project folder with python.  
```bash
./game
```
You can change the game speed to make it run faster(Thus learn faster) by decreasing the speed local varibale in the eval_fitness function in the game file.  
You can change the screen width and height by changing the content of the global variables width and height.(You should not make each of them more than 20 pixels)
Note we only tested the project with python 2.7 .

## Saving knowledge
Whenever you quit the game a new file called "population.dat" gets created. That file contains all the knowledge learnt so far.
## Loading knowledge
In order to load knowledge , open up the game with the population file as a terminal argument.
```bash
./game population.dat
```

# Notes
The game is still under development. The snake is still not able to always go to the food.

