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


Here is the provided rubric formatted in Markdown:

### Rubric

| Criteria                   | Excellent (20 points)                                                                                                                                             | Good (15 points)                                                                                                                   | Fair (10 points)                                                                                             | Poor (5 points)                                                                                  |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
| **Functionality**          | Program correctly simulates inventory with restocking based on reorder threshold, calculates relevant metrics, and allows for multiple simulations.                | Program simulates most aspects correctly, but may have minor errors or limited data output/analysis functionality.                  | Program has functional issues or limited ability to run simulations with different thresholds.                | Program has major functionality issues or doesn't run at all.                                    |
| **Code Structure**         | Code is well-organized with clear separation of concerns using functions and well-defined classes (if used).                                                       | Code is mostly organized with functions separating logic. Class usage could be improved.                                           | Some use of functions, but lacks clear separation or well-defined classes.                                    | Minimal use of functions or classes, making code difficult to read and maintain.                 |
| **Testing**                | Code demonstrates comprehensive testing of different scenarios using various reorder thresholds.                                                                  | Code demonstrates some testing, but could benefit from more comprehensive testing with different thresholds.                       | Limited evidence of testing or testing only basic functionality.                                              | No evidence of testing.                                                                         |
| **Efficiency**             | Code is optimized for efficiency, avoiding unnecessary calculations or redundant logic.                                                                           | Code functions correctly but may have room for improvement in efficiency.                                                          | Code has inefficiencies that could potentially impact performance.                                            | Code has significant inefficiencies that slow down the simulation.                              |
| **Comments and Documentation** | Code includes clear comments explaining the purpose of functions and classes (if used), variables, key logic steps, and configuration options.                     | Code has some comments, but could benefit from additional explanation for complex sections.                                        | Limited use of comments, making code difficult to understand.                                                 | No comments or unclear explanations within the code.                                            |
| **Analysis and Optimization** | Code is used to effectively analyze the impact of reorder thresholds on inventory metrics and identify an optimal threshold considering holding and stockout costs. | Code is used to analyze the impact of thresholds, but explanation of the optimal threshold selection is limited.                    | Limited analysis of the impact of thresholds or no identification of an optimal threshold.                    | No analysis of the impact of thresholds performed.                                              |
