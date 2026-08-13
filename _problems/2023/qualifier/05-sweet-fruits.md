---
title: "Sweet Fruits"
year: 2023
category: qualifier
round: "Selection Test"
sortkey: "1-qualifier-05"
index: 5
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - Screening Test 2023"
contest_slug: "noi-2023-selection-test"
contest_url: "https://www.hackerrank.com/contests/noi-2023-selection-test"
problem_slug: "sweet-fruits"
problem_url: "https://www.hackerrank.com/contests/noi-2023-selection-test/challenges/sweet-fruits"
---

Azusa brought 𝑛 different types of exotic fruits to the Fruit Lovers Club. They are numbered from 1 to 𝑛, where the 𝑖-th fruit has a sweetness level described by an integer 𝑎𝑖.

Mio loves trying new fruits, but for health reasons, she can taste at most 𝑚 fruits each day.

Days are 1-indexed (numbered 1,2,3,…). Tasting the fruit 𝑖 on the 𝑑-th day will cause a sweetness penalty of (𝑑⋅𝑎𝑖), as fruits become sweeter with time. Each fruit can be tasted at most once.

The total sweetness penalty will be the sum of the individual penalties of each fruit tasted.

Suppose that Mio chooses exactly 𝑘 fruits and tastes them in any order she wants. What is the minimum total sweetness penalty she can get?

Since Mio is an adventurous fruit enthusiast, she wants you to answer this question for every value of 𝑘 between 1 and 𝑛.

## Input Format

The first line contains two integers 𝑛 and 𝑚.

The second line contains 𝑛 integers 𝑎1,𝑎2,…,𝑎𝑛.

## Output Format

You have to output 𝑛 integers 𝑥1,𝑥2,…,𝑥𝑛 on a single line, separed by spaces, where 𝑥𝑘 is the minimum total sugar penalty Mio can get if she eats exactly 𝑘 fruits.

## Constraints

(1≤𝑚≤𝑛≤200 000)

(1≤𝑎𝑖≤200 000)

### Sample Input 0

```
9 2
6 19 3 4 4 2 6 7 8
```

### Sample Output 0

```
2 5 11 18 30 43 62 83 121
```
