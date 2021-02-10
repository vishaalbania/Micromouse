# Micromouse
Problem Statement: 
Providing a solution and designing a sustainable system to demonstrate the micro-mouse problem using a suitable algorithmic approach.
Approach:
The problem has been solved using the A* search alogorithm and it has been coded using Python.
Elaboration:
I have used the A* algorithm, which is used to calculate the shortest path between two points ideally the source and the destination,
when there are multiple obstacles loaded between them.
A* algorithm is better unlike other naive algorithm since at each step it picks the node according to a value-‘f’ which is a parameter equal to the sum of two other parameters – ‘g’ 
and ‘h’. At each step it picks the node/cell having the lowest ‘f’, and process that node/cell.We define ‘g’ and ‘h’ as simply as possible below
g = the movement cost to move from the starting point to a given square on the grid, following the path generated to get there. 
h = the estimated movement cost to move from that given square on the grid to the final destination. This is often referred to as the heuristic, 
which is nothing but a kind of smart guess.
We really don’t know the actual distance until we find the path, because all sorts of things can be in the way (walls, water, etc.). 
Idea behind the code:
1. decided to create a square grid and definded different color constants using RGB values to identify the source, destination and the obstacles.
2. created a class to remember the space where the spots are created and their locations as well.
3. we wanted to know the state of each block which is initally set to white, else it's set according to the value of the color constants provided.
4. we then created the actual grid for visualization.
5. calculated the distance between each points(heuristic distance).


User guide:
I have already converted the '.py' file into an '.exe' as you can easily locate inside the dist folder!
In order to run the file I do simply download that exe file or if you do have python you can directly run the .py file!


