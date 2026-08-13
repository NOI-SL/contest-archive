---
title: "Moving balls"
year: 2023
category: monthly
round: "January 2023"
sortkey: "2-monthly-01-03"
index: 3
max_score: 100
difficulty: "Easy"
contest_name: "National Olympiad in Informatics Sri Lanka - January 2023"
contest_slug: "noi-2023-january"
contest_url: "https://www.hackerrank.com/contests/noi-2023-january"
problem_slug: "moving-balls"
problem_url: "https://www.hackerrank.com/contests/noi-2023-january/challenges/moving-balls"
---

Amara has a collection of empty bags. And there are barrels of  coloured balls in a friend’s house. Amara need to get all of those coloured balls in to his house using the collection of empty bags.

You’re given an array of integers $$k$$ of length $$n$$. 

From $$1^{st}$$ trip to $$n^{th}$$ trip, In the $$i^{th}$$ trip, Amara can only take $$k_{i}$$ bags with him. After that, in the $$(n+1)^{th}$$ trip Amara can take $$k_1$$ bags, in the $$(n+2)^{th}$$ trip Amara can take $$k_2$$ bags and so on. When the array $$k$$ finishes, it repeats from the start.

Each bag can carry maximum $$l$$ balls. Balls in a single bag must be **of the same colour.** He has to bring back $$m$$ colours of balls. $$j^{th}$$ color has $$q_j$$ balls. 

What is the minimum number of trips $$t$$ required to transport all of the coloured balls to his home? It is guaranteed that $$t < 10^5$$

### Subtasks

- Subtask 1 - 20 pts
    - $$k_i$$ = 2
    - $$q_j = l$$
- Subtask 2 - 40 pts
    - $$k_i$$ = 2
- Subtask 3 - 25 pts
    - $$t < n$$
- Subtask 4 - 15 pts
    - No further constraints

## Input Format

The first line contains two integers $$n$$ and $$l$$

Second line contains $$n$$ integers $$k_1, k_2, k_3, ..., k_n$$

Third line contains an integer $$m$$

Forth line contains $$m$$ integers $$q_1, q_2, ..., q_m$$

## Output Format

Single integer - minimum number of trips required to transport all of the coloured balls to his home

## Constraints

$$n < 10^5$$

$$m < 10^5$$

$$k_i < 10^3$$

$$l < 10^5$$

$$q < 10^5$$

### Sample Input 0

```
2 2
1 2
2
1 2
```

### Sample Output 0

```
2
```
