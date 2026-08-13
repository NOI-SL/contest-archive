---
title: "Petra and Rising Garden"
year: 2026
category: qualifier
round: "Qualifier Round"
sortkey: "1-qualifier-06"
index: 6
max_score: 100
difficulty: "Medium"
contest_name: "NOI 2026 Qualifier Round"
contest_slug: "noi-2026-qualifier-round"
contest_url: "https://www.hackerrank.com/contests/noi-2026-qualifier-round"
problem_slug: "the-rising-garden"
problem_url: "https://www.hackerrank.com/contests/noi-2026-qualifier-round/challenges/the-rising-garden"
---

In a magical garden, there are $$N$$ **enchanted plants** arranged in a straight line. Each plant has a certain **growth level**.

Petra wants to create a **beautiful sequence** of plants such that:

- The selected plants appear in the **same order** as in the garden
- Each next plant in the sequence has a **strictly higher growth level** than the previous one.

Find the **maximum number of plants** Petra can pick to form such a sequence.

## Input Format

- The first line contains an integer $$N$$, representing the number of plants.
- The second line contains $$N$$ space-separated integers $$A_1, A_2, A_3, \dots, A_N$$, where $$A_i$$ is the growth level of plant at i<sup>th</sup> position.

## Output Format

Print a single integer — the length of the longest beautiful sequence that Perta can obtain.

## Constraints

- $$1 ≤ N ≤ 10^5$$
- $$1 ≤ A_i ≤ 10^5$$

### Sample Input 0

```
5
2
7
4
3
8
```

### Sample Output 0

```
3
```
