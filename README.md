# 🚚 Vehicle Routing Problem (VRP)

## 📌 Overview
The **Vehicle Routing Problem (VRP)** is a classic optimization problem where the objective is to determine the most efficient routes for a fleet of vehicles to serve a set of customers, subject to constraints such as vehicle capacity and minimum travel distance.

This project implements a solution to the Vehicle Routing Problem using algorithmic optimization techniques to minimize total distance while ensuring all customers are served efficiently.

---

## 🎯 Problem Statement
Given:
- A depot (starting and ending point)
- Multiple customers with known locations
- A fleet of vehicles with limited capacity

Goal:
- Assign customers to vehicles
- Determine optimal routes
- Minimize total travel distance
- Ensure capacity and routing constraints are satisfied

---

## 🧠 Approach
The problem is solved using:
- Distance matrix computation
- Route construction heuristics
- Optimization techniques (Greedy / Heuristic / Metaheuristic based)

Key steps:
1. Compute distances between all locations
2. Assign customers to vehicles based on constraints
3. Optimize route ordering
4. Calculate total distance for each vehicle

---

## ⚙️ Technologies Used
- **Programming Language:** Python  
- **Libraries:**
  - `numpy`
  - `math`
  - `matplotlib` (for visualization)
  - `itertools`

---

