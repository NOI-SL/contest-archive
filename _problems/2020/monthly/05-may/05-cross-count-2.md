---
title: "Cross Count 2"
year: 2020
category: monthly
round: "May 2020"
sortkey: "2-monthly-05-05"
index: 5
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - May 2020"
contest_slug: "noi-2020-may"
contest_url: "https://www.hackerrank.com/contests/noi-2020-may"
problem_slug: "cross-count-2"
problem_url: "https://www.hackerrank.com/contests/noi-2020-may/challenges/cross-count-2"
---

You're back at the same problem, but this time the limits are high as sky.


There is a Cartesian plane with ***N*** vertical lines (**infinitely long**), and ***M*** line segments (**finite**).  
Your task is to count the total number of crossings made by the finite line segments, with the infinitely long vertical lines.

Example:
There are ***N = 4*** infinitely long vertical lines, at 
		
$$x=-5, -3,\ \ \ 2,\ \ \ 4$$

There are ***M = 8*** finite line segments:

$${(-2,\ \ \ 5),(\ \ \ 5,-6)}$$  
$${(-5,-2),(-3,-5)}$$  
$${(-2,\ \ \ 3),(-6,\ \ \ 1)}$$  
$${(-1,-3),(\ \ \ 4,\ \ \ 2)}$$  
$${(\ \ \ 2,\ \ \ 5),(\ \ \ 2,\ \ \ 1)}$$  
$${(\ \ \ 4,\ \ \ 5),(\ \ \ 4,-5)}$$  
$${(-2,-4),(\ \ \ 5,\ \ \ 3)}$$  
$${(\ \ \ 1,\ \ \ 2),(-2,\ \ \ 1)}$$  

After marking the infinitely long vertical lines and the line segments, the Cartesian plane looks like
this.

![image]({{ "/assets/problems/546ef5f6-1590111566-39ea052506-Screenshot_2020-05-22CrossCount.png" | relative_url }})

The **circles** denote the crossings. **Black** circles denote **1** crossing. **Red** circles denote **2** crossings.
So the answer is **8**.

## Input Format

First line contains two integers, ***N*** and ***M***.  
Second line contains ***N*** space separated integers, with i<sup>th</sup> of them indicating ***X<sub>i</sub>***, the x coordinate of the i<sup>th</sup> infinitely long vertical line.  
***M*** lines follow, each containing 4 space separated integers, ***x<sub>1</sub>***, ***y<sub>1</sub>***, ***x<sub>2</sub>***, ***y<sub>2</sub>***, The start and end points of the line segments.

## Output Format

A single **integer**, denoting the total number of crossings between the infinitely long vertical lines
and the line segments.  
   
#### **Notes**
- The output might not fit into Integer data type.
- For contestants using C++ or Java, you might need to use faster I/O techniques. (Refer: [C++](https://www.geeksforgeeks.org/fast-io-for-competitive-programming/) / [Java](https://www.geeksforgeeks.org/fast-io-in-java-in-competitive-programming/))

## Constraints

- **1 $$\leq$$ n, m $$\leq$$ 10<sup>6</sup>**
- **-10<sup>16</sup> $$\leq$$ X<sub>i</sub>, x<sub>1</sub>, y<sub>1</sub>, x<sub>2</sub>, y<sub>2</sub> $$\leq$$ 10<sup>16</sup>**  
   
#### **Limits**
- **Time Limit**: 2s
- **Memory Limit**: 256MB

### Sample Input 0

```
4 8
-5 -3 2 3
-2 5 5 -6
-5 -2 -3 -5
-2 3 -6 1
-1 -3 4 2
2 5 2 1
4 5 4 -5
-2 -4 5 3
1 2 -2 1
```

### Sample Output 0

```
8
```
