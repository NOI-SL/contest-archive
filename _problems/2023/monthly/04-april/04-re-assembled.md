---
title: "Re-Assembled"
year: 2023
category: monthly
round: "April 2023"
sortkey: "2-monthly-04-04"
index: 4
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - April 2023"
contest_slug: "noi-2023-apr"
contest_url: "https://www.hackerrank.com/contests/noi-2023-apr"
problem_slug: "re-assembled"
problem_url: "https://www.hackerrank.com/contests/noi-2023-apr/challenges/re-assembled"
---

You are given some strips containing stickers. each sticker has a number. You are allowed to "Re-assemble" a strip to 2 new strips as follows.

You can just keep the current strip or

- Calculate the `mid value` of the numbers in the strip, `mid value = (maximum value in the strip + minimum value in the strip) / 2`
- take the stickers with numbers lower than or equal to the `mid value` and put them in a new strip and put the stickers with values higher than the `mid value` in another new strip. The order of the stickers from the original stip should be preserved in the new strips.

You can then Re-assemble those new strips using the same steps if necessary.

For each strip, You are given a set of queries. The queries contains a number each and you have to find out whether it's possible to Re-assemble the given strip to obtain a strip so that the queried number is the sum of the numbers in the strip you obtain.(for each query, the answer should be derived from the original strip.)

If it's possible print `Yes`. Print `No` Otherwise.

## Input Format

one line containing $$t$$, the number of strips followed by $$t$$ occurences of,

- one line containing $$n$$ and $$q$$,
 - $$n$$ = number of stickers in the strip
 - $$q$$ = number of queries
- one line containing $$n$$ integers which are the values of the stickers in the strip.
- $$q$$ lines containing 1 integer each which are the queried numbers

## Output Format

$$q_1+q_2+q_3+...q_t$$ lines containing `Yes` or `No`

## Constraints

$$1 \le t,n,q \le 100000$$  
number values of stickers are all greater than 0 and less than 100000

### Sample Input 0

```
1
6 5
1 1 7 3 8 5
1
2
3
4
25
```

### Sample Output 0

```
No
Yes
Yes
No
Yes
```
