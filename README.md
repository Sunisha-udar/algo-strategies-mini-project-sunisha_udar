# algo-strategies-mini-project-sunisha_udar
🚀 Algorithmic Problem Solving — Greedy & Dynamic Programming Approaches
📖 Overview

This repository contains four algorithmic problems implemented in Python, showcasing the use of Greedy and Dynamic Programming strategies across various real-world domains such as advertising, finance, scheduling, and optimization.

Each problem is implemented step-by-step with:
✅ Input data
✅ Algorithmic solution
✅ Analysis (time & space complexity)
✅ Visualization using matplotlib

**Problem 1: Scheduling TV Commercials to Maximize Impact**

Algorithm: Greedy (Job Sequencing)
Domain: Media and Advertisement

**Objective:** Schedule commercials (ads) within available slots to maximize total revenue.

**Approach:** Sort ads by profit (descending) and assign to latest available slot before deadline.

**Output:** Selected ad schedule and total revenue.

**Visualization:** Number of ads vs. revenue generated.

**Complexity:** Time – O(n log n), Space – O(n)

**Observation:** Revenue increases with more ads but stabilizes once all slots are filled.

**Problem 2: Maximizing Profit with Limited Budget**

Algorithm: Dynamic Programming (0/1 Knapsack)
Domain: Investment and Budget Planning

**Objective:** Select projects that yield maximum profit without exceeding the budget.

**Approach:** Uses bottom-up 0/1 Knapsack DP to calculate optimal profit and selected projects.

**Output:** List of selected projects and total profit.

**Visualization:** Profit vs. Budget graph.

**Complexity:** Time – O(n × budget), Space – O(n × budget)

**Observation:** Profit rises with budget until optimal investment is reached, then flattens.

**Problem 3: Factory Production Optimization**

Algorithm: Dynamic Programming (Resource Allocation)
Domain: Manufacturing and Supply Chain

**Objective:** Maximize profit by optimizing production under limited resources.

**Approach:** Similar to Knapsack DP; selects production combinations for maximum gain.

**Output:** Optimal production plan and maximum achievable profit.

**Visualization:** Resource usage vs. total profit.

**Observation:** Profit grows gradually and plateaus at capacity limit.

**Problem 4: Delivery Route Optimization**

Algorithm: Greedy (Shortest Path Heuristic)
Domain: Logistics and Transportation

**Objective:** Minimize total delivery distance or cost by finding an efficient route.

**Approach:** Greedy nearest-neighbor algorithm to visit the closest unvisited city.

**Output:** Route sequence and total travel distance.

**Visualization:** Graph showing optimized delivery route.

**Complexity:** Time – O(n²), Space – O(n)

**Observation:** Provides a fast and practical route though not always globally optimal.

**Common Libraries Used**
import numpy as np
import matplotlib.pyplot as plt
from memory_profiler import profile
import time

**How to Run**

Clone the repository:

git clone https://github.com/<your-username>/Algorithmic-Optimization.git
cd Algorithmic-Optimization


**Run any problem file:**

python problem1_greedy_ads.py


View results and plots.

Author

Sunisha Udar
Data Science & Algorithm Enthusiast
