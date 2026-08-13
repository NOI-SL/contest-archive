---
title: "String Transformation Cost"
year: 2023
category: finals
round: "Final Round — Day 1"
sortkey: "3-finals-1-02"
index: 2
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka 2023 - Day 1"
contest_slug: "noi-2023-day-1"
contest_url: "https://www.hackerrank.com/contests/noi-2023-day-1"
problem_slug: "string-transformation-cost"
problem_url: "https://www.hackerrank.com/contests/noi-2023-day-1/challenges/string-transformation-cost"
---

In a land of linguistic puzzles, you encounter a challenging problem involving string transformations. You are given two strings, a string $$a$$ of length $$n$$ and string $$b$$ of length $$m$$ consisting of lowercase English characters. 

Your goal is to modify string $$a$$ with the minimum cost to ensure that it becomes impossible to obtain string $$b$$ by deleting some characters from $$a$$.
To achieve this, you have two options for each character in string a:

- Replace the character with another character.
- Remove the character entirely.

Every character removal has a specific cost associated with it, represented by the array $$p$$ of length $$n$$, where $$p_i$$ denotes the cost of removing the $$i^{th}$$ character from string $$a$$.

Additionally, replacing a character with another character has its own cost, represented by a matrix $$q$$ of dimensions $$n * 26$$. Each row in the matrix corresponds to a character in string a, and each column represents a lowercase English character. The value `q[i][c]` denotes the cost of replacing the $$i^{th}$$ character in string $$a$$ with the $$c^{th}$$ character of the alphabet.

Your task is to determine the minimum cost required to transform string $$a$$ such that string $$b$$ cannot be obtained by deleting some characters from $$a$$.

Time Limit:
2 seconds

Memory Limit:
512 MB

## Input Format

- The first line contains two integers $$n$$ and $$m$$, representing the lengths of strings $$a$$ and $$b$$, respectively.
- The second line contains string $$a$$ of length $$n$$.
- The third line contains string $$b$$ of length $$m$$.
- The fourth line contains $$n$$ space-separated integers, representing the removal costs `p[i]` for each character in string $$a$$.
- The following $$n$$ lines each contain $$26$$ space-separated integers, representing the replacement costs `q[i][c]` for each character in string $$a$$ and each possible replacement character $$c$$.

## Output Format

Print a single integer, denoting the minimum cost required to transform string $$a$$ such that string $$b$$ cannot be obtained by deleting some characters from $$a$$.

## Constraints

- $$1 <= n <= 10^4$$
- $$1 <= m <= 10$$
- $$1 <= m <= n$$
- $$1 <= p_i  <= 10^9$$
- $$1 <= q_{i,c} <= 10^9$$

### Sample Input 0

```
4 1
winq
n
18 44 1 82 
100 79 81 59 95 87 78 41 94 12 97 57 23 55 52 57 67 90 95 37 89 46 21 94 15 35 
83 22 65 82 79 42 68 40 53 50 11 94 20 51 15 92 48 86 49 97 40 98 33 18 19 92 
47 82 56 95 26 60 87 20 49 87 92 16 40 31 13 22 25 13 94 22 27 22 83 99 55 74 
28 84 60 14 55 56 81 44 69 79 96 11 53 53 32 33 74 61 94 96 75 58 70 94 36 83 
```

### Sample Output 0

```
1
```
