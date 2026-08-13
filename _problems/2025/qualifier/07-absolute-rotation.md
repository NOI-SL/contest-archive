---
title: "Absolute Rotation"
year: 2025
category: qualifier
round: "Qualifier Round"
sortkey: "1-qualifier-07"
index: 7
max_score: 100
difficulty: "Medium"
contest_name: "NOI 2025 Qualifier Round"
contest_slug: "noi-2025-qualifier-round"
contest_url: "https://www.hackerrank.com/contests/noi-2025-qualifier-round"
problem_slug: "absolute-rotation"
problem_url: "https://www.hackerrank.com/contests/noi-2025-qualifier-round/challenges/absolute-rotation"
---

You are given an array of **n** integers. You need to transform this array **m** times according to the following rule:  

- The new value of the ith element in the array is the absolute difference between the **(i+1)** th element and the **i** th element of the previous array.  
- The **last element** of the array is updated as the absolute difference between the last and first elements of the previous array.  

After applying this transformation **m** times, output the resulting array.

## Input Format

The first line contains two integers \( n \) and \( m \) — the size of the array and the number of transformations.  
The second line contains \( n \) space-separated integers representing the initial array.

## Output Format

Print \( n \) space-separated integers — the array after performing the transformation \( m \) times.

## Constraints

-  1 <= n*m <= 10^6
-  1 <= a[i] <= 10^9

### Sample Input 0

```
5 3  
4 7 2 9 5  
```

### Sample Output 0

```
0 1 0 1 0  
```
