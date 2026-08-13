---
title: "Save More Water"
year: 2020
category: monthly
round: "April 2020"
sortkey: "2-monthly-04-02"
index: 2
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - April 2020"
contest_slug: "noi-2020-apr"
contest_url: "https://www.hackerrank.com/contests/noi-2020-apr"
problem_slug: "save-more-water"
problem_url: "https://www.hackerrank.com/contests/noi-2020-apr/challenges/save-more-water"
---

The ruler of Gampola Kingdom has decided to cultivate more paddy fields next year in order to expand the exports. But all his new lands are in the dry zone. So the ruler wants to collect more rainfall. But the bad news is they are 2 weeks before the monsoon rain season. So he decided to quickly convert part of his ruined palace to a water tank. The remaining ruin is almost like a giant water tank. It has two long parallel walls with a 1m gap running from East to West.  
  
Originally, there were ***N-1*** rooms created by ***N*** walls running perpendicular to the two long parallel walls. Unfortunately, all the walls are seriously damaged due to the last war.  

The walls are cracked from top to bottom and are of different heights. As the kingdom is about to get the rainfall, ruler wants to repair the tanks to contain as much rainfall as possible. He has already finished repairing the two long parallel walls. Due to the time constraints, he can **only repair 2 more walls** out of the ***N*** walls.  
  
After repairing a wall of height ***h***, it can retain a water column up to a height ***h***. So the ruler needs your help to choose ***2*** walls from ***N*** walls to repair in order to store **maximum amount of rainfall**.  
  
He has given you the heights of ***N*** walls in order from East to West. He’s repaired the two long parallel walls to a height much higher than any of the ***N*** walls, and the gap between any two consecutive walls is ***1m***.

## Input Format

First line contains a single integer ***N***, the number of separation walls.  
Next line contains ***N*** space-separated integers, with ***i <sup>th</sup>*** of them denoting height ***h<sub>i</sub>*** of the ***i <sup>th</sup>*** wall.

## Output Format

A single integer, the maximum amount of rainfall you can retain after repairing the two walls (in cubic meters).

## Constraints

- **2 $$\leq$$ N $$\leq$$ 10<sup>5</sup>**  
- **1 $$\leq$$ H<sub>i</sub> $$\leq$$ 10<sup>4</sup>**  
   
#### **Limits**
- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
7
3 6 7 1 3 8 2
```

### Sample Output 0

```
24
```
