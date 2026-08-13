---
title: "Pixel Paint"
year: 2024
category: monthly
round: "April 2024"
sortkey: "2-monthly-04-02"
index: 2
max_score: 100
difficulty: "Medium"
contest_name: "NOI 2024 April Monthly Contest"
contest_slug: "noi-2024-april"
contest_url: "https://www.hackerrank.com/contests/noi-2024-april"
problem_slug: "pixel-paint"
problem_url: "https://www.hackerrank.com/contests/noi-2024-april/challenges/pixel-paint"
---

You're given a canvas grid with $$n*10^{9}$$ pixels. ($$n$$ columns with $$10^{9}$$ pixels) Each column has a continous set of pixels painted starting from the bottom with height $$h_i$$  ($$1 \leq i \leq n$$).

You're allowed to paint new pixels and erase already painted pixels. The cost to either paint or erase a pixel in column $$i$$ is $$h_i \text{ mod } 97$$. Where $$h_i$$ is the initial height.

Your goal is to find the minimum cost to make all columns the same height.

## Input Format

- First line contains single integer $$n$$

- second line contains $$n$$ space seperated integers. Initial height of painted pixels for each coloumn

## Output Format

- Single integer - the minimum cost

## Constraints

- $ 1 \leq n \leq 10^6 $

- $ 0 \leq h_i \leq 10^{9}$


Subtask 1: 10 points

- $ 1 \leq n \leq 10 $

- $ 1 \leq h_i \leq 10$

Subtask 2: 30 points

- $ 1 \leq n \leq 100 $

- $ 1 \leq h_i \leq 10^{4} $

Subtask 3: 60 points

- $ 1 \leq n \leq 10^6 $

- $ 0 \leq h_i \leq 10^{9}$

### Sample Input 0

```
3
1 2 3
```

### Sample Output 0

```
4
```
