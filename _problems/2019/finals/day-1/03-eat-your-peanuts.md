---
title: "Eat Your Peanuts"
year: 2019
category: finals
round: "Final Round — Day 1"
sortkey: "3-finals-1-03"
index: 3
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - Day 1"
contest_slug: "noi-2019-day-1"
contest_url: "https://www.hackerrank.com/contests/noi-2019-day-1"
problem_slug: "eat-your-peanuts"
problem_url: "https://www.hackerrank.com/contests/noi-2019-day-1/challenges/eat-your-peanuts"
---

You and your friends are at a peanut eating contest. There are **N** plates on the table in order **1 to N.** You are given the number of peanuts in each plate (not all equal).

You need to **assign** each of your friends **one or more plates** that are **next to each other.** You also need to make sure that **no one eats too much** and hurt themselves. It is okay if you **don’t assign** plates to **some** of your friends, but **all plates** should be **assigned** to someone. Same plate **cannot** be assigned to **more than one** of your friends. 

Write a program to **minimize** the **total number** of peanuts eaten by the friend who eats the **most number** of peanuts.

## Limits  
Time Limit: 1s  
Memory Limit: 256MB

## Input Format

The first line of the input has **2** integers **N** and **F** respectively, separated by a space. The number of plates and the number of friends.
Each of the following **N** lines have a single integer, **A<sub>i</sub>** the number of peanuts in the **i<sup>th</sup>** plate. There can be empty plates too. (0 peanuts in the plate)

## Output Format

Output just **one integer** representing your answer, the **total number of peanuts** eaten by the friend who eats most peanuts.

## Constraints

- **1 $$\leq$$ N $$\leq$$ 10<sup>6</sup>**
- **1 $$\leq$$ F $$\leq$$ 10<sup>3</sup>**
- **1 $$\leq$$ A<sub>i</sub> $$\leq$$ 10<sup>3</sup>**

### Sample Input 0

```
6 3
4
2
3
7
1
9
```

### Sample Output 0

```
9
```
