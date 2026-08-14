# PPIC Production Planning Simulation
### Project Overview

This project simulates the production planning process in a manufacturing environment. It transforms sales forecasts into production schedules while maintaining inventory levels and ensuring production capacity is sufficient to meet demand.

IT IS RECOMMENDED TO USE CHROME TO OPEN THE FILE
[PPIC](https://github.com/Zanemii/Production-Planning-PPIC-Andi-Rahmat-/raw/main/Production%20Planning.xlsx)

### Objectives
1. Convert sales forecasts into production plans.
2. Maintain optimal inventory levels.
3. Generate Master Production Schedules (MPS).
4. Validate production plans against machine capacity.
5. Identify potential capacity bottlenecks before production.

### Planning Process
1. Aggregate Planning<br>
Purpose: Determine monthly production requirements based on demand and inventory.<br>
Inputs:<br>
-Sales Forecast (SF)<br>
-Stock on Hand (SOH)<br>
Output:<br>
-Aggregate Production Plan (AP)

2. Master Production Schedule (MPS)<br>
Purpose: Convert monthly production plans into weekly production schedules.<br>
Calculations:<br>
-Customer Orders<br>
-Inventory Balance<br>
-Planned Production (MPS)<br>
-Ending Inventory<br>
-Lot Size Planning<br>

3. Rough-Cut Capacity Planning (RCCP)<br>
Purpose: Verify that the production schedule is achievable with available manufacturing capacity.<br>
Capacity Factors:<br>
-Number of Machines<br>
-Cycle Time (CT)<br>
-Machine Efficiency<br>
-Weekly Workload<br>
-Capacity Utilization<br>
 
 A Job Load chart is used to compare machine workload against available capacity and identify bottlenecks.
