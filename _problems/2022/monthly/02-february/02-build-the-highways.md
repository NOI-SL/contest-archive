---
title: "Build the Highways"
year: 2022
category: monthly
round: "February 2022"
sortkey: "2-monthly-02-02"
index: 2
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - February 2022"
contest_slug: "noi-2022-feb"
contest_url: "https://www.hackerrank.com/contests/noi-2022-feb"
problem_slug: "build-the-highways"
problem_url: "https://www.hackerrank.com/contests/noi-2022-feb/challenges/build-the-highways"
---

There's a developing nation that wants to build the country's highway network. There are ***H*** number of segments in the higway network numbered from **1 to H.** The highway segments are connected, if thier difference between their number is 1(Ex: 1 & 2 are connected, 4 & 3 are connected. But 3 & 5 are not connected). Different segments of the highway have different lengths. They are going to issue the contract of each highway segment to you and your friends.  

You have to **assign** each of your friends **one or more segments** that are **connected to each other.** The payment for a highway segment is propotional to the length of the highway segment(The payment for a long highway segment is higher than the payment for a shorter highway segment). So, you also need to make sure that **no one gets too much** of profit. It is okay if some of your friends **don't get to build** a highway segment, but all of the highway segments need to be **assigned** to someone. But the same segment **cannot** be assigned to **more than one** of your friends.   

Write a program to **minimize** the **total length** of the highway segments built by the friend who builds the **longest** part.

## Input Format

The first line of the input has **2** integers **H** and **F** respectively, separated by a space. The number of highway segments and the number of friends.  
Each of the following **H** lines have a single integer, **H<sub>i</sub>** the length of the **i<sup>th</sup>** highway segment. There can be empty segments too. (Highway segments with 0 length)

## Output Format

Output just **one integer** representing your answer, the **total length of the highway** built by the friend who builds the longest part.

## Constraints

- **1 $$\leq$$ H $$\leq$$ 10<sup>6</sup>**
- **1 $$\leq$$ F $$\leq$$ 10<sup>3</sup>**
- **1 $$\leq$$ H<sub>i</sub> $$\leq$$ 10<sup>3</sup>**  

## Limits  
Time Limit: 1s  
Memory Limit: 256MB

### Sample Input 0

```
7 4
3
4
2
1
7
9
5
```

### Sample Output 0

```
9
```
