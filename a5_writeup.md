# Assignment 5 Write up

Assignment 5 can be broken up into the following parts:
1. Import the Necessary Modules:
- `copy`: For creating deep copies of objects
- `Stack` and `Queue`: Custom implementations for DFS and BFS operations
2. Utility Functions: 
- `remove_if_exists`: Removes a specified element from a list if it exists, which is used to remove the possibilites from a cell
3. Board Class:
- Represents the Sudoku board
- Consists of functions that will find the most constrained cell, and update the board, which eliminates possible solutions
4. DFS & BFS Functions:
- `DFS`: Uses depth-first search to solve the Sudoku puzzle. It works by trying to fill the most constrained cell with potential values until a solution is found or backtracks if a mistake is made
- `BFS`: Uses breadth-first search to solve the Sudoku puzzle in a similar fashion to DFS but explores nodes level by level
5. Main Execution:
- Defines two different sets of initial moves for Sudoku puzzles
- Uses both DFS and BFS to solve each puzzle and prints the results


After completing the assignment, answer the following reflection questions:

## Reflection Questions

1. What are some things that you learned through this assignment? Think about the concepts of backtracking, constraint satisfaction, and search algorithms. Were there any particular challenges you faced while implementing the Board class methods or the DFS/BFS functions? How did you overcome them?

I learned how to use the different methods of iteraion. The BFS and DFS were the hardest bpart of the project because it required me to not only understand what they were but the different steps they go through. I struggled much with the BFS function. I did not have an initial understanding of what it exactly did. I attempted to overcome it by using the DFS function that was given and having it as a guide. This proved somewhat useful as I got a loose understanding and a somewhat correct code. I the used ChatGPT to help fix it and explain my errors to me. I had a better code than the inital one but it was stil not very good and I resorted to the one given.

2. How can you apply what you learned in this assignment to future programs or projects? Consider other types of problems that involve searching through possibilities, making decisions, and backtracking when those decisions don't work out. Can you think of real-world scenarios where DFS or BFS might be useful? What about other constraint satisfaction problems?

I can apply what I learned form this assignment into future programs to create problem solving codes. In cases where a code is needed to check possible answers I can use this code to go through all possible answers quickly and bring back the correct one. DFS and BFS would be useful when sorting through possibilities or answers. DFS and BFS can be useful with games such as chess, it can also be used in gps to get the best route, it can also be used for mazes to find the correct exit. 

3. Explain how the Stack and Queue classes work and why they are important for DFS and BFS algorithms. Describe the difference between LIFO (Last In First Out) and FIFO (First In First Out) data structures. How does using a Stack versus a Queue change the way the search algorithm explores possible solutions? Why is one data structure better suited for depth-first search and the other for breadth-first search?

Stacks are like plates they are added and taken from the top. Queues are like lines it takes the first one and then pushes the rest to the back. In LIFO it used in stacks and the last item added is grabbed first and is used deep exploration. In FIFO it is used in queues and the first item is removed first and is used for broad explorations. DFS uses  stacks because it allows for each possibility to be run and allows for deeper exploration into the possibilities. BFS uses queue because it goes through everything in a line so it is better for broad searches. Queue is better for BFS because each one is explored individually. Stack is better for DFS because it is a deep search backtracking information that was taken in. 