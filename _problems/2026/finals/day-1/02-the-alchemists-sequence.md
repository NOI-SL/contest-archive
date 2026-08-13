---
title: "The Alchemist’s Sequence"
year: 2026
category: finals
round: "Final Round — Day 1"
sortkey: "3-finals-1-02"
index: 2
max_score: 100
difficulty: "Medium"
contest_name: "NOI 2026 Day 1"
contest_slug: "noi-2026-day-1"
contest_url: "https://www.hackerrank.com/contests/noi-2026-day-1"
problem_slug: "the-alchemists-sequence"
problem_url: "https://www.hackerrank.com/contests/noi-2026-day-1/challenges/the-alchemists-sequence"
---

You are given an array $$A$$ consisting of $$N$$ positive integers. An **Auric Subsequence** is defined as a non-empty subsequence of $$A$$ where the product of all elements in the subsequence is a **Auric** number.A number is **Auric** if it is not divisible by any perfect square greater than $$1$$ (e.g., $$6 = 2 \times 3$$ is **Auric**, but $$12 = 2^2 \times 3$$ is not).Your task is to calculate the total number of **Auric Subsequences** of the given array. Since the answer can be very large, output answer modulo $$10^9 + 7$$.


**Note on Subsequences**

Two subsequences are considered **distinct** if the sets of indices of the elements they contain are different. This applies even if the numerical values within the subsequences are identical. For example, if $$A = [2, 2]$$, there are two distinct subsequences that both result in the value $$\{2\}$$.

## Input Format

First line contains a single integer $$N$$ ($$1 \le N \le 10^5$$), representing the number of integers in the array.
Second line contains $$N$$ space-separated integers $$A_1, A_2, \dots, A_N$$ ($$1 \le A_i \le 2*10^3$$), representing the elements of the array.

## Output Format

Output a single integer representing the total number of **Auric Subsequences** of the given array, modulo $$10^9 + 7$$.

## Constraints

- $$1 \le N \le 10^5$$ and $$1 \le A_i \le 2*10^3$$

**Subtasks**

1. Subtask 1 (10 Points): $$1 \le N \le 20$$ and $$1 \le A_i \le 40$$.
2. Subtask 2 (15 Points): $$1 \le N \le 10^5$$ and $$1 \le A_i \le 50$$.
3. Subtask 3 (25 Points): $$1 \le N \le 10^5$$ and every $$A_i$$ is a prime number.
4. Subtask 4 (50 Points): $$1 \le N \le 10^5$$ and $$1 \le A_i \le 2*10^3$$.

### Sample Input 0

```
4
2 3 10 15
```

### Sample Output 0

```
7
```
