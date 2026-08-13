---
title: "central-scroll"
year: 2024
category: finals
round: "Final Round — Day 2"
sortkey: "3-finals-2-01"
index: 1
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka 2024 - Day 2"
contest_slug: "noi-2024-day-2"
contest_url: "https://www.hackerrank.com/contests/noi-2024-day-2"
problem_slug: "central-scroll"
problem_url: "https://www.hackerrank.com/contests/noi-2024-day-2/challenges/central-scroll"
---

In the historic kingdom of Numeria lies the famous Grand Library, a treasure trove of ancient scrolls kept in $$n$$ special cases, each labeled from $$T_0$$ to $$T_{n-1}$$. These scrolls are unique as each contains a numeric value representing the importance of a specific historical event, and the scrolls within each case are meticulously sorted by these importance values.

Scholars frequent this library, eager to analyze historical trends by comparing events between any two selected cases. The head librarian, aiming to facilitate these scholarly investigations, seeks to automate the process of finding the central event importance when two cases are chosen for comparison.

Here’s your challenge: Given the $$n$$ cases of scrolls, you will process $$Q$$ queries from visiting scholars. Each query specifies two indices $$i$$ and $$j$$ $$(0 \leq i, j \leq n-1)$$, which correspond to the cases they have selected. 

Your task is to quickly determine the importance of the event at the midpoint after combining the scrolls from cases $$T_i$$ and $$T_j$$ and sorting the combined case by importance values. It is guaranteed that the total number of scrolls in any pair of selected cases is always odd.

Can you devise a system that accurately and efficiently computes the central importance of the historical events, aiding the scholars in their pursuit of knowledge?

## Input Format

- Line 1: Two space separated integers $$n$$, and $$Q$$. $$i^\text{th}$$ line in next $$n$$ lines:
  - An integer $$S_i$$ representing the number of events in $$T_i$$
  - $$S_i$$ integers representing the importance of events in $$T_i$$
- Next $$Q$$ lines:
  - Two integers $$i$$ and $$j$$

## Output Format

- For each query, output a single integer representing the central importance of combined cases.

## Constraints

- $$1 \leq n \leq 10^3$$
- $$1 \leq q \leq 10^4$$
- $$\Sigma s_i \leq 10^7$$.
- $$\text {All importance values are } \leq 10^9$$.

### Subtask - 40 pts
- $$1 \leq n \leq 10^2$$
- $$1 \leq q \leq 3*10^2$$

### Limits
- Memory - 256MB
- Time - 4 seconds

### Sample Input 0

```
3 2
3 1 3 8
4 2 7 10 15
3 4 6 9
0 1
1 2
```

### Sample Output 0

```
7
7
```
