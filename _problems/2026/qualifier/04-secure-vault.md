---
title: "Secure Vault"
year: 2026
category: qualifier
round: "Qualifier Round"
sortkey: "1-qualifier-04"
index: 4
max_score: 100
difficulty: "Medium"
contest_name: "NOI 2026 Qualifier Round"
contest_slug: "noi-2026-qualifier-round"
contest_url: "https://www.hackerrank.com/contests/noi-2026-qualifier-round"
problem_slug: "secure-vault"
problem_url: "https://www.hackerrank.com/contests/noi-2026-qualifier-round/challenges/secure-vault"
---

Bob is upgrading the main security vault for the robotics lab. The vault’s locking mechanism requires an array of $$N$$ positive integers, $$A_1, A_2, \dots, A_N$$. 

To bypass the lock, the array must satisfy two strict security protocols:
1. **The Energy Rule:** The sum of all $$N$$ integers must be exactly equal to $$S$$. ($$A_1 + A_2 + \dots + A_N = S$$)
2. **The Encryption Rule:** To maximize the cryptographic strength of the lock, the **Greatest Common Divisor (GCD)** of all $$N$$ integers must be as large as possible.

Given $$N$$ (the number of integers required) and $$S$$ (the target sum), help Bob find the maximum possible GCD the array can have.

*Note: The GCD of an array is the largest positive integer that divides all elements of the array without leaving a remainder.*

## Input Format

* The first line contains a single integer $$T$$, the number of test cases.
* The next $$T$$ lines each contain two space-separated integers, $$N$$ and $$S$$.

## Output Format

* For each test case, print a single integer: the maximum possible GCD of the $$N$$ integers.

## Constraints

* $$1 \le T \le 100$$
* $$1 \le N \le S \le 10^{12}$$

### Sample Input 0

```
3
3 12
4 14
5 5
```

### Sample Output 0

```
4
2
1
```
