---
title: "Suvin’s Magic Tricks"
year: 2022
category: finals
round: "Final Round — Day 2"
sortkey: "3-finals-2-03"
index: 3
max_score: 0
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka 2022 - Day 2"
contest_slug: "noi-2022-day-2"
contest_url: "https://www.hackerrank.com/contests/noi-2022-day-2"
problem_slug: "suvins-magic-tricks"
problem_url: "https://www.hackerrank.com/contests/noi-2022-day-2/challenges/suvins-magic-tricks"
---

Suvin is back with a group of children and he is going to play a game. Each child has a number card in his/her pocket that denotes the lucky number of that child. 

Those children will not come to play unless their lucky scores are the same. The lucky score of a child is calculated by counting the number of $$1-bits$$ in the binary representation of their respective lucky number.

However, since it is unlikely for all the children to have the same lucky score, Suvin made an arrangement with the children, where he will name a magic number $$X$$, which will be used to change all the lucky numbers of children, by computing the **XOR** between the original lucky number and $$X$$.

Now, Suvin has to find a magic number such that when the new lucky numbers are computed, the lucky scores of children will become equal. 

You have to help Suvin with this task. Find a magic number that is **less than $$2^{30}$$**, or let him know that no such number exists.

## Input Format

The first line contains the number of test cases $$T$$.

Then for each test case $$T_i$$:

- The first line contains the integer $$N$$, denoting the number of children
- The second line contains $$N$$ space-separated integers ($$A_0$$, $$A_1$$, $$A_2$$, …, $$A_{N-1}$$) denoting the initial lucky numbers of $$N$$ children

## Output Format

For each test case $$T_i$$:

- If it is not possible to find a valid magic number,  print $$-1$$
- Otherwise, print any non-negative integer not exceeding $$2^{30} - 1$$, that can be used as the magic number

## Constraints

- $$1 \leq T \leq 100$$
- $$2 \leq N \leq 100$$
- $$2 \leq T*N \leq 100$$
- $$0 \leq A_i \leq 2^{30} - 1$$
- $$0 \leq X \leq 2^{30} - 1$$

#### **Limits**
- **Time Limit**: 2s
- **Memory Limit**: 512MB

### Sample Input 0

```
2
2
7 2
3
1 2 3
```

### Sample Output 0

```
1
-1
```
