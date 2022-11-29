_**8-Puzzle-Game**_

_8 Puzzle Game_ - simple sliding tiles on a 3x3 grid. You are allowed to move along with empty block, one step at a time. The puzzle is said to be solved, when it has sequential arrangement of the numbers.This game solves using an A* search algorithm. 

This is how you start solving the puzzle:
  1) Get the first state, which is your start state.
  2) Get all the possible states in which puzzle can be.
  3) Add these new states in open state list
  4) Add processed sate in the closed list
  5) Pick the next state which has the lowest cost in the open list
  6) Start repeating the steps from 1 to 6 unless you are into the final state, or no more states to examine (in this case, no solution exists).
  7) Once you have the final state, backtrack to the start node and that would be the optimal path to find the solution.

![8Puzzle](https://user-images.githubusercontent.com/111874834/204497596-e6fd9190-43ad-41d2-8ff7-81d9f61b81e1.png)
