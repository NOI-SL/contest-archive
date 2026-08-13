---
title: "Stilt Fishermen"
year: 2023
category: finals
round: "Final Round — Day 2"
sortkey: "3-finals-2-03"
index: 3
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka 2023 - Day 2"
contest_slug: "noi-2023-day-2"
contest_url: "https://www.hackerrank.com/contests/noi-2023-day-2"
problem_slug: "stilt-fishermen"
problem_url: "https://www.hackerrank.com/contests/noi-2023-day-2/challenges/stilt-fishermen"
---

Stilt fishing is a unique method practiced in Sri Lanka where fishermen perch on a crossbar attached to a vertical pole embedded in the sea bed. The pole, typically a tree trunk, has to be a specific height above sea level for aesthetic appeal and functionality, particularly as the fishing method has become a tourist attraction.

In a southern Sri Lankan village, the community of stilt fishermen aims to expand their fishing area and needs your help to optimize the placement and timing of new poles. The poles come from $$N$$ trees in the village, each with varying initial heights ($$h_0$$, $$h_1$$, $$h_2$$, ..., $$h_{n-1}$$) on day $$0$$. Each tree grows by $$1$$ meter per day until it is cut.

The sea bed's depth is inconsistent, represented by a $$W{\times}W$$ integer matrix, where each cell value indicates the depth from the *mean sea level* in meters. Every pole should be driven $$S$$ meters below the sea bed for stability, and a single cell can accomodate any number of poles. However, due to sea level fluctuations, the part of the pole that remains submerged depends on the sea bed depth at the placement site and the current sea level.

The community will present you with $$Q$$ questions, either of type 1 or type 2:

**Type 1:** Can the trees be cut on day 0, and the vertical poles placed such that $$A$$ meters of each pole remain above the water when the water level is $$L$$ meters above the *mean sea level*?

**Type 2:** What is the minimum number of days required before all $$N$$ vertical poles can be placed such that A meters of each pole remain above the water when the water level is $$L$$ meters above the *mean sea level*?

Your task is to accurately answer all $$Q$$ queries.

Explanation Images:

1. [Explanation Image 1](https://drive.google.com/file/d/1r73aFNOqF6m6AkMFqeNh7OOpRsUTgoA7/view?usp=sharing)

2. [Explanation Image 2](https://drive.google.com/file/d/18jxAOrelACPMjHDSaFvyrh9CqZ3PUjfj/view?usp=sharing)

## Input Format

- First line contains 4 integers, $$N$$, $$W$$, $$S$$, and $$Q$$; separated by spaces.
- Next $$W$$ lines describe the $$W{\times}W$$ depth matrix, where integer $$j$$ at row  $$i$$ represents sea bed depth from *mean sea level* for cell $$(i,j)$$.
- Next line contains $$N$$ integers, where integer $$i$$ represents the initial height $$h_i$$ of a tree, expected to be used as a pole.
- Next $$Q$$ lines contain $$Q$$ queries, where each line $$i$$ contains 3 integers $$t_i$$, $$A_i$$, and $$L_i$$ 
    - $$t_i$$ - Type of the question (can be 1 or 2)
    - $$A_i$$ - Height of poles above the sea level
    - $$L_i$$ - Sea water level above the *mean sea level*

## Output Format

For each query $$Q_i$$, print a single line containing a single integer.

**Type 1 Question:**

- Print $$1$$ if it is possible 
- Print $$0$$ if it is not possible

**Type 2 Question:**

- Print the minimum number of days to wait
- Print $$-1$$ if it is not possible to place the vertical poles

## Constraints

$$1 \leq W \leq 10^3$$

$$1 \leq N \leq 10^4$$

$$1 \leq Q \leq 10^3$$

$ 1 \leq N \times Q \leq 10^6$

$$1 \leq S, h_x, A_i, W_{(i,j)} \leq 10^9$$

$$-10^9 \leq L_i \leq 10^9$$

$ L_i + min(W_{(i,j)}) \geq 0$

### Subtasks:

Testcases worth 20% of total score have only type 1 queries, $$W \leq 10^2$$, $$N \leq 10^2$$

Testcases worth 40% of total score have $$W \leq 10^2$$, $$N \leq 10^2$$

### Sample Input 0

```
2 3 1 2
1 1 1 
2 3 1
1 1 1 
4 5
1 1 1
2 3 4
```

### Sample Output 0

```
1
5
```
