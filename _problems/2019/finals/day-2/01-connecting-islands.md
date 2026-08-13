---
title: "Connecting Islands"
year: 2019
category: finals
round: "Final Round — Day 2"
sortkey: "3-finals-2-01"
index: 1
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - Day 2"
contest_slug: "noi-2019-day-2"
contest_url: "https://www.hackerrank.com/contests/noi-2019-day-2"
problem_slug: "connecting-islands"
problem_url: "https://www.hackerrank.com/contests/noi-2019-day-2/challenges/connecting-islands"
---

The newly formed city X is depicted using an **M x M** grid of cells. The **bottom-left** corner cell of the grid is **(0,0)** while the **top-right** corner cell of the grid is **(M-1, M-1)**. Each cell is either **land** or **ocean**, but **not both**. If you are in a land cell you can walk to any one of 4 of neighboring (left, right, up or down) land cells from there. You can not walk into an ocean cell. Also, you can’t walk outside of the grid. 

There are **N** islands in the city right now. And the islands are **rectangular shaped**. Therefore the island can be defined by its bottom-left cell position and upper-right cell position. In a given island, if bottom-left corner cell is **(x1,y1)** and upper-right corner cell is **(x2,y2)** then the total number of cells in that island is **(x2-x1+1) * (y2-y1+1)**. Also, any given land cell in the grid is a part of exactly one island.

The cost of converting an ocean cell to a land cell is 1. Write a program to find the minimum cost required to connect all lands so that you can walk from any land cell to any other land cell in the city.

## Input Format

The first line of the input has **2** integers **M** and **N**, the size of the grid & the number of islands in the city respectively.
Each of the next **N** lines contains **4** integers **x1<sub>i</sub>**, **y1<sub>i</sub>**, **x2<sub>i</sub>**, **y2<sub>i</sub>** separated by spaces, representing the **i<sup>th</sup>** island in the city.

## Output Format

Output just **one** integer representing your answer, the **minimum cost** required to connect all land cells.

## Constraints

- **0 $$\leq$$ x1<sub>i</sub> $$\leq$$ x2<sub>i</sub> $$<$$ M**
- **0 $$\leq$$ y1<sub>i</sub> $$\leq$$ y2<sub>i</sub> $$<$$ M**  
  &nbsp;  
  
#### **Subtask 1:** 20 points
- **1 $$\leq$$ M, N $$\leq$$ 20**  
#### **Subtask 2:** 30 points
- **21 $$\leq$$ M, N $$\leq$$ 100**  
#### **Subtask 3:** 40 points
- **101 $$\leq$$ M $$\leq$$ 10<sup>5</sup>**  
- **101 $$\leq$$ N $$\leq$$ 10<sup>3</sup>**  
#### **Subtask 4:** 10 points
- **101 $$\leq$$ M $$\leq$$ 10<sup>5</sup>**  
- **101 $$\leq$$ N $$\leq$$ 10<sup>4</sup>**  
  &nbsp;  
   
#### **Limits**
- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
10 3
0 0 1 1
2 2 4 4
6 4 8 9
```

### Sample Output 0

```
2
```
