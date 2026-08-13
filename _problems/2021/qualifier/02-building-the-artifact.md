---
title: "Building the artifact"
year: 2021
category: qualifier
round: "Selection Test"
sortkey: "1-qualifier-02"
index: 2
max_score: 100
difficulty: "Easy"
contest_name: "National Olympiad in Informatics Sri Lanka - Screening Test 2021"
contest_slug: "noi-2021-selection-test"
contest_url: "https://www.hackerrank.com/contests/noi-2021-selection-test"
problem_slug: "building-the-artifact"
problem_url: "https://www.hackerrank.com/contests/noi-2021-selection-test/challenges/building-the-artifact"
---

Captain America has to go back in time and collect parts to build an artifact.

Some of these parts are interconnected with a powerful force. If there's a connection from part A to part B. Captain must collect part B before collecting A.

Sometimes a part of an artifact can be connected with itself, making it impossible to collect it.

When he collects all the parts, he can build the artifact.

## Input Format

- First line contains `n c` the number of parts and connections
- Next `c` lines contain `a b` indicating connections from part `a` to part `b`

## Output Format

Output "YES" if the artifact can be built, "NO" if it cannot be built.

## Constraints

`1 <= n <= 100,000`

`0 <= r <= 5000`

### Sample Input 0

```
2 1
1 0
```

### Sample Output 0

```
YES
```
