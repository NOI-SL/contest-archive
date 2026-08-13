---
title: "Largest Polygon"
year: 2020
category: monthly
round: "May 2020"
sortkey: "2-monthly-05-03"
index: 3
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - May 2020"
contest_slug: "noi-2020-may"
contest_url: "https://www.hackerrank.com/contests/noi-2020-may"
problem_slug: "largest-polygon"
problem_url: "https://www.hackerrank.com/contests/noi-2020-may/challenges/largest-polygon"
---

You are given a set of ***N*** points in the ***XY*** plane. There are many ways to make polygons (both concave and convex) in the ***XY*** plane connecting a subset of these points.  
You have to select a subset from the given coordinates so that you can maximize the area of the polygon to find the largest polygon. Your task is to output the number of sides of this largest polygon.

## Input Format

First line contains a single integer ***N***, the number of coordinates  
***N*** lines follow, with ***i <sup>th</sup>*** of them having 2 integers, ***x<sub>i</sub>*** , ***y<sub>i</sub>*** , the ***x*** & ***y*** coordinates of the ***i <sup>th</sup>*** point

## Output Format

A single integer, the number of sides in the largest polygon.

## Constraints

- **4 $$\leq$$ N $$\leq$$ 10<sup>3</sup>**
- **1 $$\leq$$ x<sub>i</sub> , y<sub>i</sub> $$\leq$$ 10<sup>6</sup>**
- More than ***25%*** of the test cases will have ***N $$\leq$$ 100***  
   
#### **Limits**
- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
5
2 2
0 2
1 1
0 0
2 0
```

### Sample Output 0

```
4
```

### Sample Input 1

```
10
0 2
1 2
2 1
0 1
1 1
2 2
3 1
0 0
1 0
2 0
```

### Sample Output 1

```
5
```
