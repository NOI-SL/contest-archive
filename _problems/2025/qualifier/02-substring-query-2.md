---
title: "Substring query 2"
year: 2025
category: qualifier
round: "Qualifier Round"
sortkey: "1-qualifier-02"
index: 2
max_score: 100
difficulty: "Medium"
contest_name: "NOI 2025 Qualifier Round"
contest_slug: "noi-2025-qualifier-round"
contest_url: "https://www.hackerrank.com/contests/noi-2025-qualifier-round"
problem_slug: "substring-query-2"
problem_url: "https://www.hackerrank.com/contests/noi-2025-qualifier-round/challenges/substring-query-2"
---

You are given a string S of length N, consisting of lowercase English alphabets. You are required to process Q queries.

Each query is of the form (a, b), where a and b are lowercase English characters. For each query, you must print the number of substrings of S where:

the first character of the substring is a, and

the last character of the substring is b

Note:
A substring is any continuous segment of the original string, obtained by removing a (possibly empty) prefix and suffix.

Two substrings are considered different if the pair of indices (start, end) is different.

## Input Format

The first line contains the string S
.
The second line contains the integer Q
, the number of queries.
Each of the next 
 lines contains two characters 
 a and b
, separated by a space.

## Output Format

For each query, output the number of substrings

## Constraints

1≤∣S∣≤10^5
 

1
≤
𝑄
≤
10 ^ 5
 

String 
𝑆 contains only lowercase English letters ('a' to 'z')

Each query contains two lowercase English letters 
𝑎
 and 
𝑏

### Sample Input 0

```
abacaba
2
a b
b b
```

### Sample Output 0

```
4
3
```
