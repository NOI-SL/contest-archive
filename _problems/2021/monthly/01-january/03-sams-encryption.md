---
title: "Sam’s Encryption"
year: 2021
category: monthly
round: "January 2021"
sortkey: "2-monthly-01-03"
index: 3
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - January 2021"
contest_slug: "noi-2021-jan"
contest_url: "https://www.hackerrank.com/contests/noi-2021-jan"
problem_slug: "sams-encryption"
problem_url: "https://www.hackerrank.com/contests/noi-2021-jan/challenges/sams-encryption"
---

Alice and Bob are best friends and they did their coursework together sharing Bob’s computer. But Sam who is an enemy of Bob recently got access to Bob’s computer and encrypted their coursework using Sam’s own encryption algorithm. Alice and Bob have no clue about the encryption algorithm. So the only possibility is to help Sam with his coursework and get the secret that Sam used to encrypt their file. As Sam is not good at remembering things he stored the password hidden in a big string **s**. So Alice and Bob want to get the secret from that big string instead helping Sam. Alice and Bob did some research about the technique that Sam uses to hide secrets among strings. They need your help to find the possible starting locations of the secret. 
You are given the big string **s** and a list of **n** keywords of equal length. The secret is a concatenation of a permutation of the list of keywords. Alice and Bob want you to give them a list of indexes of the starting position of possible secrets.
Big string **s** and all keywords are consist of only lower case English alphabetical characters.

## Input Format

First-line will be the big string **s**
The next line will be the integer **n**, the number of keywords.
The next **n** lines will contain a keyword in each line.

## Output Format

Print each index of the index list in separate lines. Indexes should be print in ascending order. 
If there are no possible indexes then print -1.

## Constraints

10 <= length of s <= 10 000

1 <= n <= 2000

1 <=  length of a keyword <= 25


**Limits** 

- Time Limit: 1s 
- Memory Limit: 256MB

### Sample Input 0

```
satpipcabpipsat
3
pip
cab
sat
```

### Sample Output 0

```
0
6
```

### Sample Input 1

```
batteamanbatzxsbatzxidmanbatteat
3
man
tea
bat
```

### Sample Output 1

```
0
3
22
```
