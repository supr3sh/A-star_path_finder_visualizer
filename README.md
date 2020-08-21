# A-star_path_finder_visualizer
Like Dijkstra, A* works by making a lowest-cost path tree from the start node to the target node. What makes A* different and better for many searches is that for each node, A* uses a function f(n)f(n) that gives an estimate of the total cost of a path using that node. Therefore, A* is a heuristic function, which differs from an algorithm in that a heuristic is more of an estimate and is not necessarily provably correct.

A* expands paths that are already less expensive by using this function:
    f(n)=g(n)+h(n),
    f(n)=g(n)+h(n),
where

f(n)f(n) = total estimated cost of path through node nn

g(n)g(n) = cost so far to reach node nn

h(n)h(n) = estimated cost from nn to goal. This is the heuristic part of the cost function, so it is like a guess.

 I created this project using pygame. 
 How to use this project:
 
 First click on any cube to make it the starting node.
 Next, select any node to make it ending node.
 
 Then create barriers. 
 If you want to change your selection, just right-click on it.
 
 Then press the Space button to start the algorithm.
 
 After the algorithm has run, to reset the screen, press C.
