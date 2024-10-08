# RL-Project-3
SARSA_Q-Learning

Welcome to my reinforcement learning project, where I explore key RL algorithms like Sarsa, Q-Learning, Gradient Monte Carlo, and Semi-Gradient TD(0). This project focuses on solving two main challenges: navigating through a grid world and tackling a random walk problem.


## What’s This Project About?

**Project Structure**

**1. Grid World Challenge**

In this part, an agent starts at a specific position on a grid and needs to find the best way to reach a terminal state while avoiding penalty areas. I used Sarsa and Q-learning to help the agent learn optimal strategies for navigating this environment.

**2. Random Walk Adventure**

This part involves a random walk on a 7x7 grid. The goal is to compute the value of different positions using Gradient Monte Carlo and Semi-Gradient TD(0) methods and compare these values to the exact solution. It was fascinating to observe the performance differences between these methods.

To get this project running on your machine, you’ll need a few Python libraries:

* numpy
* matplotlib
* seaborn
* collections
* random



### Results and Findings

### Grid World Results

***Visualizing the Learned Policies:*** After training, I plotted the policies that Sarsa and Q-learning learned. It’s interesting to see the differences and similarities in the paths they suggest.

**Rewards Per Episode:** I tracked the sum of rewards for each episode, providing insight into the agent’s learning progression over time.

### Random Walk Results

***Value Function Heatmaps:*** I visualized the value functions derived from Gradient Monte Carlo, Semi-Gradient TD(0), and the exact solution. The comparisons highlighted the strengths and limitations of each method.

***Policy Visualization:*** I also plotted the policies based on these value functions to evaluate the performance of each approach.


### Doing this Project I got help from:

1. The class lectures content
2. YouTube
3. These websites:

(https://www.cs.mcgill.ca/~dprecup/courses/Winter2022/Lectures/10-prediction-fa-2022.pdf)

(https://jmlr.org/papers/volume21/19-346/19-346.pdf)


### Contributing
If you’ve got any ideas to improve this project or if you find a bug, I’d love to hear from you! Feel free to fork the repo, make your changes, and submit a pull request. Let’s make this project even better together.
