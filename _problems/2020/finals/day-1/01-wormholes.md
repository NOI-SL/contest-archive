---
title: "Wormholes"
year: 2020
category: finals
round: "Final Round — Day 1"
sortkey: "3-finals-1-01"
index: 1
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka 2020 - Day 1"
contest_slug: "noi-2020-day-1"
contest_url: "https://www.hackerrank.com/contests/noi-2020-day-1"
problem_slug: "wormholes"
problem_url: "https://www.hackerrank.com/contests/noi-2020-day-1/challenges/wormholes"
---

As you all must be knowing Mando took baby yoda in and must keep him safe.  
  
Mando is now at star-system Nevarro. He needs to take baby yoda to the star-system Sorgan in the outer rim of the galaxy to ensure his safety. Some star-systems are connected and you can only travel safely between connected star-systems. You are given the time taken to travel between two connected star systems.  
  
Your task is to find the minimum time it takes for you to get to Sorgan.  
  
There’s some good *(may be bad)* news. Some star-systems have wormholes. And when you arrive on one of those systems you will go through the wormhole and randomly end up at one of the two star-systems the wormhole ends at. Also note that wormholes are one way.  

So now your task is to find the ***minimum time*** it takes for you to get to Sorgan in the ***worst case***.

## Input Format

First line of input contains ***3*** integers.  

- ***N*** the number of star systems, the star systems are numbered from ***0*** to ***N - 1***, where Nevarro is  ***0*** and Sorgan is ***1***.
- ***M*** the number connections among star-systems. ***(These are two way connections - you can travel in both ways)***.
- ***W*** the number of wormholes
  
Next ***M*** lines give ***3*** integers, each describing two connected star-systems. First two integers(***M<sub>a</sub>*** & ***M<sub>b</sub>***) are the two connected star-systems and third(***M<sub>w</sub>***) is the time it takes to travel between the two.  
Next ***W*** lines give ***3*** integers each. The first integer is the ***starting star system*** of the worm hole and the next two integers are the ***two star systems the wormhole could end up in***.

## Output Format

The ***minimum time*** it takes to go to Sorgan in the ***worst case***. If you cannot reach Sorgan in the worst case output ***-1***.

## Constraints

- **2 $$\leq$$ N $$\leq$$ 100**  
- **1 $$\leq$$ M $$\leq$$ 5000**  
- **0 $$\leq$$ M<sub>a</sub>, M<sub>b</sub> $$\leq$$ N - 1**  
- **1 $$\leq$$ M<sub>w</sub> $$\leq$$ 10<sup>6</sup>**  
- **0 $$\leq$$ W $$\leq$$ 20**  

##### **For 50% of test cases** 
- **W $$\leq$$ 1** 
   
#### **Limits**
- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
5 6 1
0 2 100
0 3 1
2 4 20
2 1 1
3 1 1
4 1 20
3 2 4
```

### Sample Output 0

```
21
```
