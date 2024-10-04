# Lin-Kernighan Algorithm with Opposition-Based Learning (OBL)

This repository contains an implementation of the **Lin-Kernighan heuristic** for solving the Traveling Salesman Problem (TSP), with an additional comparison between using **Opposition-Based Learning (OBL)** and without OBL.

## Table of Contents
- [Overview](#overview)
- [Algorithms Implemented](#algorithms-implemented)
- [Dependencies](#dependencies)


## Overview
The **Lin-Kernighan** algorithm is a local search heuristic for the TSP. It attempts to improve a given tour by performing k-opt moves, where edges in the tour are swapped to reduce the total distance traveled.

This implementation also includes **Opposition-Based Learning (OBL)**, where after each iteration of improvement, an "opposite" tour is generated and evaluated. If the opposite tour provides a shorter distance, it is used as the new current tour.

## Algorithms Implemented
1. **Lin-Kernighan Algorithm (Without OBL)**: Standard Lin-Kernighan heuristic that uses 2-opt moves to iteratively improve the solution.
2. **Lin-Kernighan Algorithm (With OBL)**: This version includes Opposition-Based Learning, where an opposite tour is generated and evaluated at each iteration.

## Dependencies
This code requires the following Python libraries:
- `numpy`

You can install the required dependencies using:
```bash
pip install numpy
