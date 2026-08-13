---
title: "Doctor Strange’s Student"
year: 2021
category: qualifier
round: "Selection Test"
sortkey: "1-qualifier-04"
index: 4
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - Screening Test 2021"
contest_slug: "noi-2021-selection-test"
contest_url: "https://www.hackerrank.com/contests/noi-2021-selection-test"
problem_slug: "doctor-stranges-student"
problem_url: "https://www.hackerrank.com/contests/noi-2021-selection-test/challenges/doctor-stranges-student"
---

You are a student of Doctor Strange and he is training you to calculate possibilities. To determine your ability to count possibilities he is giving you this task.

You are given ***n*** number of cards and each card has a number ***k(0$$\leq$$k$$\leq$$9)*** written on it.

Magic number is a number which has ***11*** digits and it always starts with digit ***‘8’***. Using numbers on those cards you have to make as many magic numbers as possible. Each card must be used in at most one magic number, and you do not have to use all cards. The magic numbers do not necessarily have to be distinct. 

Your task is to find the total number of magic numbers you can make.

## Input Format

- The first line contains an integer ***n*** - the number of cards. 
- The second line contains a string of ***n*** digits, each digit represents a card and the number written on it.

## Output Format

If at least one magic number can be made from these cards, output the maximum number of magic numbers that can be made. Otherwise, output 0.

## Constraints

- 1 $$\leq$$ ***t*** $$\leq$$ 100
- 0 $$\leq$$ ***k*** $$\leq$$ 9

### Sample Input 0

```
11
00000000008
```

### Sample Output 0

```
1
```

### Sample Input 1

```
22
0011223344556677889988
```

### Sample Output 1

```
2
```

### Sample Input 2

```
11
31415926535
```

### Sample Output 2

```
0
```
