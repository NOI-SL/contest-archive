---
title: "COVID-21 Variant"
year: 2021
category: monthly
round: "April 2021"
sortkey: "2-monthly-04-01"
index: 1
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - April 2021"
contest_slug: "noi-2021-apr"
contest_url: "https://www.hackerrank.com/contests/noi-2021-apr"
problem_slug: "covid-21-variant"
problem_url: "https://www.hackerrank.com/contests/noi-2021-apr/challenges/covid-21-variant"
---

COVID-19 virus has mutated again. The new variant seems to posses novel behavior.


1. Spreading
- COVID-19 spreads from person to person in the same way.
- COVID-21 spread is dependent on the age.
2. Distance (all values are given in meters)
- COVID-19 can jump $$D_1$$ from any person to another person.
- COVID-21 can jump $$D_2$$ from/to an older person or $$D_3$$ from a younger person. 
$$D_2 \geq D_3$$
This is because the older people are weak so they can catch the virus FROM a further person and their immunity systems cannot fight the virus so it will spread TO far away people. 
3. Total spread
- COVID-19 can spread for as long as there are people to spread to.
- COVID-21 can spread only up to $$D_4$$ jump length between people.

Consider a situation where people are inside a room. The surveillance system is monitoring the human interactions and records all the close contacts where a disease spread is possible. Unfortunately, the time stamps of these records are lost.

Given these records, can you find if there is at least one person who if sick will spread the disease to the entire room?

## Input Format

The first line contains the number of testcases $$T$$.

The second line contains four integers, $$D_1, D_2, D_3, D_4$$.

The third line contains two integers $$P$$ (the number of people) and $$N$$ (the number of interactions).

Next $$P$$ lines contains a string $$A_i$$ denoting the age of the person ($$OLD$$ or $$YOUNG$$). 

Next $$N$$ lines contains three integer and a string $$p_{j0}$$, $$p_{j1}$$ (the two people interacting) and $$D_j$$ (the distance between the people during the interaction).

## Output Format

Print $$T$$ lines, one lines for each testcase.

The line should contain $$YES$$ or $$NO$$ twice denoting 
1. Whether COVID-19 will spread to the whole room.
2. Whetehr COVID-21 will spread to the whole room.

## Constraints

$0 < T \geq 20 $

$0 < N \geq 25000 $

$0 < P \geq 100100 $

$$0 < D_1,D_2,D_3 \geq 100$$

$$0 < D_4 \geq 10e7$$

$0 < D_j \geq 250 $

### Sample Input 0

```
4
5 5 2 10
4 4
YOUNG
YOUNG
OLD
YOUNG
0 1 2
0 2 2
0 3 5
2 3 5
2 5 2 10
4 4
YOUNG
YOUNG
OLD
YOUNG
0 1 2
0 2 2
0 3 5
2 3 5
5 5 2 10
4 4
YOUNG
YOUNG
YOUNG
YOUNG
0 1 2
0 2 2
0 3 5
2 3 5
5 5 2 8
4 4
YOUNG
YOUNG
OLD
YOUNG
0 1 2
0 2 2
0 3 5
2 3 5
```

### Sample Output 0

```
YES YES
NO YES
YES NO
YES NO
```
