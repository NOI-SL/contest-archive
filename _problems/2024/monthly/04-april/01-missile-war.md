---
title: "Missile war"
year: 2024
category: monthly
round: "April 2024"
sortkey: "2-monthly-04-01"
index: 1
max_score: 100
difficulty: "Hard"
contest_name: "NOI 2024 April Monthly Contest"
contest_slug: "noi-2024-april"
contest_url: "https://www.hackerrank.com/contests/noi-2024-april"
problem_slug: "missile-war"
problem_url: "https://www.hackerrank.com/contests/noi-2024-april/challenges/missile-war"
---

There are two countries $$A$$ and $$B$$ at war. Country $$A$$ plans to attack $$t$$ number of targets and country $$B$$ wants to defend them.

$$A$$ has $$n$$ missile systems. Each missile system has a set of predifined targets and will attack all targets in that set.

$$B$$ has $$m$$ defence systems. Each defence system has a set of predifined targets and a defence capacity $$c$$. A single defence system can choose to defend $$r$$ targets in it's set such that $$r \leq c$$.

Your task is to find out the maximum amount of succesful defence operations that can be carried out by $$B$$.

There can be multiple defence operations on a single target.

## Input Format

- First line contains three space seperated integers $$n$$ $$m$$ $$t$$
- next $$n$$ lines contains attack range of $$i^{th}$$ ($$1 \leq i \leq n$$) missile system,
  - integer $$|r_i|$$ followed by $$|r_i|$$ space seperated integers $$r_i$$. ($$r_i$$ are the targets of the Missile system $$i$$)
- next $$m$$ lines contains defence range of $$i^{th}$$ ($$1 \leq i \leq m$$) missile system,
  - integer $$|r_i|$$ followed by $$|r_i|$$ space seperated integers $$r_i$$. ($$r_i$$ are the targets of the defence system $$i$$)
- next line contains $$m$$ space seperated integers (Capacity of each defence system)

## Output Format

- Single Integer - maximum amount of succesful defence operations

## Constraints

Constraints:

- $$1 \leq n,m,t \leq 10^3$$
- $$0 \leq c_i \leq 10^3$$
- $ 0 \leq |r_i| \leq 10^3$

### Sample Input 0

```
2 2 3
1 1
2 2 3
2 1 2
1 3
1 2
```

### Sample Output 0

```
2
```
