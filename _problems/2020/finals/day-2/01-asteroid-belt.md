---
title: "Asteroid Belt"
year: 2020
category: finals
round: "Final Round — Day 2"
sortkey: "3-finals-2-01"
index: 1
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka 2020 - Day 2"
contest_slug: "noi-2020-day-2"
contest_url: "https://www.hackerrank.com/contests/noi-2020-day-2"
problem_slug: "asteroid-belt"
problem_url: "https://www.hackerrank.com/contests/noi-2020-day-2/challenges/asteroid-belt"
---

There are a bunch of asteroids in a belt. For simplicity let's assume the asteroids are in a straight-line from left to right. You want to explore these asteroids. You can start at any asteroid and finish at any asteroid. However you can only travel towards the right. You want to visit and explore as **many** asteroids as possible.  
  
There is another problem. Your tiny ship can **only** jump from an asteroid to another **if the second asteroid has a larger diameter** than the first. However, from some **exceptional asteroids** you can jump to either an **asteroid with a larger diameter** or to **one or more specified asteroids**.  
  
You are given the diameters of the asteroids and the exceptions. You need to compute the ***maximum number of asteroids*** you can visit.

## Input Format

First line contains ***N*** and ***E***. ***N*** is the number of asteroids and ***E*** is the number of exceptions.  
The second line contains ***N*** positive integers representing the diameters of the ***N*** asteroids from left to right order.  
The following ***E*** lines contain two pairs of integers (***X<sub>i</sub>***, ***Y<sub>i</sub>***) each, giving the exception.  
This means that you can jump from the asteroid numbered ***X<sub>i</sub>*** to asteroid ***Y<sub>i</sub>*** regardless of their diameters. The asteroids are numbered from ***0*** to ***N-1*** from left to right.  
***X<sub>i</sub>*** will always be less than ***Y<sub>i</sub>*** (***X<sub>i</sub>*** < ***Y<sub>i</sub>***).

## Output Format

Output a single number indicating the ***maximum number of asteroids*** you can visit.

## Constraints

- **1 $$\leq$$ N $$\leq$$ 10<sup>4</sup>**  
- **0 $$\leq$$ E $$\leq$$ 10<sup>4</sup>**  
  
   
#### **Limits**
- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
10 2
1 2 3 6 4 7 1 4 5 6
2 5
4 6
```

### Sample Output 0

```
8
```
