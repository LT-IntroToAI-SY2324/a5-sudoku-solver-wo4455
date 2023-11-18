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

1. How do the performance and efficiency of the Depth-First Search (DFS) and Breadth-First Search (BFS) algorithms compare when solving Sudoku puzzles? In what scenarios might one approach be preferable over the other?
I think that BFS would be a more viable option in most cases, because of some technical differences. Even though it would need to run through multiple trees and technically be slower, I still think that BFS would be a better option because it covers a wider margain of possiblities in a shorter amount of time. Although which method you choose depends entirely on the scenario you are given, such as the depth/variety of what you are searching for. 


2. How did the choice of data structures (like the Stack for DFS and Queue for BFS) impact the implementation and functionality of the algorithms? Are there alternative data structures or design patterns that could have been used to achieve the same objectives?
Whether if its a stack or queue changes the implementation of BFS and DFS as DFS enters items from the top and removes from the top, while BFS adds items to the end and removes from the beginning. These differences create different functioning algorithms. Another pattern that could be used is looping through a list from start to end checking each individual possibility. 


3. Considering the current implementation, how might the Sudoku solver be adapted or extended for larger puzzles or different types of grid-based logic games? How can the lessons learned from this assignment be applied to real-world problem-solving or optimization challenges?
One way that the program could be extended for a larger puzzle is by changing the hardcoded values in the grid that is already set up, although other small changes would need to be made throughout the code in order for that to work. The lessons from this assignment could be applied to real-world problems becuase it is a reminder that there are multiple ways to solve the same problem, and sometimes you need to think about something a little differently in some situations. 

