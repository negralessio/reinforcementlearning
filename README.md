# Reinforcement Learning -- Theoretical Introduction and Applications

During my bachelor thesis at Karlsruhe Institute of Technology I introduced the theoretical aspects of Reinforcement Learning.
To amplify the theory I implemented RL algorithms that are foundamental in this area of study. Namely:
* Value Iteration
* Q-Learning

## Application :rocket:
We applied Value Iteration and Q-Learning to the following 3x4 grid world to keep things simple.

<img src="assets/grid.png?raw=true" width="600" height="350">

# 
The jupyter notebook "q_learning_pokemon" contains the Q-Learning algorithm to find the shortest path to the pokemon as seen below:

<img src="assets/pokemon_gridworld_only_charmander_solution.png?raw=true" width="600" height="350">

#
The return of each episode, i.e. the sum of rewards, can be seen in the following graph. The number of high return episodes increases with the number of episodes. The variance is because

<img src="assets/pokemon-rewards-per-episode.png?raw=true" width="600" height="350">