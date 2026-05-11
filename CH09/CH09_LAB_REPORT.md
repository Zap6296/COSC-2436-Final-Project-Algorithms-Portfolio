# Chapter 9: Dijkstra's Shortest Path - Lab Report

## Student Information
- **Name:** Nathaniel Tryon
- **Date:** 4/15/26

## Algorithm Summary
- **How it works:** Finding the shortest path between nodes in a graph. Like BFT search but now didtance betwween points is in play 
- **Time complexity:** Null
- **When to use it:** finding the shortest path and time to take that path on a map

## Program run
=== Dijkstra's Shortest Path ===

Enter node names one per line.
Type 'done' when finished.

Node: road 1
  Added: road 1
Node: road 2
  Added: road 2
Node: road 3
  Added: road 3
Node: road 4
  Added: road 4
Node: road 5
  Added: road 5
Node: done

For each pair of nodes, enter the edge weight if connected, or press Enter to skip.

  road 1 <--> road 2  (weight or Enter to skip): 5
    Added: road 1 <--5--> road 2
  road 1 <--> road 3  (weight or Enter to skip): 6
    Added: road 1 <--6--> road 3
  road 1 <--> road 4  (weight or Enter to skip): 8
    Added: road 1 <--8--> road 4
  road 1 <--> road 5  (weight or Enter to skip): 9
    Added: road 1 <--9--> road 5
  road 2 <--> road 3  (weight or Enter to skip): 1
    Added: road 2 <--1--> road 3
  road 2 <--> road 4  (weight or Enter to skip): 2
    Added: road 2 <--2--> road 4
  road 2 <--> road 5  (weight or Enter to skip): 3
    Added: road 2 <--3--> road 5
  road 3 <--> road 4  (weight or Enter to skip): 4
    Added: road 3 <--4--> road 4
  road 3 <--> road 5  (weight or Enter to skip): 6
    Added: road 3 <--6--> road 5
  road 4 <--> road 5  (weight or Enter to skip): 4
    Added: road 4 <--4--> road 5

────────────────────────────────────────────────────
  GRAPH
────────────────────────────────────────────────────
      (road 1)  <->  5       (road 2)
      (road 1)  <->  6       (road 3)
      (road 1)  <->  8       (road 4)
      (road 1)  <->  9       (road 5)
      (road 2)  <->  1       (road 3)
      (road 2)  <->  2       (road 4)
      (road 2)  <->  3       (road 5)
      (road 3)  <->  4       (road 4)
      (road 3)  <->  6       (road 5)
      (road 4)  <->  4       (road 5)
────────────────────────────────────────────────────

Nodes: road 1, road 2, road 3, road 4, road 5
From: road 1
To:   road 5

────────────────────────────────────────────────────
  GRAPH
────────────────────────────────────────────────────
      [road 1]  <=>  5       [road 2]
      [road 1]  <->  6       (road 3)
      [road 1]  <->  8       (road 4)
      [road 1]  <->  9       [road 5]
      [road 2]  <->  1       (road 3)
      [road 2]  <->  2       (road 4)
      [road 2]  <=>  3       [road 5]
      (road 3)  <->  4       (road 4)
      (road 3)  <->  6       [road 5]
      (road 4)  <->  4       [road 5]
────────────────────────────────────────────────────
  [node] = on shortest path    (node) = not on path    <=> = path edge    <-> = other edge

  Shortest path: road 1 -> road 2 -> road 5
  Total cost:    8


