---
title: "Minimal Cost "
year: 2021
category: monthly
round: "April 2021"
sortkey: "2-monthly-04-03"
index: 3
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - April 2021"
contest_slug: "noi-2021-apr"
contest_url: "https://www.hackerrank.com/contests/noi-2021-apr"
problem_slug: "minimal-cost-1"
problem_url: "https://www.hackerrank.com/contests/noi-2021-apr/challenges/minimal-cost-1"
---

You are given a set of cities( numbered from ***1*** to ***N*** )  that are connected with directed roads. Each city has a value assigned to it. Your task is to find a path such that minimizes the  [Great Common Devisor](https://en.wikipedia.org/wiki/Greatest_common_divisor) in the values of the cities on the path and output that minimum GCD value. 

There can be a path that contains only one city.

## Input Format

- The first line contains two integer ***N*** and ***M***, number of cities and number of roads.
- Next line contains space seperated ***N*** integers represendting the value of the ***i<sup>th</sup>*** (***V<sub>i</sub>***) city.
- Each of the next ***M*** lines contain two integers ***S*** and ***E***, denoting a directed road from city ***S*** to city ***E***.

## Output Format

Print the minimum GCD value you found.

## Constraints

- 1 $$\leq$$ ***N*** $$\leq$$ 10<sup>5</sup> 
- 1 $$\leq$$ ***M*** $$\leq$$ 10<sup>5</sup>  
- 1 $$\leq$$ ***V<sub>i</sub>*** $$\leq$$ 10<sup>5</sup>

### Sample Input 0

```
3 2
4 6 8
1 2
2 3
```

### Sample Output 0

```
2
```
