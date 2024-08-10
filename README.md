# RL-Project-3
SARSA_Q-Learning

Hey there! Welcome to my reinforcement learning project, where I’ve been diving deep into some cool RL algorithms like Sarsa, Q-Learning, and a few others. The main focus here is solving challenges like navigating through a grid world and tackling a random walk problem.

## What’s This Project About?

I split this project into two main parts:

***Grid World Challenge:*** Here, I set up a scenario where an agent (starting in one spot on a grid) needs to figure out how to reach a terminal state while avoiding high-cost areas. I used Sarsa and Q-learning to help the agent learn the best strategy for navigating through this tricky environment.

***Random Walk Adventure:*** This one’s about a random walk on a 7x7 grid. The goal was to compute the value of different positions using methods like Gradient Monte Carlo and Semi-Gradient TD(0), and then compare these values to the exact solution. Spoiler: It was super interesting to see how they stack up!

To get this project running on your machine, you’ll need a few Python libraries:

* numpy
* matplotlib
* seaborn
* collections
* random


### Results and Findings
**Grid World Results**
Visualizing the Learned Policies: After training, I plotted the policies that Sarsa and Q-learning learned. It’s really interesting to see how different (or similar) they turn out!

**Rewards Per Episode:** I also tracked the sum of rewards for each episode, so you can see how the agent’s learning progresses over time.

### Random Walk Results
**Value Function Heatmaps:** I visualized the value functions that I got from Gradient Monte Carlo, Semi-Gradient TD(0), and the exact solution. It was pretty cool to see the differences and similarities.

**Policy Visualization:** I also plotted the policies derived from these value functions to compare how well each method performed.

### Contributing
If you’ve got any ideas to improve this project or if you find a bug, I’d love to hear from you! Feel free to fork the repo, make your changes, and submit a pull request. Let’s make this project even better together.
