---
title: "Delete the Binary String"
year: 2020
category: monthly
round: "July 2020"
sortkey: "2-monthly-07-01"
index: 1
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - July 2020"
contest_slug: "noi-2020-jul"
contest_url: "https://www.hackerrank.com/contests/noi-2020-jul"
problem_slug: "delete-the-binary-string"
problem_url: "https://www.hackerrank.com/contests/noi-2020-jul/challenges/delete-the-binary-string"
---

You are given a string of length ***N*** and an array ***A*** of size ***N***, numbered from ***1*** to ***N***. String only has ‘1’s and ‘0’s.

You should do the following operations until the string becomes empty.

Select a part from the string such that all characters are the same and delete that part.
Then reconnect the remaining parts of the string without changing the order.

You will get ***A<sub>x</sub>*** points for deleting part of length ***x***  from the string. Your task is to maximize the points you can get.

## Input Format

- First line contains single integer ***N***, length of the string
- Second line contains the binary string ***S***
- Third line contains ***N*** space seperated integers ***A<sub>i</sub> (1 $$\leq$$ i $$\leq$$ N), A<sub>i</sub>*** = Number of points you can get by deleting length i part.

## Output Format

- Print one integer — the maximum total points you can get.

## Constraints

- **1 $$\leq$$ N $$\leq$$ 100**  
- **1 $$\leq$$ A<sub>i</sub> $$\leq$$ 10<sup>9</sup>**

### Sample Input 0

```
7
1101001
4 5 10 101 2 3 4
```

### Sample Output 0

```
113
```
