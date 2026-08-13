---
title: "Hide And Seek"
year: 2023
category: monthly
round: "February 2023"
sortkey: "2-monthly-02-01"
index: 1
max_score: 100
difficulty: "Easy"
contest_name: "National Olympiad in Informatics Sri Lanka - February 2023"
contest_slug: "noi-2023-feb"
contest_url: "https://www.hackerrank.com/contests/noi-2023-feb"
problem_slug: "hide-and-seek-4"
problem_url: "https://www.hackerrank.com/contests/noi-2023-feb/challenges/hide-and-seek-4"
---

A group of friends$$(F_{1..n})$$ are about to play hide and seek. First they need to decide who will seek first. So they stand in a circle and starts counting clockwise while singing a counting rhyme. When the rhyme ends, the friend that is counted on the last word is safe(see sample testcase).

When the counting ends and a friend is safe, he/she goes out of the scircle and the remaining friends start counting again. If the friend that started counting in the previous round is still in the circle, that friend will start the counting in the next round as well. Otherwise the friend that was counted after the first friend will start.

This counting is repeated until only one friend is remaining on the circle and that friend will have to seek.

You are given the names of the friends and the rhyme they sing. Find out who has to seek.

## Input Format

one line containing $$t$$ : the number of testcases  
followed by $$t$$ occurences of,  
- $$n$$ number of Friends in the testcase  
- $$n$$ lines with each friend's name  
- One Line with the words of the counting rhyme.

## Output Format

$$t$$ lines containing the name of the last friend remaining

## Constraints

$$10 \le t,n \le 10^3$$

$$2 \le$$number of words in the rhyme $$\le 4000$$

Words in the rhyme are sepereated by spaces.

### Sample Input 0

```
1
5
John
Jane
Juan
Jean
June
Eeny meeny miny moe Catch a tiger by the toe
```

### Sample Output 0

```
Juan
```
