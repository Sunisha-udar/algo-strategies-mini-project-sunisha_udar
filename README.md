# algo-strategies-mini-project-sunisha_udar
🚀 Algorithmic Problem Solving — Greedy & Dynamic Programming Approaches
👩‍💻 Author: Sunisha Udar
📚 Course Project | Media, Finance & Optimization Algorithms
📖 Overview

This repository contains four algorithmic problems implemented in Python, showcasing the use of Greedy and Dynamic Programming strategies across various real-world domains such as advertising, finance, scheduling, and optimization.

Each problem is implemented step-by-step with:
✅ Input data
✅ Algorithmic solution
✅ Analysis (time & space complexity)
✅ Visualization using matplotlib

🧩 Problem 1: Scheduling TV Commercials to Maximize Impact

Algorithmic Strategy: Greedy (Job Sequencing)
Domain: Media & Advertisement

📝 Description

Given a set of commercials, each with a deadline and revenue, the goal is to schedule them in available slots to maximize total revenue without overlap.

💡 Approach

Sort ads by profit (descending).

Allocate each ad to the latest possible time slot before its deadline.

Uses a Greedy algorithm similar to the Job Sequencing Problem.

📊 Visualization

A line graph showing Number of Ads vs. Total Revenue demonstrates that revenue rises with the number of ads but eventually stabilizes when all slots are filled.

⚙️ Complexity

Time: O(n log n) (due to sorting)

Space: O(n)

🧠 Real-world Constraints

Limited air-time slots, variable ad durations, and priority-based scheduling.

💰 Problem 2: Maximizing Profit with Limited Budget

Algorithmic Strategy: Dynamic Programming (0/1 Knapsack)
Domain: Investment & Budget Planning

📝 Description

Select projects with associated costs and profits to achieve maximum profit without exceeding a given budget.

💡 Approach

Uses bottom-up 0/1 Knapsack DP to compute maximum achievable profit.

Tracks which projects contribute to that profit.

📊 Visualization

Plot of Profit vs. Budget shows profit increasing with investment until reaching a plateau — indicating optimal budget utilization.

⚙️ Complexity

Time: O(n × budget)

Space: O(n × budget)

🧠 Real-world Constraints

Budget limits, varying ROI, and project interdependencies.

🏭 Problem 3: Factory Production Optimization

Algorithmic Strategy: Dynamic Programming (Resource Allocation)
Domain: Manufacturing & Supply Chain

📝 Description

Optimize factory production by selecting items to produce within a resource or capacity limit, maximizing total profit.

💡 Approach

Similar to Knapsack DP, but applied to production planning.

Compares profit per unit resource and optimizes output.

📊 Visualization

Graph between Resources Used vs. Total Profit shows gradual growth and a flattening curve — a typical diminishing returns pattern.

⚙️ Complexity

Time: O(n × capacity)

Space: O(n × capacity)

🧠 Real-world Constraints

Limited raw materials, machine hours, and demand uncertainty.

🚚 Problem 4: Delivery Route Optimization

Algorithmic Strategy: Greedy (Shortest Path Heuristic)
Domain: Logistics & Transportation

📝 Description

Determine an efficient route for deliveries to minimize distance or cost, similar to the Traveling Salesman Problem (TSP) in simplified form.

💡 Approach

Uses a Greedy nearest-neighbor approach to visit the closest next city.

Reduces total travel cost but may not always yield the global optimum.

📊 Visualization

A connected graph shows the route path with minimized total distance.

⚙️ Complexity

Time: O(n²)

Space: O(n)

🧠 Real-world Constraints

Traffic conditions, delivery time windows, and vehicle capacity.

🧾 Common Libraries Used
import numpy as np
import matplotlib.pyplot as plt
from memory_profiler import profile
import time

📊 Key Learnings

Greedy algorithms make locally optimal choices to approach global optimization.

Dynamic Programming provides an exact, optimal solution through overlapping subproblems.

Real-world optimization often balances between speed (Greedy) and accuracy (DP).

🖥️ How to Run

Clone the repository:

git clone https://github.com/<your-username>/Algorithmic-Optimization-Projects.git
cd Algorithmic-Optimization-Projects


Run any problem file (e.g., problem1_greedy_ads.py):

python problem1_greedy_ads.py


View generated output and visualization graph.

👩‍💻 Author

Sunisha Udar
🎓 Data Science & Algorithm Enthusiast
📫 Feel free to connect or contribute!
