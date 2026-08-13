---
title: "Find the Worlds"
year: 2020
category: finals
round: "Final Round — Day 2"
sortkey: "3-finals-2-03"
index: 3
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka 2020 - Day 2"
contest_slug: "noi-2020-day-2"
contest_url: "https://www.hackerrank.com/contests/noi-2020-day-2"
problem_slug: "find-the-worlds"
problem_url: "https://www.hackerrank.com/contests/noi-2020-day-2/challenges/find-the-worlds"
---

There are ***M*** known worlds in a ***two-dimensional*** universe. Each world contains one or more cities, and each city will be located in one of those ***M*** worlds. A city is a ***point in the 2D universe*** that is represented by an integer coordinate ***(x,y)***. No more than 1 city will share the same coordinate.  
  
The distance between two cities is the ***euclidean distance*** (the distance of the straight line) between the two points. All the cities in the universe are laid out satisfying the following conditions:

- ***Distance between any two cities of any given world ≤ 10,000***  
- ***Distance between any two cities from different worlds > 10,000***  
  
Given the location of cities, find the number of worlds in the universe and the number of cities in each world.

## Input Format

The first line contains the number of cities, ***N***   
Each of the next ***N*** lines contains ***2*** integers separated by a space representing ***X***,***Y*** coordinate of a city.

## Output Format

The first line should contain the number of worlds in the universe, ***M***   
The second line should contain the number of cities in each of those ***M*** worlds. These ***M*** integers should be separated by a space and sorted in the ascending order.

## Constraints

- **1 $$\leq$$ N $$\leq$$ 10<sup>7</sup>**  
- **-10<sup>9</sup> $$\leq$$ X, Y $$\leq$$ 10<sup>9</sup>** where ***(X,Y)*** are the integer coordinates of cities.   
  
At least ***30%*** of test cases will have **N $$\leq$$ 10,000**  
   
#### **Limits**
- **Time Limit**: 2s
- **Memory Limit**: 256MB

### Sample Input 0

```
5
2 1
3 1
2 100000
2 100002
1 1
```

### Sample Output 0

```
2
2 3
```
