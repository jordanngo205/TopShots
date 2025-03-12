# Shot Analysis Script - README

## Overview
This script processes game logs to analyze shooting efficiency for Waterloo basketball players. It identifies the most and least efficient play types based on shot attempts, makes, and misses.

## Features
- Tracks shot attempts and makes by play type.
- Calculates efficiency (makes/attempts) for each play type.
- Identifies the top and bottom play types by efficiency.
- Ranks play types based on most makes and most misses.
- Reads game log data from a specified text file.




## How It Works
1. **Read Game Log**: The script reads the game log file and searches for plays involving Waterloo players.
2. **Extract Shot Data**: It identifies the play type and whether it resulted in a make or miss.
3. **Calculate Efficiency**: Computes efficiency (makes/attempts) for each play type.
4. **Sort and Display**: Sorts play types by efficiency, makes, and misses, then prints the results.

## Example Output
```
Total shots taken by Waterloo: 75

Top 3 Play Types by Efficiency:
1. Fast Break Layup - Efficiency: 0.80 (8 makes / 10 attempts)
2. Catch & Shoot 3PT - Efficiency: 0.67 (10 makes / 15 attempts)
3. Mid-Range Jumper - Efficiency: 0.60 (6 makes / 10 attempts)

Bottom 3 Play Types by Efficiency:
1. Off-Balance Jumper - Efficiency: 0.20 (2 makes / 10 attempts)
2. Contested 3PT - Efficiency: 0.25 (3 makes / 12 attempts)
3. Fadeaway - Efficiency: 0.30 (3 makes / 10 attempts)

Top 3 Play Types with the Most Makes:
1. Catch & Shoot 3PT - 10 makes
2. Fast Break Layup - 8 makes
3. Mid-Range Jumper - 6 makes

Top 3 Play Types with the Most Misses:
1. Contested 3PT - 9 misses
2. Off-Balance Jumper - 8 misses
3. Fadeaway - 7 misses
```


