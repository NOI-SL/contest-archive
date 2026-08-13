---
title: "Sequence Hunt"
year: 2024
category: finals
round: "Final Round — Day 2"
sortkey: "3-finals-2-03"
index: 3
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka 2024 - Day 2"
contest_slug: "noi-2024-day-2"
contest_url: "https://www.hackerrank.com/contests/noi-2024-day-2"
problem_slug: "sequence-hunt-1-1"
problem_url: "https://www.hackerrank.com/contests/noi-2024-day-2/challenges/sequence-hunt-1-1"
---

You are given two integers, $$N$$ and $$K$$. Your task is to generate a sequence of $$N$$ distinct integers such that:


1. 	Each integer in the sequence is within the range $$1$$ to $$K$$ (inclusive).
2. 	There is no subsequence of size $$3$$ where the difference between consecutive terms remains constant.



In other words, you need to find a sequence $$a_1, a_2, ..., a_N$$ such that for any indices $$p < q < r$$, the difference $$a_q - a_p$$ is not equal to $$a_r - a_q$$.

## Input Format

Two space-separated integers: $$N$$ representing the length of the sequence and $$K$$ representing the range upper limit for the numbers in the sequence.

## Output Format

A sequence of $$N$$ space separated integers. In case of multiple valid answers, print any.

## Constraints

- $$1 \leq N \leq 10^4$$
- $$1 \leq K \leq 2 \times 10^6$$

**Subtasks**

1. (15 points) $$1 \leq N \leq 10$$ and $ K = 2 \times 10^6$
2. (15 points) $$1 \leq N \leq 10$$ and $ K = N$
3. (15 points) $$1 \leq N \leq 250$$ and $ K = 4 \times 10^3$
4. (15 points) $$1 \leq N \leq 10^4$$ and $ K = 2 \times 10^6$
5. (40 points) $$1 \leq N \leq 10^4$$ and $ K = N$

**Limits**

- Memory - 256MB
- Time - 2 seconds

### Sample Input 0

```
4 7
```

### Sample Output 0

```
1 2 4 5
```
