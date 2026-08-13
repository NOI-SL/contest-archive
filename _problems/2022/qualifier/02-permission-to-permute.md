---
title: "Permission to Permute"
year: 2022
category: qualifier
round: "Selection Test"
sortkey: "1-qualifier-02"
index: 2
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - Screening Test 2022"
contest_slug: "noi-2022-selection-test"
contest_url: "https://www.hackerrank.com/contests/noi-2022-selection-test"
problem_slug: "permission-to-permute"
problem_url: "https://www.hackerrank.com/contests/noi-2022-selection-test/challenges/permission-to-permute"
---

Given ***n***, find whether an arrangement of positive integers from **1** to ***n*** exists such that the absolute difference between adjacent integers is in the set {2,3,4}.  If there exists such an arrangement, print it.

## Input Format

- The first line contains an integer ***t*** denoting the number of test cases
- The following ***t*** lines each contain the value of ***n*** for a given case

## Output Format

- For a given ***n***, print a space-separated arrangement of integers that correspond to the given criteria. If no such arrangement exists, print -1.

## Constraints

- 1 $$\leq$$ ***t*** $$\leq$$ 100
- 2 $$\leq$$ ***n*** $$\leq$$ 1000

#### **Limits**

- **Time Limit**: 2s
- **Memory Limit**: 256MB

### Sample Input 0

```
4
10
6
13
2
```

### Sample Output 0

```
9 6 10 8 4 7 3 1 5 2
5 3 6 2 4 1
13 9 7 11 8 4 1 3 5 2 6 10 12 
-1
```

### Sample Input 1

```
2
1
5
```

### Sample Output 1

```
-1
5 3 1 4 2
```
