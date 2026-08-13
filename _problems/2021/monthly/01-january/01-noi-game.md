---
title: "NOI Game"
year: 2021
category: monthly
round: "January 2021"
sortkey: "2-monthly-01-01"
index: 1
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - January 2021"
contest_slug: "noi-2021-jan"
contest_url: "https://www.hackerrank.com/contests/noi-2021-jan"
problem_slug: "noi-game"
problem_url: "https://www.hackerrank.com/contests/noi-2021-jan/challenges/noi-game"
---

Mr. Ian is a past contestant of NOI and he has an interest in playing games with the letters ‘n’ ,o’ and ‘i’. Initially his friend Ms.Nio gives him a random string(text) which only contains the letters ‘n’, ‘o’ and ‘i’.
Then he performs the following operations on the string

1. Find an even substring that only contains one character type(‘n’/’o’/’i’)
2. Removes it from the original string to make a new string
3. Continue step 1 with the new string until there are no even substrings of same character type(‘n’/’o’/’i’) or the resulting string is empty


After all the operations Mr. Ian comes up with the resulting string. Having a programming background Mr. Ian wishes to make his task easy by using a program. 
Your task is to help Ian find the resulting string after following the above operations

## Input Format

One line containing a string of length N that has only lowercase characters ‘n’ ,’o’ and ‘i’

## Output Format

A single line containing the resulting string
If the resulting string is empty print **-1**

## Constraints

5 <= N <= 100 000

**Limits** 

- Time Limit: 1s 
- Memory Limit: 256MB

### Sample Input 0

```
nonooni
```

### Sample Output 0

```
noi
```

### Sample Input 1

```
noooiion
```

### Sample Output 1

```
-1
```

### Sample Input 2

```
nnooinnnnoinooiin
```

### Sample Output 2

```
ioi
```
