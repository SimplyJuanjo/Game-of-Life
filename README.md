# Game-of-Life Project

#ThirdProject: Let's sum up all I have learned this 2 weeks into a classy project: Game Of Life 

#Input information from Wiki:
#The universe of the Game of Life is an infinite, two-dimensional orthogonal grid of square cells, each of which is in one of two possible states, live or dead, 
# (or populated and unpopulated, respectively). Every cell interacts with its eight neighbours, which are the cells that are horizontally, vertically, or diagonally 
# adjacent. At each step in time, the following transitions occur:

  # - Any live cell with fewer than two live neighbours dies, as if by underpopulation.
  # - Any live cell with two or three live neighbours lives on to the next generation.
  # - Any live cell with more than three live neighbours dies, as if by overpopulation.
  # - Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.

#To sum:

  # - Any live cell with two or three live neighbours survives.
  # - Any dead cell with three live neighbours becomes a live cell.
  # - All other live cells die in the next generation. Similarly, all other dead cells stay dead.
  
  
  
#Intuition: I suppose I'll be needing a matrix of 0s and 1s to perfom the logic, and then some other module to transform the arrays into square cells dead(0) or alive (1)
#First I'll try module numpy for matrix manipulation
#Then I'll search the other module for visualization : matplotlib

#Func I'll need:
    # - Checking nearby cells (implemented)
    # - Updating next gen (implemented)
    # - Show actual gen (implemented)
    # - Func for 1 life cycle (implemented)
    # - Func for nth iterations (implemented)
