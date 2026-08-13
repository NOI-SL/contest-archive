---
title: "Beskar Armor"
year: 2020
category: finals
round: "Final Round — Day 2"
sortkey: "3-finals-2-02"
index: 2
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka 2020 - Day 2"
contest_slug: "noi-2020-day-2"
contest_url: "https://www.hackerrank.com/contests/noi-2020-day-2"
problem_slug: "besker-armor"
problem_url: "https://www.hackerrank.com/contests/noi-2020-day-2/challenges/besker-armor"
---

Mando wants to travel again. This time there are no wormholes. But most of the space in this path is hot. So he wants to forge new armor with Beskar steel that’s not only resident to blasts but also to heat.  
  
You are given the map of connected planets which Mando can travel across. Mando cannot travel directly between unconnected planets. You are given the ***time it takes to travel between two connected planets*** in seconds. You are also given the ***maximum temperature between each connected pair***. You have to get from Planet Sorgan to Nevarro within ***T*** seconds (in less than or equal to ***T*** seconds). You need to find the ***minimum temperature rating*** your armor should have to make sure you can get from Sorgan to Nevarro within ***T*** seconds. Mando can't travel on a path with a temperature higher than the rated temperature of the armor.

## Input Format

First line contains three integers ***N***, ***M*** and ***T***, where ***N*** is the number of planets and ***M*** is the number of connected pairs. Sorgan is numbered ***0*** and Nevarro is numbered ***1***. ***T*** is the number of seconds Mando has to go from Sorgan to Nevarro.  
  
The next ***M*** lines have four integers each (***X<sub>i</sub>***, ***Y<sub>i</sub>***, ***D<sub>i</sub>***, ***H<sub>i</sub>***). This means ***X<sub>i</sub>*** and ***Y<sub>i</sub>*** planets are connected and it takes ***D<sub>i</sub>*** seconds to travel between the two. Mando can travel in either direction. ***H<sub>i</sub>*** is the maximum temperature between ***X<sub>i</sub>*** and ***Y<sub>i</sub>***. That is,  Mando can travel between ***X<sub>i</sub>*** and ***Y<sub>i</sub>*** only if the temperature rating of his armor is greater than or equal to ***H<sub>i</sub>***.

## Output Format

A single integer representing the ***minimum temperature rating required*** for the armor for Mando to be able to start at Sorgan and arrive at Nevarro within ***T*** seconds. It is guaranteed that he can reach Nevarro from Sorgan.

## Constraints

- **2 $$\leq$$ N $$\leq$$ 2500**  
- **1 $$\leq$$ T $$\leq$$ 10<sup>9</sup>**  
- **1 $$\leq$$ H<sub>i</sub> $$\leq$$ 10<sup>6</sup>**  
- **1 $$\leq$$ D<sub>i</sub> $$\leq$$ 10<sup>4</sup>**   
  
   
#### **Limits**
- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
5 8 6
0 1 3 1000
0 2 1 1
0 3 5 2
2 1 20 1
2 3 3 5
3 1 2 2
0 4 1 1
4 1 20 20
```

### Sample Output 0

```
5
```
