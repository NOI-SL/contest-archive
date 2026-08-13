---
title: "Two Spindles"
year: 2022
category: finals
round: "Final Round — Day 1"
sortkey: "3-finals-1-02"
index: 2
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka 2022 - Day 1"
contest_slug: "noi-2022-day-1"
contest_url: "https://www.hackerrank.com/contests/noi-2022-day-1"
problem_slug: "two-spindles"
problem_url: "https://www.hackerrank.com/contests/noi-2022-day-1/challenges/two-spindles"
---

Nimal and his group of friends are going to create a Vesak decoration. To create the Vesak decoration, they bought a set of **N** disks of different radii and two spindles. The decoration will be created by mounting disks on the spindles. But unfortunately, the maximum difference between the radius of any two disks in a spindle cannot exceed **K**. Nimal wants your support to know the maximum beauty value of the decoration so that he can show the decoration confidently to the public. The beauty value increases with the number of disks used therefore Nimal wants to know how many disks can be mounted to the two spindles. (Any number of disks can be mounted to a spindle while satisfying the conditions for the radii). 

You have to help Nimal calculate the maximum number of disks that can be mounted. 


![image]({{ "/assets/problems/04bb9eaa-1656729590-7a82f5ead3-diy_spindles.jpeg" | relative_url }})

## Input Format

First Line: **N K**

Next **N** lines: radius of the **i<sup>th</sup>** disk

## Output Format

A single integer denoting the maximum number of disks that can be mounted.

## Constraints

- 1 $$\leq$$ N $$\leq$$ 10<sup>6</sup>
- 1 $$\leq$$ K $$\leq$$ 10<sup>9</sup>
- 1 $$\leq$$ radius of each disk $$\leq$$ 10<sup>9</sup>


#### **Limits**
- **Time Limit**: 1s
- **Memory Limit**: 512MB

### Sample Input 0

```
7 3
10
5
1
12
9
5
14
```

### Sample Output 0

```
5
```
