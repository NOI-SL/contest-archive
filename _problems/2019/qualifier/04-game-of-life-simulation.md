---
title: "Game of Life Simulation"
year: 2019
category: qualifier
round: "Selection Test"
sortkey: "1-qualifier-04"
index: 4
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - Screening Test"
contest_slug: "noi-2019-selection-test"
contest_url: "https://www.hackerrank.com/contests/noi-2019-selection-test"
problem_slug: "game-of-life-simulation"
problem_url: "https://www.hackerrank.com/contests/noi-2019-selection-test/challenges/game-of-life-simulation"
---

The game of life is in a grid of ***N rows*** and ***N columns***. Each cell in the grid is either ***dead*** or ***alive***. In the beginning only a ***single cell*** is alive. Then at each steps cells become dead or alive based on the following criteria:

1. ***If 1 or 3 of the neighboring cells (up, down, left or right not in diagonal directions) are alive the cell becomes or stays alive.***
2. ***If 0 or 2 or 4 of the neighboring cells are alive the cell becomes dead or stays dead.***

![image]({{ "/assets/problems/660245f9-1557996766-f3371f1a99-4.GameofLife-Map.png" | relative_url }})

The four cells marked in red are the neighboring cells of the black cell. So, if 1 or 3 of the red cells are alive, the black cell will be alive in the next step or dead otherwise.

You are given 

1. ***N*** - size of the grid
2. ***R*** and ***C*** - the row and column of the first cell alive, (rows are numbered from 1 to N from top to bottom and columns are numbered from 1 to N from left to right)
3. ***S*** - the number of steps 

You need to find the ***number of cells alive*** after ***S*** steps.

## Input Format

First row will contain ***N***, the second row will contain ***R*** and ***C*** separated by a space and the third row will contain ***S***.

## Output Format

You should output the ***total number of cells*** alive after ***S*** steps.

## Constraints

- ***1 $$\leq$$ N $$\leq$$ 100***
- ***1 $$\leq$$ R, C $$\leq$$ N***
- ***0 $$\leq$$ S $$\leq$$ 100***

### Sample Input 0

```
4
2 2
3
```

### Sample Output 0

```
6
```
