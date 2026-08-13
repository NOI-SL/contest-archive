---
title: "Triotopia"
year: 2024
category: monthly
round: "March 2024"
sortkey: "2-monthly-03-01"
index: 1
max_score: 100
difficulty: "Medium"
contest_name: "NOI 2024 March Monthly Contest"
contest_slug: "noi-2024-march"
contest_url: "https://www.hackerrank.com/contests/noi-2024-march"
problem_slug: "triotopia"
problem_url: "https://www.hackerrank.com/contests/noi-2024-march/challenges/triotopia"
---

You are a government analyst in Triotopia, a country with infinitely many triangular cities arranged as a triangular grid. You usually have nothing much to do - but not anymore! A new virus has emerged and is spreading rapidly, and you are tasked with modelling the spread of the virus.

On Day 0 no cities are infected, but the virus emerges from an intersection point somewhere in the grid on this day. During every subsequent day, any city that shares a corner with an infected point also becomes infected.

<img src="https://i.imgur.com/sTplVu5.gif">

You have to answer $$q$$ questions about the spread of the virus. In each question, you are given an integer $$n$$, and you have to find the number of cities that get **newly** infected on Day $$n$$.

## Input Format

The first line contains $$q$$, the number of questions.  
Each of the next $$q$$ lines contain a positive integer $$n$$.

## Output Format

The output should have $$q$$ lines, with the answers to the questions in input order.

## Constraints

$$0 \leq q \leq 10^6$$  
$$0 \leq n \leq 10^{16}$$

**Subtask 1 (60 points)**: $$0 \leq n \leq 10^{7}$$  
**Subtask 2 (40 points)**: No further constraints.

### Sample Input 0

```
3
1
2
4
```

### Sample Output 0

```
6
18
42
```
