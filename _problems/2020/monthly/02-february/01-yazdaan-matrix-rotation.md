---
title: "Yazdaan's Matrix Rotation"
year: 2020
category: monthly
round: "February 2020"
sortkey: "2-monthly-02-01"
index: 1
max_score: 100
difficulty: "Easy"
contest_name: "National Olympiad in Informatics Sri Lanka - February 2020"
contest_slug: "noi-2020-feb"
contest_url: "https://www.hackerrank.com/contests/noi-2020-feb"
problem_slug: "yazdaan-matrix-rotation"
problem_url: "https://www.hackerrank.com/contests/noi-2020-feb/challenges/yazdaan-matrix-rotation"
---

Yazdaan loves to work with numbers. He especially likes to work with [matrices](https://en.wikipedia.org/wiki/Matrix_(mathematics)). Yazdaan doesn’t like to keep things the same way all the time. He likes to do all sorts of things to stir things up. Right now, he wants to figure out what a matrix would look like, when it’s rotated. Since he’s too lazy to do it manually, he’s seeking your help to create a program to do it. 
Given a matrix of ***H*** height & ***W*** width, the program should do ***N*** rotations to the matrix in ***D*** direction and print the result.

## Input Format

First line contains 3 integers, ***H***, ***W***, ***N***. Followed by a character(‘*l*’ or ‘*r*’), ***D***.  
***H*** lines follow, each with ***W*** integers, with the ***I<sub>h,w</sub>*** being the integer in the **h<sup>th</sup>** row and **w<sup>th</sup>** column.

## Output Format

A matrix of ***H*** x ***W*** or a matrix of ***W*** x ***H***.

## Constraints

- **1 $$\leq$$ H, W $$\leq$$ 500**
- **1 $$\leq$$ N $$\leq$$ 1000**
- **-10<sup>7</sup> $$\leq$$ I<sub>h,w</sub> $$\leq$$ 10<sup>7</sup>**
  &nbsp;  
   
#### **Limits**
- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
5 4 1 r
2 1 1 3
7 9 7 5
0 4 2 5
9 1 9 1
5 1 0 3
```

### Sample Output 0

```
5 9 0 7 2 
1 1 4 9 1 
0 9 2 7 1 
3 1 5 5 3 
```
