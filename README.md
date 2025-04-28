# SE601_Project: VRP in a Smart Logistics System

## Introduction 🚚
The Vehicle Routing Problem (VRP) is a core challenge in logistics, focusing on minimizing travel distance and improving delivery efficiency. Smart logistics systems apply data and optimization algorithms to enhance delivery performance.  
This project demonstrates VRP techniques using a public distance matrix dataset to optimize delivery routes.

## Case Study: Basic Route Optimization (Based on Distance Data)

### Company Profile 🏢
A delivery company operating in a major city 🌆 seeks to optimize its last-mile delivery operations 🚚.  
Their main goals:
- Minimize travel distances 📏
- Reduce fuel costs ⛽
- Improve overall delivery efficiency 📦

Deliveries are made from a central warehouse 🏢 to multiple customer locations 📍.

### Dataset Description 📝
The dataset includes:
- Customer locations 📍 (street names and notations like A, B, C)
- Distances from a central warehouse to each customer 📏
- Pairwise distances between all customer locations 📏

It models a VRP scenario **without** complex constraints like vehicle capacity or time windows, focusing purely on **distance optimization**.

### The Challenge 😫
The company faced challenges:
- Manual, inefficient route planning 🛣️
- Longer total travel distances 📏
- Higher fuel and maintenance costs ⛽🛠️
- Difficulty scaling operations as customer numbers increased 📈

### The Smart Logistics Solution 💡
A smart logistics system was developed with key features:
1. **Data Preprocessing** ⚙️  
   Preparing the distance matrix 📏 and customer locations 📍 for algorithm processing.

2. **Route Optimization Algorithms** 🤖  
   Applied optimization methods included:
   - Nearest Neighbor heuristic 🔍
   - Genetic Algorithms 🧬
   - Simulated Annealing ❄️
   - Exact methods (e.g., Branch and Bound) 🌳
