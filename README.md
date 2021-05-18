# Treasure_Hunters_Inc

The main goal of this project is to understand Reinforcement Learning and solve a map like environment.

## Algorithms:
For this project, I used Q-Learning to solve a maze designed with Obstacles, Opponents and Treasures at different positions in the maze.

## Explanation:
The implementation of Q-Learning algorithm is located in the Notebooks folder.

## Reinforcement Learning:

Reinforcement algorithms can be used to train an agent to solve environments without any prior information. In this project, the agent needs to navigate from start till final destiantion and collect most of the treasures while avoiding obstacles and opponents. RL is used to make the optimal decisions. The reward system is used to evaluate different scenarios, an environment where the tasks need to be performed and different states to make transition or take an action. The agent will receive more reward for an obstacle free state and for avoiding opponents. The training should be done multiple times until the agent learns how to navigate through the maze, to know the state-actions, rewards and penalties. 

The optimal path traversal is solved using the principles of QLearning to update the Q matrix to maximize the rewards. This algorithm uses exploration and exploitation to get the optimal path. Once, training is done the optimal path can be obtained by taking optimal moves at each state based on the Q matrix. The Q learning strategy includes immediate reward based on the action and quality of the action based on the moves for the agent learning experience. We can observe from the last two plots, the optimal path collecting all the treasures till agent reaches the destination.

Detailed explanation can be found in the notebook.

## Conclusions:

From the plots we can observe that Q Learning algorithm achieved great results. From the paths obtained, we can see that the agent navigated from start point to end point without touching any obstacles and opponents. The optimal paths atmost covered all the treasures in the maze. The future work will be adjusting the parameters used for training the agent to get more optimal paths.



## References:
https://visualstudiomagazine.com/articles/2018/10/18/q-learning-with-python.aspx </br>
https://towardsdatascience.com/introduction-to-q-learning-88d1c4f2b49c </br>
https://www.freecodecamp.org/news/an-introduction-to-q-learning-reinforcement-learning-14ac0b4493cc/ </br>

## Steps to execute:
1. Download the files from the github repository.
2. The notebooks folder should have ipynb file.
3. Navigate to terminal and type "jupyter notebook"
4. Navigate to the folder where the notebooks are placed.
5. From the menu icon cell, select the notebook and click on Run all which will run the whole notebook from the first cell.

## Steps to follow:
1. We do the treasure hunting and monster fighting for you
2. Set up a new git repository in your GitHub account
3. Think up a map-like environment with treasure, obstacles and opponents
4. Choose a programming language (Python, C/C++, Java)
5. Formulate ideas on how reinforcement learning can be used to find treasure efficiently while avoiding obstacles and opponents
6. Build one or more reinforcement policies to model situational assessments, actions and rewards programmatically
7. Document your process and results
8. Commit your source code, documentation and other supporting files to the git repository in GitHub
