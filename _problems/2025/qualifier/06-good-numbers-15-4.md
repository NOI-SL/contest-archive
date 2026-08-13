---
title: "A-B Good Numbers"
year: 2025
category: qualifier
round: "Qualifier Round"
sortkey: "1-qualifier-06"
index: 6
max_score: 100
difficulty: "Medium"
contest_name: "NOI 2025 Qualifier Round"
contest_slug: "noi-2025-qualifier-round"
contest_url: "https://www.hackerrank.com/contests/noi-2025-qualifier-round"
problem_slug: "good-numbers-15-4"
problem_url: "https://www.hackerrank.com/contests/noi-2025-qualifier-round/challenges/good-numbers-15-4"
---

Alice and Bob are about to play a game with numbers. Alice has an integer A and Bob has an integer B. They both will choose two numbers under the following rules:

Alice’s Choice: She writes down an A-good number — a positive integer that is divisible by A but not divisible by B.

Bob’s Choice: He writes down a B-good number — a positive integer that is divisible by B but not divisible by A.

Both chosen numbers must be at most N. Your task is to determine how many distinct pairs (x, y) can be formed such that:

x is an A-good number, and
y is a B-good number.

Since the answer may be very large, output it modulo 10^9+7.

## Input Format

A single line containing three space-separated integers:
A B N

## Output Format

Output a single integer — the number of distinct pairs (x, y) where x is A-good and y is B-good, modulo 10^9+7.

## Constraints

1 <= A, B, N <= 10^18

### Sample Input 0

```
3 5 15
```

### Sample Output 0

```
8
```
