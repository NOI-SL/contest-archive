---
title: "Open the chest 1"
year: 2025
category: qualifier
round: "Qualifier Round"
sortkey: "1-qualifier-01"
index: 1
max_score: 100
difficulty: "Hard"
contest_name: "NOI 2025 Qualifier Round"
contest_slug: "noi-2025-qualifier-round"
contest_url: "https://www.hackerrank.com/contests/noi-2025-qualifier-round"
problem_slug: "open-the-chest-1-1"
problem_url: "https://www.hackerrank.com/contests/noi-2025-qualifier-round/challenges/open-the-chest-1-1"
---

Deep in a mystical cave lies an infinite row of treasure chests labeled from 1 onwards. Guarding these chests are 40 magic locks, each labeled from 1 to 40.

A lock labeled x can seal multiple chests—specifically, all chests whose labels are multiples of x.

For example:

Lock 2 seals chests 2, 4, 6, 8, ...

Lock 3 seals chests 3, 6, 9, 12, ...

Some chests are sealed by multiple locks, while others remain unlocked (if no lock seals them).

A curious adventurer, Riya, discovers that only locks with prime numbers (2, 3, 5, 7, ...) are active, while the rest are broken and harmless.

A chest can be opened (unlocked) if at least one active lock seals it. Riya wants to find the K-th openable chest in the sequence.

## Input Format

First line contains number of test cases (T). Each test case contains two lines- First line contains a string S of length 40 containing 0s and 1s that represents the state of locks. 1 is Unlocked , 0 is Locked. Second line contains one integer k. Atleast One chest is in Unlocked condition.

## Output Format

Output one integer per test case representing kth unlocked chest.

## Constraints

1 <= T <= 500

S contains only 0s and 1s. 1s are only at prime positions.

1 <= k <= 10^15

1 is not prime

### Sample Input 0

```
3
0110000000000000000000000000000000000000
5
0010000000000000000000000000000000000000
5
0100000000100000001000100000101000001000
16807
```

### Sample Output 0

```
8
15
26866
```
