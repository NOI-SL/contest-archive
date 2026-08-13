---
title: "Mystical Matrix Quest"
year: 2024
category: monthly
round: "February 2024"
sortkey: "2-monthly-02-04"
index: 4
max_score: 100
difficulty: "Medium"
contest_name: "NOI 2024 february monthly contest"
contest_slug: "noi-2024-feb"
contest_url: "https://www.hackerrank.com/contests/noi-2024-feb"
problem_slug: "mystical-matrix-quest"
problem_url: "https://www.hackerrank.com/contests/noi-2024-feb/challenges/mystical-matrix-quest"
---

In the ancient land of Algothria, there exists a mystical matrix with extraordinary properties. Legend has it that this matrix holds the key to unlocking the secrets of the algorithmic universe. The matrix is a square grid of size N x N, where each cell contains an integer.

The wise elders of Algothria have deciphered a riddle that reveals the path to harnessing the matrix's power. The riddle states: "Traverse the matrix, but heed the signs. Choose the path that maximizes the sum"

The matrix has a few cursed cells marked with negative integers, and you must navigate from the top-left corner to the bottom-right corner, **moving only right or down**. Your quest is to write a program to find the **maximum sum achievable**.

## Input Format

- The first line contains an integer N, representing the size of the matrix.
- The next N lines contain N space-separated integers, representing the elements of the matrix.

## Output Format

A single integer representing the maximum sum achievable by navigating from the top-left to the bottom-right corner.

## Constraints

- 1 <= N <= 100
- -1000 <= matrix[i][j] <= 1000

### Sample Input 0

```
3
1 2 -1
2 -2 4
5 6 7
```

### Sample Output 0

```
21
```

### Sample Input 1

```
3
1 2 -1
-2 -2 4
5 6 7
```

### Sample Output 1

```
17
```
