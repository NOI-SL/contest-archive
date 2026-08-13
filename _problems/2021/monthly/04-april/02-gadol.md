---
title: "Gadol"
year: 2021
category: monthly
round: "April 2021"
sortkey: "2-monthly-04-02"
index: 2
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - April 2021"
contest_slug: "noi-2021-apr"
contest_url: "https://www.hackerrank.com/contests/noi-2021-apr"
problem_slug: "gadol"
problem_url: "https://www.hackerrank.com/contests/noi-2021-apr/challenges/gadol"
---

You are planning to renovate a broken wall made with bricks. The wall has ***N*** columns for you to lay bricks. 

Some of the columns already have a number of old bricks remaining. Weirdly, you have a strange sense of art and decided to fill-in the ***N*** columns in a way that it follows the following rules:

1. At most ***K*** new bricks can be laid in each column, one on top of the other contiguously
2. Consecutive columns should have at least a single newly laid brick in each column, sharing a common side.
3. New bricks laid out in the first and last columns should touch the ground/ an old brick.
4. You may leave a space of maximum height ***K-1*** in each column between the new bricks and the old bricks (or the ground in case no old bricks are there), for ventilation

Given ***N***, ***K***, and an array **A** of length ***N*** containing the number of old bricks present in each column, print whether it is possible to lay out the new bricks following the specified rules.

## Input Format

The first line contains a single integer ***T*** the number of test cases.
The first line of each test case contains two integers ***N***, and ***K*** separated by a space.
Second line of each test case contains a list of ***N*** integers, corresponding to the array **A**, separated by spaces.

## Output Format

Print “YES” if it’s possible to lay out the bricks following the rules. “NO” if it is impossible.

## Constraints

- 1 $$\leq$$ ***T*** $$\leq$$ 10<sup>4</sup> 
- 2 $$\leq$$ ***N*** $$\leq$$ 2x10<sup>5</sup> 
- 2 $$\leq$$ ***K*** $$\leq$$ 10<sup>8</sup> 
- 0 $$\leq$$ ***A<sub>i</sub>*** $$\leq$$ 10<sup>8</sup>

### Sample Input 0

```
3
6 3
0 0 2 5 1 1
2 3
0 2
3 2
3 0 2
```

### Sample Output 0

```
YES
YES
NO
```
