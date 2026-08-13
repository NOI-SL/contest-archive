---
title: "Mango Plantation"
year: 2021
category: finals
round: "Final Round — Day 1"
sortkey: "3-finals-1-01"
index: 1
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka 2021 - Day 1"
contest_slug: "noi-2021-day-1"
contest_url: "https://www.hackerrank.com/contests/noi-2021-day-1"
problem_slug: "mango-plantation"
problem_url: "https://www.hackerrank.com/contests/noi-2021-day-1/challenges/mango-plantation"
---

Mango trees grow in different sizes but each gives equal produce. And they need sun as well as wind 🤷‍♂️ to grow. You have a rectangular plot of land. The wind is flowing from north to south (**along y axis**).  
  
Your workers have spread the mango seeds all over the place. And the seeds have germinated already (so you can’t remove and plant them somewhere else). They have used up all ***N*** seeds. You know the location of each seed (***x<sub>i</sub>***, ***y<sub>i</sub>***) and the size it would grow into (their radius: ***r<sub>i</sub>***). The trees grow into a perfect semi-spherical shape of radius ***r<sub>i</sub>***.  
  
You need to remove seeds so that the remaining plants can grow, without overlapping and with full exposure to wind (**full corridor of width equal to the diameter of the tree along x-axis should be open for each tree**). You also need to remove trees that would grow beyond your plot of land.  
  
Calculate the **maximum number of seeds** that can be kept.

## Input Format

First line contains ***3*** integers, ***N***, ***W*** and ***H***, the number of seeds planted, width and height of the plot of land.  
Following ***N*** lines each contain three integers, ***x<sub>i</sub>***, ***y<sub>i</sub>*** and ***r<sub>i</sub>***. The location of the seeds and radius they will grow into.

## Output Format

The maximum number of seeds that can be kept.

## Constraints

- **1 $$\leq$$ N $$\leq$$ 10<sup>6</sup>**  
- **1 $$\leq$$ W, H $$<$$ 10<sup>8</sup>**  
- **0 $$\leq$$ X $$<$$ W**
- **0 $$\leq$$ Y $$<$$ H**
- **1 $$\leq$$ R $$<$$ 10<sup>8</sup>**
  
#### **Subtasks**  

1. **(50 points)**  
	- 1 $$\leq$$ N $$\leq$$ 5000  
    - 1 $$\leq$$ W, H $$<$$ 10<sup>6</sup>
    - 1 $$\leq$$ R $$<$$ 10<sup>6</sup>
2. **(50 points)**  
	- No additional constraints.  
   
#### **Limits**  

- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
6 10 10
0 0 5
2 5 1
8 8 2
3 9 2
4 4 3
4 5 1
```

### Sample Output 0

```
3
```
