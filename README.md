# EECS-738-Project-4
Treasure hunt with reinforcement learning


# Goal
The point of this assignment is to create a map-like environment for an agent to navigate and find treasure, weaving around obstacles, using reinforcement learning.

# Approach
I implemented Q-learning because it has contextual feedback. The environment is set up as a graph of vertices with edges attached, represented as an adjacency matrix. There is a reward for each edge or each vertice (i.e., a vertice's edge to itself). Small numbers in the adjacency matrix > 0 are taken to be punishments, so they're enemies, large numbers are rewards like treasure and -1 represents edges where vertices aren't connected. I implemented this based on a tutorial for Q-learning as seen below.

# References
http://firsttimeprogrammer.blogspot.com/2016/09/getting-ai-smarter-with-q-learning.html
