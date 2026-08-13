---
title: "Best King"
year: 2021
category: finals
round: "Final Round — Day 2"
sortkey: "3-finals-2-01"
index: 1
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka 2021 - Day 2"
contest_slug: "noi-2021-day-2"
contest_url: "https://www.hackerrank.com/contests/noi-2021-day-2"
problem_slug: "best-king"
problem_url: "https://www.hackerrank.com/contests/noi-2021-day-2/challenges/best-king"
---

King Unumagudut decided to travel each city one after another from the southernmost city to the northernmost city, along the way in the newly built motorway. There are ***N*** cities and cities are numbered from ***0*** to ***N-1*** from the southernmost city to the northernmost city. Location of city ***i*** is (***0***, ***y<sub>i</sub>*** ). No two cities are located at the same position.  
  
The king wants to hold meetings in some of the cities they stop by. As the king's chief advisor you want the king to keep believing that he's the most successful ruler in the world. Therefore you want to hold the meetings in some of the cities during the king's travel so that total success score is maximized.  
  
For each city ***i***, you know how much positive score you can achieve (***P<sub>i</sub>*** ) because you can control the crowd taking part in the meetings. But for each city ***i*** they hold a meeting, the king will lose score equal to ***L<sub>i</sub>*** * distance to any previous city they held a meeting at.  
They will not lose score for the first meeting they hold.  
  
Given ***P<sub>i</sub>***, ***L<sub>i</sub>*** and ***y<sub>i</sub>*** for all ***N*** cities, calculate the maximum score

## Input Format

First line contains an integer, ***N***. 

Next ***N*** lines represent data for city ***0*** to ***N-1*** in that order. Each line will contain ***3*** integers separately representing ***y<sub>i</sub>***, ***P<sub>i</sub>*** and ***L<sub>i</sub>*** respectively.

## Output Format

Output only one integer, the maximum score.

## Constraints

- **0 $$\leq$$ L<sub>i</sub>, P<sub>i</sub> $$\leq$$ 10<sup>3</sup>**  
- **0 $$\leq$$ y<sub>i</sub> $$\leq$$ 2*10<sup>6</sup>**  
- **0 $$\leq$$ N $$\leq$$ 10<sup>6</sup>**  
    
#### **Limits**  

- **Time Limit**: 2s
- **Memory Limit**: 256MB

### Sample Input 0

```
3
0 10 0
1 1 12
3 7 2
```

### Sample Output 0

```
11
```
