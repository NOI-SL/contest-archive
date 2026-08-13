---
title: "duck-pond"
year: 2025
category: finals
round: "Final Round — Day 1"
sortkey: "3-finals-1-01"
index: 1
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics 2025 day 1"
contest_slug: "noi-2025-day-1"
contest_url: "https://www.hackerrank.com/contests/noi-2025-day-1"
problem_slug: "duck-pond"
problem_url: "https://www.hackerrank.com/contests/noi-2025-day-1/challenges/duck-pond"
---

You are given a pond that is a grid of size $$h \times w$$. Each cell in the grid can either contain a duck or be empty.

There are $$h$$ kids standing along the rows (one per row) and $$w$$ kids standing along the columns (one per column). Each kid is standing at the edge of their respective row or column and can only see consecutive ducks starting from the edge they are facing.

- For each row, you are given the number of consecutive ducks starting from the left.
- For each column, you are given the number of consecutive ducks starting from the top.

Given these observations, how many valid configurations of ducks are there on the grid? (Answer can be zero if the given data are impossible)
Since the answer can be large, output the answer modulo $$1e9+7$$

Sample grid:

![image]({{ "/assets/problems/d0e93e3d-1745549939-8644b21240-image.png" | relative_url }})

## Input Format

• An integer $$h$$ — number of rows.
• An integer $$w$$ — number of columns.
• A list of $$h$$ integers $$r[1 \dots h]$$ — number of consecutive ducks from the left in each row.
• A list of $$w$$ integers $$c[1 \dots w]$$ — number of consecutive ducks from the top in each column.

## Output Format

• A single integer — the number of valid configurations of ducks that satisfy the given row and column constraints modulo $$1e9+7$$.

## Constraints

-   $ 1 \leq h,w \leq 2 \times 10^5$
-   $ 0 \leq r_i \leq w$
-   $ 0 \leq c_i \leq h$

### Subtasks

#### Subtask 1 - $$10\%$$

-   $$h = 1$$
-   $$r_i = 0$$

#### Subtask 2 - $$20\%$$

-   $$h = 1$$

#### Subtask 3 - $$30\%$$

-   $ 1 \leq h,w \leq 10^3$

#### Subtask 4 - $$40\%$$

-   No extra constraints

### Sample Input 0

```
3 4
0 3 1
0 2 3 0
```

### Sample Output 0

```
2
```
