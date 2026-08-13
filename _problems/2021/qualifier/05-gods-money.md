---
title: "God's Money"
year: 2021
category: qualifier
round: "Selection Test"
sortkey: "1-qualifier-05"
index: 5
max_score: 100
difficulty: "Easy"
contest_name: "National Olympiad in Informatics Sri Lanka - Screening Test 2021"
contest_slug: "noi-2021-selection-test"
contest_url: "https://www.hackerrank.com/contests/noi-2021-selection-test"
problem_slug: "gods-money"
problem_url: "https://www.hackerrank.com/contests/noi-2021-selection-test/challenges/gods-money"
---

Asgard - home to the god of Thunder, has a currency system very different from Earth’s system. Gods being gods, they have infinite types of Asgardian Coins, with their values following the pattern **1939 $$\times$$ 10<sup>k</sup> where 0 $$\leq$$ k $$\lt$$ $$\infty$$** .

So the values of the coins go like 1939, 19390, 193900, and so on until infinity.

Loki, the god of mischief has an infinite supply of Asgardian Coins of all the infinite types. But he’s very greedy about spending his treasures.

Popular for your geniusness, Loki hired you to be his personal finance manager. Your task is simple; given any amount, you have to find the minimum number of coins that Loki needs to settle that exact amount, or state that it’s not possible to settle the required amount even with Loki’s infinite supply of infinite types of Asgardian Coins.

## Input Format

- The first line contains an integer ***Q***, the number of queries
- The **i<sup>th</sup>** line of next ***Q*** lines contain an integer ***A<sub>i</sub>***, representing an amount to be settled

## Output Format

Print ***Q*** lines, the ***i<sup>th</sup>*** line containing the minimum number of coins needed to settle the ***A<sub>i</sub><sup>th</sup>*** amount, or -1 if it is impossible to settle the exact amount.

## Constraints

- 1 $$\leq$$ ***Q*** $$\leq$$ 10<sup>5</sup>
- 0 $$\lt$$ ***A<sub>i</sub>*** $$\leq$$ 10<sup>18</sup>



For 50% of the testcases:

- 0 $$\lt$$ ***A<sub>i</sub>*** $$\leq$$ 10<sup>9</sup>

### Sample Input 0

```
3
1939
1940
193900
```

### Sample Output 0

```
1
-1
1
```
