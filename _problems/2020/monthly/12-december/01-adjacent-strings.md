---
title: "Adjacent Strings"
year: 2020
category: monthly
round: "December 2020"
sortkey: "2-monthly-12-01"
index: 1
max_score: 100
difficulty: "Easy"
contest_name: "National Olympiad in Informatics Sri Lanka - December 2020"
contest_slug: "noi-2020-dec"
contest_url: "https://www.hackerrank.com/contests/noi-2020-dec"
problem_slug: "adjacent-strings"
problem_url: "https://www.hackerrank.com/contests/noi-2020-dec/challenges/adjacent-strings"
---

A string is said to be ***adjacent*** if it contains ***distinct*** letters and the string is made from an ***adjacent segment*** of the English alphabet. 

**“pqrs”** is an adjacent segment of  the alphabet. 
So **"pqrs"**, **"srqp"**, **"qprs"** and **"rspq"** adjacent strings, but  **"ppqrs"**, **"ssrpq"** and **"rrqps"** are not.

You are given ***n*** strings. If the given string is an ***adjacent string*** print ***"Yes"***, otherwise print ***"No"***.

## Input Format

First line will be a single integer ***n***, the number of input strings.
Following ***n*** lines will have a string in each line.

## Output Format

***n*** lines containing answers(either ***"Yes"*** or ***"No"***) for each query

## Constraints

- **1 $$\leq$$ n $$\leq$$ 10<sup>5</sup>**  
- **1 $$\leq$$ length of a string $$\leq$$ 26**
- All the strings will be in lowercase

#### **Limits**
- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
3
pqrs
rspq
pqs
```

### Sample Output 0

```
Yes
Yes
No
```
