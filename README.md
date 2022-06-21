In this assignment, you are going to write a program that solves the eight puzzle problem. You
will solve it using
1) [20 points] Iterative deepening depth-first search (100 cases in the given file)
2) [20 points] Breadth First Search (If it takes too long in your BFS, you need to give the
results based on at least 10 cases. But you will lose 5 points.)
To test your program and analyze the efficiency, you need to test your program on the 100
different input cases. The input data is Input8PuzzleCases.txt. This file contains a hundred
different states of 8-puzzle. All the given cases are solvable.
An 8-puzzle case is given in the format as the following line,
3, 2, 4, 5, 8, 6, 0, 1, 7
means state
3 2 4
5 8 6
0 1 7
You need to find solutions for all 100 different states to the goal state.
The Goal state is
0 1 2
3 4 5
6 7 8
Requirements:
1. The search algorithms must be programmed by you. Plagiarism will be filed.
2. You are required to use the given IPython Notebook file to do this assignment.
3. You need to install Anaconda Environment to use the notebook file. Refer to the
following links.
a. https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook
b. https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/
4. You are required to follow the notebook file’s requirement to print out results.
5. The search algorithms must be implemented by you! That means you are not allowed to
import Iterative deepening depth-first search or BFS from other libraries. Otherwise,
the assignment will receive 0.
CS461 Advanced Artificial Intelligence
6. You need to follow our class to design your program. For example, you need to
implement a frontier queue. 