# Sudoku-using-graph-coloring
This project solves the sudoku problem with representing the grid in graph form and using graph coloring concept for solving the blanks
Idea Name: Solving Sudoku problem using graph coloring(with backtracking concept)
Idea description:
Sudoku:
Sudoku is a logic based combinatorial number placement game,Where we have to fill in the left
places of 9*9 grid in which there are 9 sub grids with 3*3 placements of digits 1 to 9.The digits
should occur distinctly in 3*3 subgrid and also with the respective rows and column.This will
lead to the distinct solution for the problem.Hence while solving this problem we have to
primarily aim for completing 3*3 grid without repetition and then we have to check row wise and
column wise for altering the placement of respective digit. While placing the digits we should
also check the scope for future digits which are to be placed which makes the game complex
and logical.If you have chosen a wrong position then it will affect the whole grid.We can solve
this program using graph coloring.
Graph coloring:
It is a concept of labeling the elements(vertices/edges..) of the graph as per our requirement.We
generally label with color for better identification.For example if we are searching for a element
we have to mark the element which is already checked,which is been checking,which is about to
be checked.We have to mark 3 labels for them hence we use this concept of graph coloring.
For solving the problem of sudoku we can assume the blanks as nodes in a graph since they
should be distinct with each other in the grid and in the row and column.For solving this, we will
label each digit with a distinct color which gives 9 labels.We have now a clear statement of
problem that is
There should be distinct colors in the row and column
We interlink the nodes in subgraph of 3*3 such that we can easily assign distinct color
by observing the adjacent elements
Project goals:
1-Representing sudoku grid in the form of graph by which we can easily assign distinct numbers
to the blanks
2-Separating subgrid from the main grid in the graph
3-Interlinking the segments of rows and columns in the subgrid so that there won’t be
overlapping
4-Assigning colors in the graph with the algorithm we want to proceed
5-Using backtracking for assigning distinct colors for graph coloring
6-backtracking idea should also be extended to both row wise & column wise with grid as main
domain for correct assignment
References:
1-http://www.phys.ens.fr/~monasson/Articles/a51.pdf
2-https://www.researchgate.net/publication/344016939_Applications_of_Graph_Coloring_in_Mo
dern_Computer_Scienc
