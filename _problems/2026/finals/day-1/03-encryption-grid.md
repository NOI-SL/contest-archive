---
title: "Encryption Grid"
year: 2026
category: finals
round: "Final Round — Day 1"
sortkey: "3-finals-1-03"
index: 3
max_score: 100
difficulty: "Medium"
contest_name: "NOI 2026 Day 1"
contest_slug: "noi-2026-day-1"
contest_url: "https://www.hackerrank.com/contests/noi-2026-day-1"
problem_slug: "encryption-grid"
problem_url: "https://www.hackerrank.com/contests/noi-2026-day-1/challenges/encryption-grid"
---

A cybersecurity lab is stress-testing encryption protocols across **n** servers. Each server is assigned a **security token** — a non-negative integer strictly less than $$2^k$$.

The monitoring system computes two aggregate metrics across all n tokens:

- **Defense rating**: the bitwise AND of all n tokens: $$t_1\ \&\ t_2\ \&\ \ldots\ \&\ t_n$$
- **Vulnerability score**: the bitwise XOR of all n tokens: $$t_1 \oplus t_2 \oplus \ldots \oplus t_n$$

An assignment is called **stable** if the Defense rating is **at least as large** as the Vulnerability score.

Count the number of distinct token assignments (arrays of length n with each element in $$[0, 2^k)$$) that result in a **stable** configuration.

Since the answer may be very large, print it modulo $$1\,000\,000\,007\ (10^9 + 7)$$.

## Input Format

The first line contains a single integer $$t$$ $$(1 \le t \le 5)$$ — the number of test cases.

Each test case consists of one line containing two integers $$n$$ and $$k$$ $$(1 \le n \le 2 \cdot 10^5,\ 0 \le k \le 2 \cdot 10^5)$$.

## Output Format

For each test case, print a single integer — the number of stable assignments modulo $$10^9 + 7$$.

## Constraints

**Time limit:** 2 seconds  
**Memory limit:** 256 megabytes

### Sample Input 0

```
3
3 1
2 1
4 0
```

### Sample Output 0

```
5
2
1
```
