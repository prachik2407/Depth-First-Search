# Depth-First-Search
Python Code
The code I've written is a Python implementation of the **Depth-First Search (DFS)** algorithm. DFS is an algorithm for traversing or searching tree or graph data structures. It starts at the root (selecting some arbitrary node as the root in the case of a graph) and explores as far as possible along each branch before backtracking.

Here's how code works:
1. Defined a graph as a dictionary where each key-value pair represents a node and its adjacent nodes.
2. Also defined an empty list `visited` to keep track of the nodes that have been visited during the search.
3. The `dfs` function is defined to perform the depth-first search. It takes three parameters: `visited`, `graph`, and `node`. The `node` parameter represents the current node being visited.
4. Inside the `dfs` function, if the current node is not in the `visited` list, it is printed and added to the `visited` list.
5. Then, for each neighbor of the current node, the `dfs` function is called recursively.
6. Finally, you call the `dfs` function with `'5'` as the starting node.

When you run this code, it will print the nodes visited during the depth-first search, starting from node `'5'`. The order of the nodes printed represents the order in which they were visited. 
