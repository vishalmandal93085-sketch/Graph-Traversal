Breadth-First Search (BFS) in C

This repository contains a simple implementation of the Breadth-First Search (BFS) algorithm in C using an adjacency matrix and a queue.

📌 Description

Breadth-First Search (BFS) is a graph traversal algorithm that explores vertices level by level. Starting from a given source vertex, it visits all its adjacent vertices before moving on to the next level.

This implementation:

Uses a fixed-size queue

Tracks visited nodes to avoid revisiting

Works on an undirected graph represented as an adjacency matrix

🧠 How the Algorithm Works

Start from a given node.

Mark it as visited and enqueue it.

Dequeue a node, print it, and enqueue all its unvisited adjacent nodes.

Repeat until the queue is empty.

🛠️ Code Features

Fixed-size queue implementation

Adjacency matrix representation

BFS traversal starting from node 0

Simple and beginner-friendly C code
