8-puzzle solver created during AI course in university, following S. Russell and P. Norvig book "Artificial Intelligence - A Modern Approach".

C#, .NET 4.5

Includes unit tests and GUI application (WPF) for some vizualization.

![gif](http://i.imgur.com/vQtCeZf.gif)

Implemented algorithms:
- A*

A* can be used with Manhattan Distance heuristic function or without any heuristic function.

In GUI it is possible to choose board size, from 2x2 to 5x5 (can be not square). But starting from 4x4 it may take more time (such as 2-10 minutes) to find the solution and it finishes in reasonable time not for all inputs, using RBFS (A* works too but may take too much memory and crash).

