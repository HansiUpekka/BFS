# Breadth-First Search (BFS) Program

## Overview
This program implements the Breadth-First Search (BFS) algorithm in C. BFS is a fundamental graph traversal algorithm that explores all the vertices of a graph level by level.

## Features
- Traverses a graph using the BFS algorithm.
- Supports graph input from a file.
- Outputs the traversal path.

## How to Compile and Run

### Prerequisites
- GCC compiler installed on your system.

### Steps:
1. Clone or download the code.
2. Open a terminal and navigate to the code directory.
3. Compile the program using the following command: <br>
   bash <br>
      " gcc bfs.c -o bfs "
5. Run the program: <br>
   bash <br>
     " ./bfs graph.txt " <br>
     Replace <graph_file> with the name of the file containing the graph data "graph.txt".<br>

### Input Format
The program reads graph data from a file. The input file should have the following format:
1. Number of vertices (nodes) in the graph.
2. Adjacency matrix representing the graph.

Example `graph.txt`:

4
0 1 1 0
1 0 1 1
1 1 0 0
0 1 0 0


### Output
The program outputs the BFS traversal path starting from a source node.

## Example Usage

### Input:
Graph file content (`graph.txt`):

4
0 1 1 0
1 0 1 1
1 1 0 0
0 1 0 0


Command to run: <br>
bash <br>
  " ./bfs graph.txt "


### Output:

BFS Traversal: <br>
     " 0 -> 1 -> 2 -> 3 "


## Known Issues
- Ensure the graph input file is formatted correctly.
- Check buffer sizes in the program to avoid overflow errors.

## License
This code is open-source and available for educational purposes.

## Author
Name:            Hansi Upekka Sithumini. <br>
Section Numbers: 7.   <br>
Email Address:   hansiupekkasithumini2002@gmail.com. <br>

