# Reinforcement Learning -- Theoretical Introduction and Applications

During my bachelor thesis at Karlsruhe Institute of Technology I introduced the theoretical aspects of Reinforcement Learning.
To amplify the theory I implemented RL algorithms that are foundamental in this area of study. Namely:
* Value Iteration
* Q-Learning

## Application :rocket:
I applied Value Iteration and Q-Learning to the following 3x4 grid world to keep things simple.

<img src="assets/grid.png?raw=true" width="600" height="340">

# 
## Q-Learning :joystick:
The jupyter notebook `q_learning_pokemon` contains the Q-Learning algorithm to find the shortest path to the Pokémon as seen below:

<img src="assets/pokemon_gridworld_only_charmander_solution.PNG?raw=true" width="600" height="350">

#
The return of each episode, i.e. the sum of rewards, can be seen in the following graph. The number of high return episodes increases with the number of episodes. The variance is due to how I implemented Q-Learning: In each episode, the agent starts at a random (valid) start state. Thus the return varies, since each state transition costs 0.05 and the only terminal state yields a reward of 100.

<img src="assets/pokemon-rewards-per-episode.png?raw=true" width="600" height="350">