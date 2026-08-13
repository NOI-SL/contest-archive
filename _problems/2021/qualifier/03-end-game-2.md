---
title: "End Game 2"
year: 2021
category: qualifier
round: "Selection Test"
sortkey: "1-qualifier-03"
index: 3
max_score: 100
difficulty: "Hard"
contest_name: "National Olympiad in Informatics Sri Lanka - Screening Test 2021"
contest_slug: "noi-2021-selection-test"
contest_url: "https://www.hackerrank.com/contests/noi-2021-selection-test"
problem_slug: "end-game-2"
problem_url: "https://www.hackerrank.com/contests/noi-2021-selection-test/challenges/end-game-2"
---

In End Game 1 Thanos, an intergalactic warlord, disintegrates half of the universe. But then Thanos realized that it was not the best way to make the universe perfectly balanced. The only way to make the universe perfectly balanced is by changing the **UBC(Universal Binary Code)** of the universe. **UBC** is a string that only consists of **1s and 0s(leading 0s are allowed)** that represent all the decoded information about a universe. 

So Thanos knows the **UBC** of a perfectly balanced universe **(PUBC- Perfect Universal Binary Code)** and he wants to find if he can make this universe perfectly balanced. 

You are given the **PUBC** and the **UBC** of equal even length ***n***. You need to balance **UBC** by doing the following operation on **UBC** at most ***n+1*** times. Balancing **UBC** means **making strings UBC equal to PUBC.**

In each operation you can select an **even size prefix** from the **UBC** and **reverse it.**

Find a way to balance **UBC** and **PUBC** by doing the the above operation, or determine it is impossible.

## Input Format

- The first line contains a single integer ***t***, denoting the number of test cases.
- Each test case consists of two lines. The first line contains a string **UBC** of length ***n***, and the second line contains a string **PUBC** of the same length . Both strings consist of characters ***0*** and ***1***.

## Output Format

- For each test case, if it's impossible to make **UBC** equal to **PUBC** in at most ***n+1*** reversals, output a single integer ***−1***.
- Otherwise, output an integer ***k*** ***(0 $$\leq$$ k $$\leq$$ n+1)***, denoting the number of reversals in your sequence of operations, followed by ***k*** **even integers** ***p1,p2,…,pk*** ***(2 $$\leq$$ p<sub>i</sub> $$\leq$$ n)***, denoting the lengths of prefixes of a to be reversed, in chronological order.

## Constraints

1. For 10% of test cases
- 1 $$\leq$$ ***t*** $$\leq$$ 2000
- n **=** 2

1. For 90% of test cases
- 1 $$\leq$$ ***t*** $$\leq$$ 2000
- 2 $$\leq$$ ***n*** $$\leq$$ 4000

### Sample Input 0

```
4
0100011011
1101011000
10101010
10101010
0011
1001
100011
110010
```

### Sample Output 0

```
3
6 4 10
0

-1
7
2 6 2 6 2 2 6
```
