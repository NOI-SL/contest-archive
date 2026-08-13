---
title: "Knuckles Range"
year: 2021
category: monthly
round: "April 2021"
sortkey: "2-monthly-04-04"
index: 4
max_score: 100
difficulty: "Hard"
contest_name: "National Olympiad in Informatics Sri Lanka - April 2021"
contest_slug: "noi-2021-apr"
contest_url: "https://www.hackerrank.com/contests/noi-2021-apr"
problem_slug: "knuckles-range"
problem_url: "https://www.hackerrank.com/contests/noi-2021-apr/challenges/knuckles-range"
---

Knuckles is a mountain range located in the Central province of Sri Lanka. The Tourist Authority of Sri Lanka wants to create an adventures cable car track connecting peaks in the mountain. The authority wants to create a track connecting the maximum possible amount of mountain peaks. 

For simplicity assume that mountains are arranged along a straight line. As they want to create the most adventurous cable car track they can connect two mountain peaks only if their altitude difference is at least ***H***. They need to figure out the number of *maximum possible peaks* that can be used in order to get the budget allocated from the parliament. They asked for your help to calculate the maximum possible number of peaks that can be used. 

Note: A cable tract can be connected from ***j<sup>th</sup>*** mountain peak to ***i<sup>th</sup>*** mountain peak only if ***j*** &lt; ***i***.

## Input Format

- First line contains two integers ***N*** and ***H*** separated by spaces, where ***N*** is the number of mountain peaks.
- The next line contains ***N*** integers denoting the height ***h<sub>i</sub>*** of ***i<sup>th</sup>*** mountain peak.

## Output Format

A single integer denoting the maximum number of possible mountain peaks that can be selected.

## Constraints

1 $$\leq$$ ***N*** $$\leq$$ 10<sup>5</sup>

1 $$\leq$$ ***h<sub>i</sub>*** $$\leq$$ 10<sup>15</sup>

1 $$\leq$$ ***H*** $$\leq$$ 10<sup>9</sup>

### Sample Input 0

```
5 2
1 3 6 7 4
```

### Sample Output 0

```
4
```
