# DFSearch

This Java program is used to find the cut vertices in a given undirected graph from file if there are any. 
  To Execute this program:
  1. create a text file to read. enter the numbers in terms of edges. ex: 1 2 means that 1 is connected to 2. go to the next line and keep building the graph.
  2. enter the name of the text file so that the scanner can read the graph. ex. sampleA.txt means enter just sampleA
  3. enter what vertex you would like to check in number format. ex: 4 = node 4.
  
  To run our program with our test graph, ENTER "samplea" (it is not case sensitive)  and you will get the correct output according to 
  that graph.
  To run another graph, enter your own text file with our edge representation. or simply change our numbers in our test file.
  
  This program uses linked lists to provide the adjacency matrix representation to build graph edges.
  once the edges are build the cut vertex is determined by checking 2 cases:
  
  1. the vertex is a root and has two or more children 
  2. the vertex is not a root and one of its children as a low value that is less than the vertex discovery time
