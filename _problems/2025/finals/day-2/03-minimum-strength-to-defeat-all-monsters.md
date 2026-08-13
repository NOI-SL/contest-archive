---
title: "Wizards, Wands, and the Great Tower"
year: 2025
category: finals
round: "Final Round — Day 2"
sortkey: "3-finals-2-03"
index: 3
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics 2025 day 2"
contest_slug: "noi-2025-day-2"
contest_url: "https://www.hackerrank.com/contests/noi-2025-day-2"
problem_slug: "minimum-strength-to-defeat-all-monsters"
problem_url: "https://www.hackerrank.com/contests/noi-2025-day-2/challenges/minimum-strength-to-defeat-all-monsters"
---

In a world of magic, there are `n` young **wizards** who wish to enter the **Great Tower** of Sorcery to complete their final trials.  
However, the Tower has a rule:  
> "No wizard may enter without holding a **magic wand**."

There are `k` **magic wands** scattered along the **Ancient Path**, a straight road leading directly to the Tower, located at position `p`.  
Each wizard starts at their own position along the path.  
To enter the Tower, each wizard must:

1. First **collect exactly one wand** (each wand can be taken by only one wizard),
2. Then **proceed to the Tower** at position `p`.

- Wizards can **pass by** wands without picking them up.
- If two wizards reach a wand at the same time, **only one can take it**.
- All wizards move at **one unit distance per second**.

Your mission is to figure out the **minimum possible time** needed for all wizards to enter the Great Tower with wands.

## Input Format

```
n k p
a1 a2 ... an
b1 b2 ... bk
```
- `n`: number of wizards
- `k`: number of wands
- `p`: position of the Tower
- `a[i]`: starting positions of wizards
- `b[j]`: positions of wands

## Output Format

```
Minimum time for all wizards to enter the Great Tower.
```

## Constraints

```
- 1 ≤ n ≤ 1000
- n ≤ k ≤ 2000
- 1 ≤ p, a[i], b[j] ≤ 10^9
- No two wizards or wands share the same starting position. But a wand and a wizard can share a same position.
```

### Subtasks

- Subtask 1 (20 points): n, k ≤ 10
- Subtask 2 (10 points): n = 1
- No more subtasks

### Sample Input 0

```
3 5 10
1 5 15
2 6 9 13 20
```

### Sample Output 0

```
9
```
