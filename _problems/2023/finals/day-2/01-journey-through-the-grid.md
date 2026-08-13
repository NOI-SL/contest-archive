---
title: "Journey Through The Grid"
year: 2023
category: finals
round: "Final Round — Day 2"
sortkey: "3-finals-2-01"
index: 1
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka 2023 - Day 2"
contest_slug: "noi-2023-day-2"
contest_url: "https://www.hackerrank.com/contests/noi-2023-day-2"
problem_slug: "journey-through-the-grid"
problem_url: "https://www.hackerrank.com/contests/noi-2023-day-2/challenges/journey-through-the-grid"
---

Once upon a time, in a magical world, you found yourself trapped in a mystical prison. The prison consists of a grid with $$n + 1$$ rows and $$m + 1$$ columns, where each cell represents a unique location. Your current cell is $$(0, 0)$$, the top-left corner of the grid.

To escape from the prison, you must embark on a journey through the grid and reach the destination cell $$(i,j)$$. However, the path to freedom is not straightforward. You can only move downwards (D) or rightwards (R) to adjacent cells.

You have an infinite amount of different pebbles and before each query you can pick any amount from it.(Selected amount of pebbles cannot be changed throughout the query) You are provided with a character $$S$$, which determines how these pebbles are placed during your journey.

When moving to a new cell:

- If S == 'D', you must place one of the given pebbles on each down edge of a cell you pass.
- If S == 'R', you must place one of the given pebbles on each right edge of a cell you pass.

An pebble can only be placed once in a single path.

It is important to note that two paths from the starting cell to the destination cell are considered different if:

- They visit different cells along the path.
- The same edge is assigned different pebbles.

You are given $$Q$$ queries, and for each query, you need to find the number of ways to reach the destination cell $$(i, j)$$ using the pebbles you have at your disposal. Your task is to calculate this number of ways for each query efficiently, considering the grid's dimensions. As this number can be very large, output it mod $$1e9+7$$


Time Limit:
2 seconds

Memory Limit:
512 MB

## Input Format

- The first line contains three integers $$n$$, $$m$$, and $$Q$$, representing the dimensions of the grid ($$n$$ rows and $$m$$ columns) and the number of queries ($$Q$$), respectively.
- The following $$Q$$ lines each contain 1 character and 2 integers (space separated), $$S$$, $$i$$, $$j$$. (Zero-indexed)

## Output Format

For each query, output a single integer on a new line, denoting the number of ways to reach the destination cell $$(i,j)$$ mod $$1e9+7$$ using the given pebbles and considering the constraints of the problem.

## Constraints

- 3 <= n,m <= 10^3
- 1 <= q <= 10^4

- Subtask 1 - 20 pts
    - 3 ≤ n,m ≤ 15
- Subtask 2 - 80 pts
    - No furthur constraints

### Sample Input 0

```
2 3 1
R 1 2
```

### Sample Output 0

```
6
```
