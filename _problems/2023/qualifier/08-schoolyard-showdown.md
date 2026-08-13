---
title: "Schoolyard Showdown"
year: 2023
category: qualifier
round: "Selection Test"
sortkey: "1-qualifier-08"
index: 8
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - Screening Test 2023"
contest_slug: "noi-2023-selection-test"
contest_url: "https://www.hackerrank.com/contests/noi-2023-selection-test"
problem_slug: "schoolyard-showdown"
problem_url: "https://www.hackerrank.com/contests/noi-2023-selection-test/challenges/schoolyard-showdown"
---

In a sprawling schoolyard, students of two different types, A and B, are scattered across a row of size $$n$$. The schoolyard is represented as a string, where each character corresponds to a student's type.

The types of students are denoted as follows:

- Type A students are represented by the character 'A'.
- Type B students are represented by the character 'B'.

You are given a series of queries to manipulate and analyze the student distribution in the schoolyard. There are two types of queries you need to implement:

1. Toggle Query:
Syntax: `1 x y`
    
    This query allows you to toggle the type of each student within a given range [x, y] (inclusive). Specifically, all students in the range will switch their type from A to B or from B to A.
    
    Note that toggling means that if a student is initially of type A, it becomes type B, and vice versa.
    
2. Count Query:
Syntax: `2 x y`
    
    This query requires you to determine if the number of students of type B  within a given range [x, y]  (inclusive), is odd or even. You need to output either "ODD" or "EVEN" accordingly.
    
    Note: Assume the string is 1-indexed
    

You need to implement a program that can process a sequence of these queries efficiently.

## Input Format

- The first line contains an integer, $$n$$, representing the size of the schoolyard row ($$1 ≤ n ≤ 10^6$$).
- The following line contain n characters, representing the initial distribution of students in the schoolyard. Each character is either 'A' or 'B'.
- Next line contains a single integer $$q$$ ($$1 ≤ q ≤ 10^5$$)
- Next $$q$$ lines containes queries of either type

## Output Format

For each count query (type 2), output either "ODD" or "EVEN" on a new line.

## Constraints

### Subtask 1 - 20 pts

$$1 ≤ n ≤ 1000$$

$$1 ≤ q ≤ 100$$

### Subtask 2 - 30 pts

All queries are of type 2. (Count queries)

### Subtask 3 - 50 pts

No other constraints

### Sample Input 0

```
6
AAAAAA
4
1 1 3
1 2 4
2 1 3
2 1 4
```

### Sample Output 0

```
ODD
EVEN
```
