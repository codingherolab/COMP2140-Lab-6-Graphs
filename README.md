# COMP2140-Lab-6-Graphs

Download Here: [COMP2140 Lab 6: Graphs](https://codingherolab.com/product/comp2140-lab-6-graphs/)

For Custom/Original Work email codingprolab@gmail.com/whatsapp +1(541)423-7793

Objective
To write code to compute the in-degree of every vertex and to print out the vertices visited in a depth-first traversal
starting at Vertex 0, for an adjacency-list implementation of a directed graph.
In-Degrees and a Depth-First Traversal
Get a copy of GraphAL.java (an adjacency-list implementation). Get a copy of the graph file graph.txt which lists
the number of vertices (5) and edges between them. Write the body of the method printIndegrees, which prints out
the in-degree of each vertex in the graph. Also, write the body of the method recursiveTraversal, which performs
a recursive depth-first traversal of the graph starting at the vertex given by parameter currVertex, printing out a
vertex when the traversal visits it.
The steps of a recursive depth-first traversal at currVertex:
• Visit currVertex;
• for each vertex i that is adjacent to currVertex (i.e., such that there is an edge from currVertex to i)
• if vertex i has not yet been visited do a recursive depth-first traversal at i
The intent is to see which vertices can be reached if you start at vertex 0, and what order you would visit them
in.
