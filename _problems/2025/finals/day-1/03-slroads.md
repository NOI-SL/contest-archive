---
title: "SLroads"
year: 2025
category: finals
round: "Final Round — Day 1"
sortkey: "3-finals-1-03"
index: 3
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics 2025 day 1"
contest_slug: "noi-2025-day-1"
contest_url: "https://www.hackerrank.com/contests/noi-2025-day-1"
problem_slug: "slroads"
problem_url: "https://www.hackerrank.com/contests/noi-2025-day-1/challenges/slroads"
---

The Sri Lankan roads are the heart of the country’s transport system. From the busy streets of Colombo to the scenic routes through the hills of Kandy, the roads are constantly in use. However, there's one huge issue — the roads have bumps and holes everywhere, especially after the monsoon rains.

These holes don’t just ruin the driving experience — they also trap rainwater. And it’s no small problem! The water-filled pits often become a danger for motorists, causing accidents and roadblocks, especially during the wet season.

Repairing these roads has become a critical task for the country's road authorities, and that's where you come in. You’ve been hired by the Sri Lankan Road Repair Department to identify the largest water-filled pit and calculate how much water it can hold, so that repairs can be prioritized.

The Challenge:
Given the 2D map of the road with varying height values representing bumps and holes, you need to calculate the largest volume of trapped water in the road. However, water can only stay in a hole if it’s completely enclosed by higher terrain. Any hole connected to the edge of the road can have its water drain away, so only the internal holes that are surrounded by higher points will hold water.

Your job is to determine which hole holds the most water, and that will be the first one to repair. Let’s see if you can help avoid any more vehicles getting stuck in those water traps!

## Input Format

First line: An integer T — the number of test cases.

For each test case:

Two integers N and M — the number of rows and columns in the road grid.

Then N lines follow, each containing M integers — the heights of the road cells (where higher values represent bumps and lower values represent holes).

## Output Format

For each test case, output a single line containing the volume of the largest hole that can be filled with water (the first hole that needs repair).

## Constraints

1≤T≤10

1
≤
𝑁
,
𝑀
≤
1000

0
≤
height
[
𝑖
]
[
𝑗
]
≤
1000

Subtask 1 : N or M is equals to 3 (25 points)

### Sample Input 0

```
1
3 6
3 3 4 4 4 2
3 1 3 2 1 4
7 3 1 6 4 1
```

### Sample Output 0

```
3
```
