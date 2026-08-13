---
title: "reductor"
year: 2024
category: qualifier
round: "Qualifier Round"
sortkey: "1-qualifier-01"
index: 1
max_score: 100
difficulty: "Medium"
contest_name: "NOI 2024 Qualifier Round"
contest_slug: "noi-2024-qualifier-round"
contest_url: "https://www.hackerrank.com/contests/noi-2024-qualifier-round"
problem_slug: "reductor"
problem_url: "https://www.hackerrank.com/contests/noi-2024-qualifier-round/challenges/reductor"
---

You're given an array $$a$$ of length $$n$$, array $$b$$ of length $$n$$ and a reduction parameter $$r$$. 

Your target is to reduce all values in the array such that the array only contains non-positive values.

In a single step, you can negate $$r$$ from every element in $$a$$. After applying this negation, $$r$$ will be reduced by $$k$$.

 $$k$$ is the lowest value in $$b$$, where the corresponding element in $$a$$ is positive. 

There are $$t$$ testcases. For each case, If it's possible to achive the goal output "YES", otherwise "NO".

## Input Format

Input:

- First line contains $$t$$.
- Next $$t$$ three sets of lines
  - First line of the pair contains $$n$$ and $$r$$. length of the array and the reduction parameter.
  - Second line contains $$n$$ space seperated integers, array $$a$$
  - Third line contains $$n$$ space seperated integers, array $$b$$

## Output Format

Output:

- $$t$$ lines each containing `YES` or `NO`

## Constraints

Constraints:

- $$1 <= t <= 100$$
- $$1 <= n,r <= 10^5$$
- $$1 <= a_i, b_i <= 10^9$$

### Sample Input 0

```
1
6 7
18 5 13 9 10 1
2 7 2 1 2 6
```

### Sample Output 0

```
YES
```
