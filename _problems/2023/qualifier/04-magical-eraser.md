---
title: "Magical Eraser"
year: 2023
category: qualifier
round: "Selection Test"
sortkey: "1-qualifier-04"
index: 4
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - Screening Test 2023"
contest_slug: "noi-2023-selection-test"
contest_url: "https://www.hackerrank.com/contests/noi-2023-selection-test"
problem_slug: "magical-eraser"
problem_url: "https://www.hackerrank.com/contests/noi-2023-selection-test/challenges/magical-eraser"
---

You are given a magic eraser and tasked with erasing a word. When you use the magic eraser on a character on a word, if the characters on the left or right are the same character as the charcter you are using the eraser on, all those adjacent same characters are erased at once.  
ex: `abaaaaaca` becomes `abca` when the magic eraser is used on any of the `a` characters in the middle.  
Find out the minimum number of uses of the magic eraser that you need to erase the given word completely.

## Input Format

one line containing $$n$$: the length of the word  
one line containing the word

## Output Format

one line containing the minimum number of magic eraser uses to erase the word.

## Constraints

all characters in the word are lowercase english letters  
$$10 \le n \le 1000$$

### Sample Input 0

```
10
bbbabaabaa
```

### Sample Output 0

```
4
```
