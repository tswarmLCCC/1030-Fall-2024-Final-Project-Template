Introduction
 

COSC Course Project Requirements
Assignment Description: Inventory Optimization with Simulation (100 points)
This assignment simulates a multi-day inventory management scenario for a company that sells monitors. You will develop a C++ program to model the daily demand for monitors, implement various restocking strategies, and analyze the trade-off between minimizing average on-hand inventory and out-of-stock days by adjusting reorder thresholds.

Objectives (80 points):

Implement a program that simulates daily monitor inventory for a specified number of days (20 points).
Utilize functions and classes to organize the code effectively (20 points). Functions are mandatory, classes are optional (bonus for good use).
Practice random number generation, conditional statements, and data structures (vectors) (10 points).
Implement a restocking strategy with a configurable reorder threshold (20 points):
Order a fixed amount (configurable) when the on-hand inventory falls below the reorder threshold (configurable).
Track the number of days the company is out-of-stock and calculate the average daily inventory level (10 points).
Provide a means to show a simulation's single run daily data output including (10 points):
Day number
On-hand monitors at the start of the day
Monitors demanded on that day
Reorder threshold used
Any monitors ordered on that day (amount and reason - reorder or to reach min level)
Number of days until ordered monitors arrive (if applicable)
NOTE:  This will not be used in the final program - but is a great intermediate step to make sure one run is working correctly and will be a means to grade one of the early check-ins.
Calculate and output the following metrics at the end of the simulation (10 points):
Total out-of-stock days
Average daily inventory level
Remaining monitors
Cost of placing orders (optional: consider a fixed cost per order)
Analysis and Optimization (20 points):

Run multiple simulations with different reorder threshold values (10 points).
Analyze the impact of changing the reorder threshold on the following metrics (10 points):
Average daily inventory level
Total out-of-stock days
Identify a suggestedl reorder threshold that minimizes the combined cost of holding inventory (proportional to average daily inventory) and lost sales due to stockouts (consider a fixed cost per out-of-stock day). (Optional: You can implement a simple cost function to quantify this.)
