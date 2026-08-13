---
title: "Simon the Giant"
year: 2022
category: monthly
round: "April 2022"
sortkey: "2-monthly-04-04"
index: 4
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - April 2022"
contest_slug: "noi-2022-apr"
contest_url: "https://www.hackerrank.com/contests/noi-2022-apr"
problem_slug: "simon-the-giant"
problem_url: "https://www.hackerrank.com/contests/noi-2022-apr/challenges/simon-the-giant"
---

Simon is a construction worker Giant who is interested in making patterns of everything he sees, no matter how pointless they are. Simon, being irritated by the way humans have constructed a **series of buildings** in his homeworld, decides to use his Giant magic to alter them in his own way by **adding to** or **taking away** stories from the buildings such that every building has an **equal or greater** amount of stories than the one **before** it.
(Note that it may exist buildings with 0 stories)

Using his Giant magic **once** which consumes **1 credit**, Simon can alter a building by either **adding or removing a single story**.


What is the **minimum** amount of credits that Simon should consume to attain his desired pattern of buildings?

## Input Format

- The first line contains a single integer ***N*** denoting the number of buildings.
- Second line contains ***N*** number of space separated integers, denoting the heights (***h<sub>i</sub>***) of buildings.

## Output Format

-  Print the **minimum amount of credits** Simon should consume.

## Constraints

- 1 $$\leq$$ ***T*** $$\leq$$ 5000
- 0 $$\leq$$ ***h<sub>i</sub>*** $$\leq$$ 10<sup>9</sup>

### Sample Input 0

```
5
3 2 1 2 11
```

### Sample Output 0

```
2
```

### Sample Input 1

```
2
10 2
```

### Sample Output 1

```
8
```
