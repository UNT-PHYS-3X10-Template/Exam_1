# Exam 1 Take-Home Project

In this project you will implement a code to simulate the motion of non-interacting particles inside a box. The simulation 
The project is organized into four tasks. Although each following task can be implemented as a modification of the same starting code, 
in order to simplify and guide your work four different python files have been created in this repository. 

TASKS:
1. Starting from the task1.py program, implement a function to move a particle inside a one-dimensional box. The particle follows a uniform velocity motion along the x axis. The particle has no interactions with other objects, but it can undergo elastic collisions with the sides of the box. 
2. Starting from the task2.py program, and the developments in the previous task, extend the program to account for a variable number of particles. Initialize the positions and velocities of the particles using random numbers. 
3. Starting from the task3.py program, and the developments in the previous two tasks, extend the program to model non-interacting particles in two dimensions. Initialize the positions and velocities in the two directions using random numbers.
4. Starting from the task4.py program, and the developments in the previous three tasks, modify the program to implement a random-walk motion for the particles: at each timestep the particle moves according to a uniform velocity motion, but after the move the velocity is changed randomly. 

OPTIONAL TASKS:
1. For tasks 1-4, modify the program to count the number of collisions with the box walls per particle. How is this number related to the speed of the particle? 
2. For tasks 2-4, modify the program to count the number of encounters between particles. Since the particles do not really interact with each other, two particles can be considered to encounter when their distance is within a certain small threshold. 

