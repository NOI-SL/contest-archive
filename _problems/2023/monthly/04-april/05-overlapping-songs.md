---
title: "Overlapping Songs"
year: 2023
category: monthly
round: "April 2023"
sortkey: "2-monthly-04-05"
index: 5
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - April 2023"
contest_slug: "noi-2023-apr"
contest_url: "https://www.hackerrank.com/contests/noi-2023-apr"
problem_slug: "overlapping-songs"
problem_url: "https://www.hackerrank.com/contests/noi-2023-apr/challenges/overlapping-songs"
---

Aasha likes to listen to songs. One day while she was listening to songs, her brother came and challenged her as "I'll play some songs, some of them might overlap, some of them might be an advertisements.You have find the maximum possible times the songs have been played". She was already kinda bored, So she accepts the challenge. <p><b>She knows that:</b></p>   <ul><li>A song or an advertisement is a power of two / single bit integer.<br></li> <li>if its a song then, it must be played atleast for two minutes continuously, otherwise its considered as an advertisement.<br></li><li>Two same songs won't overlap and Advertisements might be same as a clip of a song, but two same advertisements won't overlap.<br></li><li>When two songs or advertisements overlap, it'll xor the value of both.<br></li></ul>
You're given an array $$A$$ of length $$N$$ denotes the songs played $$i^{th}$$ minute.
Can you help her to find the total number of times the songs have been played.

## Input Format

The first line contains an integer $$N$$.  The second line contains $$N$$ space-separated integers denoting the elements of array $$A$$.

## Output Format

Print the total number of times the songs have been played.

## Constraints

$$0 \lt N \le 100000$$  
$$1 \lt A_i \le 10 ^ {16}$$

### Sample Input 0

```
5
1 2 3 7 5
```

### Sample Output 0

```
7
```
