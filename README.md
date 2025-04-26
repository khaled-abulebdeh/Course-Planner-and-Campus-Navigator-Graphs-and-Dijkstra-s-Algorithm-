
# Course Planner and Campus Navigator (Graphs and Dijkstra's Algorithm)

## Overview

This project helps 1st-year university students by:

- Finding the **shortest path between two campus buildings** using **Dijkstra's Algorithm**.
- Sorting the **courses they must take** using **Topological Sort**.

The system is fully implemented in **C Language** using adjacency lists and graph data structures.

---

## Files

| File | Description |
|:-----|:------------|
| `main.c` | Main C source code implementing graphs for courses and buildings. |
| `input_buildings.txt` | Input file containing building connections and distances. |
| `input_courses.txt` | Input file containing courses and their prerequisites. |
| `Project_Description.pdf` | Full project assignment description and requirements. |

---

## Features

- Load building distances and course prerequisites from files.
- Find and display the shortest route and total distance between two buildings.
- Sort courses based on prerequisite dependencies using topological sorting.
- Display sorted list of courses in correct order.
- Handle invalid inputs and missing data gracefully.

---

## Requirements

- C Language (Standard C)
- Graphs and Linked List concepts
- Understanding of Dijkstra's algorithm and Topological Sort
- Input files `input_buildings.txt` and `input_courses.txt` must be available
