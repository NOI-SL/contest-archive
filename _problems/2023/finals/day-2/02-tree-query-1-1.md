---
title: "Tree Query - 1"
year: 2023
category: finals
round: "Final Round — Day 2"
sortkey: "3-finals-2-02"
index: 2
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka 2023 - Day 2"
contest_slug: "noi-2023-day-2"
contest_url: "https://www.hackerrank.com/contests/noi-2023-day-2"
problem_slug: "tree-query-1-1"
problem_url: "https://www.hackerrank.com/contests/noi-2023-day-2/challenges/tree-query-1-1"
---

There is a country consisting of $$N$$ cities with values $$A_i$$, and $$N-1$$ bidirectional roads connecting them, such that we can travel between any two cities using these roads. In other words, these cities and roads form a tree. Arya is currently on vacation and plans to visit either city $$U$$ or city $$V$$. He wants to choose some starting points on the shortest path between $$U$$ and $$V$$ so that he can visit at least one of the cities, $$U$$ or $$V$$, without passing through a city with a value less than $$K$$. This means he must not stay or pass through a city that has a value less than $$K$$. Your task is to help him choose the possible starting points.

## Input Format

The first line contains an integer $$N$$ denotes the number of cities. The second line contains $$N$$ space-separated integers denoting the values of cities($$A$$). The next $$N - 1$$ line contains $$2$$ space-separated integers denoting the connection between cities. The fourth line contains $$Q$$. Each of the next $$Q$$ lines contain three space-separated integers $$U$$, $$V$$ and $$K$$.

## Output Format

For each query, print the count of possible cities.

## Constraints

$$2 \lt N \le 10 ^ 5$$    
$$0 \lt Q \le 10 ^ 5$$  
$$0 \lt A_i\ ,\ K \le 10 ^ 9$$  
Time Limit: $$2$$ sec  
Memory Limit :$$512$$ MB

### Sample Input 0

```
9
11 7 2 5 9 11 10 8 6
0 1
1 2
2 7
7 8
1 3
0 4
4 5
5 6
1
8 6 6
```

### Sample Output 0

```
5
```
