---
title: "Prisoners and Enemies"
year: 2020
category: monthly
round: "July 2020"
sortkey: "2-monthly-07-02"
index: 2
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - July 2020"
contest_slug: "noi-2020-jul"
contest_url: "https://www.hackerrank.com/contests/noi-2020-jul"
problem_slug: "prisoners-and-enemies"
problem_url: "https://www.hackerrank.com/contests/noi-2020-jul/challenges/prisoners-and-enemies"
---

The warden of Fox River needs to assign some of its prisoners for an outdoor activity. But as prisoners are cunning and always try to escape he wants to minimize the chance of an escape. With his experience, the warden knows that every prisoner has exactly one serious enemy, and that prisoner will never help his serious enemy to escape out. Knowing this fact the warden wants to make the biggest circle by selecting a set of prisoners such that for each prisoner in the circle has his serious enemy is either in his left or right. Thus no prisoners can make an escape attempt without getting his serous enemy’s attention. As warden is busy with prison work he asked your help.

## Input Format

- First-line will have an integer ***T*** for the number of test cases.
- Next lines will have ***T*** test cases. Each test case has two lines. First-line will have the number of prisoners ***N***.
- The next line of that test case will have ***N*** integers. ith integer denotes the enemy of ith prisoner. ( counting ***i*** starts from ***1*** and goes to ***N***).

## Output Format

***T*** lines denoting the maximum number of the prisoners that can be put into the circle for each test case.

## Constraints

- **1 $$\leq$$ T $$\leq$$ 10<sup>2</sup>**  
- **1 $$\leq$$ N $$\leq$$ 10<sup>3</sup>**  
   
#### **Limits**
- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
3
5
2 3 4 5 1
5
2 3 4 1 1
9
2 3 6 3 4 5 5 5 7
```

### Sample Output 0

```
5
4
4
```
