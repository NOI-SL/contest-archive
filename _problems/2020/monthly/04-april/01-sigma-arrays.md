---
title: "Sigma Arrays"
year: 2020
category: monthly
round: "April 2020"
sortkey: "2-monthly-04-01"
index: 1
max_score: 100
difficulty: "Easy"
contest_name: "National Olympiad in Informatics Sri Lanka - April 2020"
contest_slug: "noi-2020-apr"
contest_url: "https://www.hackerrank.com/contests/noi-2020-apr"
problem_slug: "sigma-arrays"
problem_url: "https://www.hackerrank.com/contests/noi-2020-apr/challenges/sigma-arrays"
---

You are given two arrays ***A*** and ***B***, each containing ***N*** number of distinct positive integers. In other words, ***A*** and ***B*** are sets of positive integers such that $$n(A) = n(B) = N$$. But a number in ***A*** can appear in ***B*** and vice versa.  
  
For each integer (***A<sub>i</sub>*** ) in ***A*** , you need to pair it with an integer (***B<sub>j</sub>*** ) in ***B***. You are not allowed to pick the same integer (***B<sub>j</sub>*** ) from ***B*** more than once.  
  
If it’s possible to create ***N*** pairs such that the sum of each pair is the same, then the two arrays are considered as **Sigma Arrays**.  

Given two arrays, your task is to determine whether they are **Sigma Arrays**, AND if they are **Sigma Arrays**, create ***N*** pairs of integers that display this quality.

## Input Format

First line contains a single integer ***N***, the number of elements in each array.  
Next line contains ***N*** integers, the elements of the array ***A***, with ***i<sup> th</sup>*** of them being ***A<sub>i</sub>***.  
Last line contains ***N*** integers, the elements of the array ***B***, with ***i<sup> th</sup>*** of them being ***B<sub>i</sub>***.

## Output Format

If they **are Sigma Arrays**, print ***N*** lines, each containing a pair (***A<sub>i</sub>*** , ***B<sub>j</sub>*** ), sorted in the increasing order of ***A<sub>i</sub>***.  
If the two arrays are **not Sigma Arrays**, print ***-1***  
  
Refer the samples for a clearer picture.

## Constraints

- **1 $$\leq$$ N $$\leq$$ 10<sup>5</sup>**  
- **1 $$\leq$$ A<sub>i</sub> , B<sub>i</sub> $$\leq$$ 10<sup>9</sup>**  
   
#### **Limits**
- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
8
20 10 11 4 8 3 1 5
29 27 25 22 26 20 19 10
```

### Sample Output 0

```
1 29
3 27
4 26
5 25
8 22
10 20
11 19
20 10
```

### Sample Input 1

```
10
2 12 4 5 6 8 15 3 45 99
1 5 3 24 15 13 48 56 32 10
```

### Sample Output 1

```
-1
```
