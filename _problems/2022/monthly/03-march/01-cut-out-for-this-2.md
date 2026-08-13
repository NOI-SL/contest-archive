---
title: "Cut Out For This"
year: 2022
category: monthly
round: "March 2022"
sortkey: "2-monthly-03-01"
index: 1
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - March 2022"
contest_slug: "noi-2022-mar"
contest_url: "https://www.hackerrank.com/contests/noi-2022-mar"
problem_slug: "cut-out-for-this-2"
problem_url: "https://www.hackerrank.com/contests/noi-2022-mar/challenges/cut-out-for-this-2"
---

Punk Castle is recruiting soldiers for its Royal Army. As per the wishes of the Minister of Defence, Sir Iman Anna, roles will be assigned based on height, where everyone deemed ‘tall’ will man the rifles, while those deemed ‘short’ will man the barracks.  

All candidates will be personally interviewed by the minister himself. However, the minister is extremely short-tempered, and cannot stand having to interview two tall or two short people in succession. 

Vatserle, the Minister’s nephew, has been assigned as his Secretary. In an attempt to prove the court his intelligence and worth (as well as maintain the goodwill of his dearest Uncle) , Vatserle decides to rearrange the candidates, who are aligned in a queue, in a rather interesting manner. To do this, he proposes that the candidates can only be rearranged in portions where a selected portion (any contiguous sequence of people in the queue), will be selected at a time, and their order will be reversed. Vatserle challenges the court to find the minimum number of such operations required such that no two short or tall people stand in succession.

Given a queue of ***n*** men , denoted with a ***‘0’*** for those shorter than 6ft and ***‘1’*** for those above, where exactly **half is tall** and the **other half short**, what is the minimum number of such operations required?

## Input Format

- The first line contains a single integer ***t*** - the number of testcases.
- The first line of each test case contains a single integer ***n*** - the length of the queue.
- The second line of each test case contains a string of length ***n*** denoting the queue with ***'0'*** s and ***'1'*** s.

## Output Format

- For each test case, print the minimum number of such operations required.

## Constraints

- 1 $$\leq$$ ***t*** $$\leq$$ 1000
- 2 $$\leq$$ ***n*** $$\leq$$ 10<sup>5</sup>

### Sample Input 0

```
3
8
00010111
2
01
4
1001
```

### Sample Output 0

```
2
0
1
```
