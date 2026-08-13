---
title: "Number Triangles"
year: 2022
category: monthly
round: "February 2022"
sortkey: "2-monthly-02-04"
index: 4
max_score: 100
difficulty: "Easy"
contest_name: "National Olympiad in Informatics Sri Lanka - February 2022"
contest_slug: "noi-2022-feb"
contest_url: "https://www.hackerrank.com/contests/noi-2022-feb"
problem_slug: "noi-number-triangles"
problem_url: "https://www.hackerrank.com/contests/noi-2022-feb/challenges/noi-number-triangles"
---

Chathura loves to create number patterns. Recently he started creating a number pattern which he calls a number traingle. A number triangle of a size of ***N*** is a list of numbers which are in the shape of a right-angled triangle and has ***N*** lines. In the ***i<sup>th</sup>*** line, there should be numbers from ***1*** to ***i***.  

For example if the size is ***1***, ***(N=1)***, the pattern should only have ***1*** in it.
That is, 
```
1
```

If the size is ***2***, ***(N=2)***,
```
1
1 2
```

If the size is ***3***, ***(N=3)***,
```
1
1 2
1 2 3
```

If the size is ***4***, ***(N=4)***,
```
1
1 2
1 2 3
1 2 3 4
```

And so on...

Chathura has asked you to help him by building a program that prints a number triangle of a given size.

## Input Format

A single integer **N**, indicating the size of the number triangle.

## Output Format

A number triangle in the shape of a right-angled triangle aligned to the left, with **N** rows, where the last row contains **N** numbers.
You must include a space between each number in the row.

## Constraints

- **1 $$\leq$$ N $$\leq$$ 1000**

### Sample Input 0

```
4
```

### Sample Output 0

```
1
1 2
1 2 3
1 2 3 4
```

### Sample Input 1

```
7
```

### Sample Output 1

```
1
1 2
1 2 3
1 2 3 4
1 2 3 4 5
1 2 3 4 5 6
1 2 3 4 5 6 7
```
