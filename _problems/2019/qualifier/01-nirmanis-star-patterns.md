---
title: "Nirmani's Star Patterns"
year: 2019
category: qualifier
round: "Selection Test"
sortkey: "1-qualifier-01"
index: 1
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - Screening Test"
contest_slug: "noi-2019-selection-test"
contest_url: "https://www.hackerrank.com/contests/noi-2019-selection-test"
problem_slug: "nirmanis-star-patterns"
problem_url: "https://www.hackerrank.com/contests/noi-2019-selection-test/challenges/nirmanis-star-patterns"
---

Nirmani loves finding star patterns in the night sky. She started playing a game where on each night, she has to find a star pattern in the shape of a right-angled triangle. There has to be an equal number of stars in the two adjacent sides of the right angle.

On the first night ***(N=1)***, the goal is to find the star pattern with just one star.
That is, 
```
*
```

On the second night ***(N=2)***,
```
*
**
```

On the third night ***(N=3)***,
```
*
**
***
```

On the 4th night ***(N=4)***,
```
*
**
***
****
```

And so on...

She requested you to help her out by building a program that prints the star pattern she should find on the **N<sup>th</sup>** night.

## Input Format

A single integer **N**, indicating the **N<sup>th</sup>** night.

## Output Format

A star pattern in the shape of a right-angled triangle aligned to the left, with **N** rows, where the last row contains **N** stars.
You must not include any spaces between stars in the same row.

## Constraints

- **1 $$\leq$$ N $$\leq$$ 1000**

### Sample Input 0

```
4
```

### Sample Output 0

```
*
**
***
****
```

### Sample Input 1

```
7
```

### Sample Output 1

```
*
**
***
****
*****
******
*******
```
