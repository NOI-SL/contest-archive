---
title: "Aimballs"
year: 2023
category: qualifier
round: "Selection Test"
sortkey: "1-qualifier-09"
index: 9
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - Screening Test 2023"
contest_slug: "noi-2023-selection-test"
contest_url: "https://www.hackerrank.com/contests/noi-2023-selection-test"
problem_slug: "aimballs"
problem_url: "https://www.hackerrank.com/contests/noi-2023-selection-test/challenges/aimballs"
---

Tenz, one of the most popular Valorant players, is preparing to participate in a shooting contest where $$N$$ balls will be given, and the objective is to pop as many balls as possible. However, there is a twist in this contest: each participant has information about where and when the ball will pop up. Now, the question is: What is the maximum number of balls that Tenz can pop off?  
NOTE 1: He can start from any point.  
NOTE 2: The time taken to move from $$X$$ to $$Y$$ = |$$X$$ - $$Y$$|.

## Input Format

The first line contains an integer $$N$$. Each of the next $$N$$ lines contain two space-separated integers $$X$$ and $$T$$ where $$X$$ denotes the point and $$T$$ denotes the time.

## Output Format

Print the maximum number of balls he can pop off.

## Constraints

$$0 \lt N \le 10 ^ 5$$  
$$0 \lt X_i\ ,\ T_j \le 10 ^ 5$$  
$$X_i \le X_(i + 1)$$  
$$T_i \le T_(i + 1)$$  
$$X_i \le T_i$$

### Sample Input 0

```
5
0 59
3 66
3 74
7 80
61 93
```

### Sample Output 0

```
4
```
