---
title: "Visit Sri Lanka"
year: 2023
category: finals
round: "Final Round — Day 1"
sortkey: "3-finals-1-01"
index: 1
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka 2023 - Day 1"
contest_slug: "noi-2023-day-1"
contest_url: "https://www.hackerrank.com/contests/noi-2023-day-1"
problem_slug: "visit-sri-lanka-1"
problem_url: "https://www.hackerrank.com/contests/noi-2023-day-1/challenges/visit-sri-lanka-1"
---

The Tourist Board of Sri Lanka wants to contribute more to the economy by increasing revenue from tourism. With that intention, they decided to develop facilities in cities in a subset of all the cities. The proposal with the list of cities needs to be approved by Mr X the president of Sri Lanka. He approves a proposal that looks cost-effective according to his criteria. A proposal is cost-effective only if all the proposed cities are located on a single path from Colombo or at least there is an immediate neighbouring city which is on that path. 

The bidirectional road network of Sri Lanka connects each city such that there is only one unique shortest path between every pair of cities(Cities and roads form a tree). A path is a sequence of roads which joins a sequence of cities without any repeating cities.

There is **n number of cities** and **n-1 roads** that connects cities. There is only one road between each pair of neibouring cities and there are no roads from a city to itself.
The tourist board has **m proposal** with different subsets of cities. The director of the tourist board wants your assistance to decide which proposals are approvable and which are not.

## Input Format

- First line: Two integers n and m, the number of cities and the number of proposals.
- Next n-1 lines: Each line has two integers a and b describing each bidirectional road(a ⍯ b)
- <s>Next 2m lines:
	In each pair of lines
	- The first line contains c which is the number of cities in the given proposal
	- The next line has c numbers denoting each city in the proposal</s>
- Next m lines:
	In each line
	- The first integer contains c which is the number of cities in the given proposal
	- The c integers denotes each city in the proposal

**Cities are named from 1 to n. Colombo is named as 1.**

## Output Format

Output m lines. The output of i<sup>th</sup> line should be ‘Approved’ if the proposal meets the president’s criteria. Otherwise output ‘Declined’.

## Constraints

1 $$\leq$$ n $$\leq$$ 10<sup>5</sup>
1 $$\leq$$ m $$\leq$$ 10<sup>5</sup>

Sum of C<sub>i</sub> $$\leq$$ 3*10<sup>5</sup> (0 $$\leq$$ i $$\leq$$ m-1) 

#### **Limits**
- **Time Limit**: 1s
- **Memory Limit**: 512MB

### Sample Input 0

```
8 2
1 2
1 3
2 5
3 4
3 6
4 8
4 7
3 3 6 8
2 5 7
```

### Sample Output 0

```
Approved
Declined
```
