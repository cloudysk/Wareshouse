# Wareshouse
Warehouse Stock Filling Simulation with Peak/Off-Peak Time (Every 4 Hours) In this challenge, you'll simulate adding stock to a warehouse where the stock-adding rate changes based on peak or off-peak hours. Stock is added every 4 hours at specific intervals within that hour, and you must track the warehouse's total stock level while preventing overflow beyond its maximum capacity

Warehouse Details:

The warehouse has a maximum capacity of 1200 units.

Problem Instructions

Initially, the warehouse is empty.

Stock Adding Intervals:

Stock is added every 4 hours, specifically at the 0th, 20th, and 40th minutes of the hour. • The base rate is 100 units each time stock is added.

Peak/Off-Peak Time Variation:

Operations start at 6 AM.

Peak Time (6 AM to 10 AM): The amount of stock added increases by 80 units every 20 minutes,

up to a maximum of 200 units each time. Off-Peak Time (11 AM to 6 PM): The amount of stock added decreases by 40 units every 20

minutes, with a minimum of 50 units each time.

Output Requirements:

• Display whether it is "Peak Time" or "Off-Peak Time" in each iteration. • Display the stock added and the total stock after each addition at the 0th, 20th, and 40th minutes of the hour.

AM, 2PM, etc.). Stop the simulation once the warehouse reaches or exceeds the full capacity of 1200 units.

Output Format:

Print a summary of the total stock in the warehouse at the end of each 4-hour interval (e.g., 6 AM, 10

For each interval, display:

• Hour, minute, and whether it's "Peak Time" or "Off-Peak Time" (e.g., "Hour 6-Min 0-Peak Time")

Stock added in that interval

• Total stock in the warehouse so far

Overflow Prevention: Stop the simulation if the warehouse reaches or exceeds its full capacity of 1200 units.

Output: Hout 6-Min 0-Peak Time | Stock

Added: 100

units

Total: 100 units

Total: 280 units

Hour 6-Min 20-Peak Time | Stock Added: 180 units Hour 6-Min 40- Peak Time Stock Added 200 units Total:

480 units

Summary at Hour 6: Total stock in warehouse is 480 units ---

Total: 580 units Total: 760 units

Hour 10-Min 40-Peak Time Stock Added: 200 units Total: 960 units

Hour 10-Min 0-Peak Time Stock Added: 100 units Hour 10-Min 20-Peak Time Stock Added: 180 units |

--- Summary at Hour 10 Total stock in warehouse is 960 units

Hour 14-Min 0-Off-Peak Time Stock Added: 100 units Total: 1060 units Hour 14-Min 20-Off-Peak Time Stock Added. 60 units | Total: 1120 units Hour 14-Min 40-Off-Peak Time Stock Added: 50 units Total: 1170 units

-Summary at Hour 14. Total stock in warehouse is 1170 units...

Hour 18-Min 0-Off-Peak Time Stock Added: 100 units Total: 1270 units
