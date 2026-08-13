---
title: "JUMANJI - The snake and ladder version"
year: 2023
category: monthly
round: "February 2023"
sortkey: "2-monthly-02-02"
index: 2
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - February 2023"
contest_slug: "noi-2023-feb"
contest_url: "https://www.hackerrank.com/contests/noi-2023-feb"
problem_slug: "jumanji-the-snake-and-ladder-version"
problem_url: "https://www.hackerrank.com/contests/noi-2023-feb/challenges/jumanji-the-snake-and-ladder-version"
---

After Jumanji - The next level all the main characters has returned to their normal life but Milo  had admitted to his close friend, Eddie, that he was dealing with an illness, so he chose to stay in the game in the form of a flying horse. But after sometime Smoldor and his friends decided to check on Milo so they decided to play jumanji one more time. But unfortunately this time they landed in a snake and ladders version of jumanji. In this extraordinary snake and ladders board there are **snakes**, **ladders** and **broken indexes** (where you cannot set your foot on).
The dark Lord who created this mysterios game decides the maximun **M** value the dice can show. Unlike an ordinary dice, this dice can throw any number between **1 to M** .
You are given the index **N** and locations of ladders , snakes , cursed indexes and the maximum value dice can give (**M**) . Your task is to find minimum number of dice throws that are needed to reach the index **N** . 
You cannot land on a cursed index no matter what.

## Input Format

1.First line contains the five integers **N**,**L**,**S**,**B**,**M**

2.Second line contains **L** no of interger pairs (x,y) such that x denotes the start of the ladder  and y denotes the end index of the ladder which starts at x.

3.Third line contains **S** no of interger pairs (x,y) such that x denotes the start of the snakes mouth and y denotes the index where you land once you get bitten by the snake.

4.fourth line contains **B** no of intergers denoting the cursed indexes

**N - end index**

**L- no of Ladder**

**S-no of snakes**

**C-no of cursed indexes**

**M-maximum dice value**

## Output Format

output a single integer denoting the **minimum no of dice throws** required to reach the end block N

## Constraints

**1 <= N,M <=500**

starting and ending indexes cannot be cursed.

Theres always a way to finish the game.

If Dr Smoldor jumps  on a ladder or a snake he must be moved accordingly ( he cannot stay on a ladder without climbing nor he cannor stay on a snake block without getting eaten).

Dr Smoldor cannot land on a cursed index under any circumstance

### Sample Input 0

```
36 5 5 3 2
2 15 5 7 9 27 18 29 25 35
17 4 20 6 24 16 32 30 34 12
2 7 9
```

### Sample Output 0

```
13
```
