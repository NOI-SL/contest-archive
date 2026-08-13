---
title: "Planet Cruise"
year: 2023
category: monthly
round: "March 2023"
sortkey: "2-monthly-03-03"
index: 3
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - March 2023"
contest_slug: "noi-2023-mar"
contest_url: "https://www.hackerrank.com/contests/noi-2023-mar"
problem_slug: "planet-cruise"
problem_url: "https://www.hackerrank.com/contests/noi-2023-mar/challenges/planet-cruise"
---

There are $$n$$ planets in a solar system (In this universe planets lie on a 2D coordinate plane). **You're on the first planet and you need to reach the planet with the highest $$x$$ coordinate using your spaceship.**

Coordinates of the first planet is [0,0]. Coordinates of other planets are given to you. When you visit the $$i^{th}$$ planet at $$t^{th}$$ hour you have to pay $$v_{i,t}$$ for the planetory visa. You'll need spaceship fuel to travel between planets. Speed of the spaceship is 1 distance unit per hour. (to travel 5 distance units it will take 5 hours). Distance between two planets is the manhattan distance of their coordinates. You're only allowed to carry enough fuel to reach your next destination. In $$i^{th}$$ planet you can buy fuel for the price $$f_i$$.

You're only allowed to move to planets which has **higher $$x$$ coordinate than the current planet you're in**. You can choose any order of planets you want to visit (not breaking the increasing $$x$$ rule) and you do not have to visit all planets, except the planet with the highest $$x$$ coordinate.

Find the **minimum cost** required for the journey and output on a single line.

Note: It is guaranteed that one x coordinate will contain only one planet.

**Subtasks**

- In 50% of testcases $$n<=10$$, $$T<=50$$

## Input Format

First line contains $$n$$, the number of planets

next $$n$$ lines has $$x$$ $$y$$, x axis and y axis position of the planet

next line contains $$n$$ integers, $$f_1$$, $$f_2$$, $$f_3$$, ... $$f_n$$

next line contains integer $$T$$

Next $$n$$ lines contains $$T$$ integers each, $$v_{i,t} (0<=t<=T-1)$$

## Output Format

Single integer containing the minimum cost. It is guaranteed that a solution exists.

## Constraints

- All inputs are integers.
- $$2<n<10^2$$
- $$2<T<5*10^2$$
- $$0<v_{i,t}<10^6$$
- $$0<f_i<10^6$$
- $$0<x<10^2$$
- $$0<y<4$$

### Sample Input 0

```
3
0 0
2 0
1 0
10 30 20
3
0 0 0
100 100 10
100 100 100
```

### Sample Output 0

```
30
```
