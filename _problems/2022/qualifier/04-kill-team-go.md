---
title: "Kill Team Go"
year: 2022
category: qualifier
round: "Selection Test"
sortkey: "1-qualifier-04"
index: 4
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - Screening Test 2022"
contest_slug: "noi-2022-selection-test"
contest_url: "https://www.hackerrank.com/contests/noi-2022-selection-test"
problem_slug: "kill-team-go"
problem_url: "https://www.hackerrank.com/contests/noi-2022-selection-test/challenges/kill-team-go"
---

Amanda Waller is assembling her “Suicide Squad”. The given roster of players contains Gamma players denoted by ***"G"*** that specialize in muscle-power, and Beta players denoted by ***"B"*** that specialize in planning. Waller can form a squad by picking a contiguous set of players from the roster while maintaining the original order.

The squad can further break itself into sub-squads. The size of a sub-squad, ranges from **a minimum of 2** to **the size of the entire squad**, and in a sub-squad, the order must be flippable without making a difference to the structure. In other words, the order of specialty of a sub-squad must be a [palindrome](https://en.wikipedia.org/wiki/Palindrome). For a selected squad to be an **ideal squad**, every member should be a part of at least one such sub-squad.

How many different ideal squads can Waller form from the given roster?

Note that when forming the squads, the initial order of players should never be altered.
Check the explanation given below.

## Input Format

- The first line contains a single integer ***n*** denoting the number of players.
- The second line contains ***n*** number of characters, denoting the order of specialization of the players in the roster.

## Output Format

-  Print the **number of different ideal squads** that can be formed from the roster.

## Constraints

- 1 $$\leq$$ ***n*** $$\leq$$ 3*10<sup>5</sup>

#### **Limits**

- **Time Limit**: 2s
- **Memory Limit**: 256MB

### Sample Input 0

```
5
GGGBB
```

### Sample Output 0

```
6
```

### Sample Input 1

```
5
GGBBG
```

### Sample Output 1

```
5
```
