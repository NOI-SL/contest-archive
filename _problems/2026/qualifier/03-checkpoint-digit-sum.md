---
title: "Rehan and Checkpoints"
year: 2026
category: qualifier
round: "Qualifier Round"
sortkey: "1-qualifier-03"
index: 3
max_score: 100
difficulty: "Medium"
contest_name: "NOI 2026 Qualifier Round"
contest_slug: "noi-2026-qualifier-round"
contest_url: "https://www.hackerrank.com/contests/noi-2026-qualifier-round"
problem_slug: "checkpoint-digit-sum"
problem_url: "https://www.hackerrank.com/contests/noi-2026-qualifier-round/challenges/checkpoint-digit-sum"
---

Rehan is tracking a numbered sequence of checkpoints in a long training route, labeled from $$1$$ to $$N$$

During the training, rehan only pays attention to checkpoints whose numbers are divisible by $$M$$. Whenever he reaches such a checkpoint, he record the **last digit of that checkpoint number** as a small note.

For instance, if $$N = 27$$ and $$M = 9$$ the relevant checkpoints are $$9, 18$$ and $$27$$. The recorded last digits are $$9, 8$$ and $$7$$, and their total is $$24$$.

Your task is to determine the sum of all recorded digits.

You are given $$Q$$ **independent queries**, and for each query, compute the required sum.

## Input Format

First line contains an integer $$Q$$.
Next $$Q$$ lines contains queries, one per line with two integers $$N$$ and $$M$$.

## Output Format

For each query print the sum of recorded digits.

## Constraints

- $$1 ≤ Q ≤ 1000$$
- $$1 ≤ N, M ≤ 10^{16}$$

### Sample Input 0

```
1
27 9
```

### Sample Output 0

```
24
```
