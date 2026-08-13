---
title: "Counting Sentences"
year: 2022
category: monthly
round: "April 2022"
sortkey: "2-monthly-04-05"
index: 5
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - April 2022"
contest_slug: "noi-2022-apr"
contest_url: "https://www.hackerrank.com/contests/noi-2022-apr"
problem_slug: "counting-sentences"
problem_url: "https://www.hackerrank.com/contests/noi-2022-apr/challenges/counting-sentences"
---

You are given an array of $$N$$ words and an integer $$K$$. You have to make different sentences by selecting a  [subsequence](https://en.wikipedia.org/wiki/Subsequence) of words from the words in the given array without changing their order. Also the difference between indices of any pair of selected words from the array should be greater than $$K$$.  In other words, let $$w1$$ and $$w2$$ be any two words in the array and their indices are $$i$$ and $$j$$. Then to select the both words($$w1$$ and $$w2$$) to make a sentence they must satisfy $$|$$ $$i$$ $$-$$ $$j$$ $$|$$ $$>$$ $$K$$.


Your task is to find the number of unique sentences you can make from the word array, modulo $$1 000 000 007$$ $$(10$$<sup>$$9$$</sup>$$+7)$$

## Input Format

The first line contains a single integer $$T$$, the number of test cases.

Each test case has two integers $$N$$ and $$K$$ seperated by space on the first line. The next $$N$$ lines each have a string that consists of lowercase English letters, describing one word in the word array.

## Output Format

- For each test case, output the number of unique sentences modulo $$1 000 000 007$$ $$(10$$<sup>$$9$$</sup>$$+7)$$ on a single line.

## Constraints

- $$1$$ $$\leq$$ $$T$$ $$\leq$$ $$1000$$
- $$1$$ $$\leq$$ $$N$$ $$\leq$$ $$10$$ <sup>$$5$$</sup>
- $$0$$ $$\leq$$ $$K$$ $$\leq$$ $$N-1$$
- The length of any word is between $$1$$ to $$10$$

### Sample Input 0

```
1
7 1
a
abc
abc
a
dac
a
a
```

### Sample Output 0

```
16
```
