

# Making Change

This repository contains a coding challenge that can be asked in interviews.

## Objective

The project focuses on solving the problem of finding the fewest number of coins required to make a specific total, given a collection of coins with varying values.

## Task Breakdown

### 0. **Change comes from within**

The script [0-making_change.py](0-making_change.py) includes a function to determine the minimum number of coins needed to achieve a given total using a specified set of coin denominations.

#### Function Details:
- **Prototype:** `def makeChange(coins, total)`
- **Returns:** The minimum number of coins needed to make the total.
  - If `total` is `0` or less, the function returns `0`.
  - If the total cannot be reached with the available coins, the function returns `-1`.
- **Parameters:**
  - `coins`: A list of integers representing the available coin denominations.
  - Each coin’s value is a positive integer.
  - The function assumes you have an unlimited supply of each coin denomination.

#### Performance Considerations:
- The efficiency of your solution will be evaluated based on its runtime.


