---
title: "Subtle Cheater"
year: 2024
category: monthly
round: "February 2024"
sortkey: "2-monthly-02-01"
index: 1
max_score: 100
difficulty: "Easy"
contest_name: "NOI 2024 february monthly contest"
contest_slug: "noi-2024-feb"
contest_url: "https://www.hackerrank.com/contests/noi-2024-feb"
problem_slug: "subtle-cheater"
problem_url: "https://www.hackerrank.com/contests/noi-2024-feb/challenges/subtle-cheater"
---

You're at the coordinate $$(0,0)$$ in an infinite grid. And you were asked to move around to a given a sequence of directions. As an example, if you were given the sequence $$L,L,U,R,D$$ you have to move in the following path.

$$(0,0)$$ -> $$(-1,0)$$ -> $$(-2,0)$$ -> $$(-2,1)$$ -> $$(-1,1)$$ -> $$(-1,0)$$

But your goal is to remain at the coordinate $$(0,0)$$ after following directions. In order to achieve that, you can cheat by ignoring some of the instructions. But to remain unnoticed to the moderator you need to find out the minimum number of instructions you will have to ignore.

## Input Format

First line contains a single integer $$n$$, number of instructions.
The next line contains a string of length $$n$$ consisting of $$L,R,D,U$$ characters.

## Output Format

Single integer, Minimum number of instructions you have to ignore

## Constraints

- $$n <= 10^3$$

### Sample Input 0

```
5
LUDRR
```

### Sample Output 0

```
1
```
