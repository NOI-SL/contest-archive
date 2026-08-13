---
title: "The Candy Shop Conundrum"
year: 2024
category: qualifier
round: "Qualifier Round"
sortkey: "1-qualifier-03"
index: 3
max_score: 100
difficulty: "Medium"
contest_name: "NOI 2024 Qualifier Round"
contest_slug: "noi-2024-qualifier-round"
contest_url: "https://www.hackerrank.com/contests/noi-2024-qualifier-round"
problem_slug: "the-candy-shop-conundrum"
problem_url: "https://www.hackerrank.com/contests/noi-2024-qualifier-round/challenges/the-candy-shop-conundrum"
---

**Storyline**

You run a charming candy shop known for its 12 unique flavors of handcrafted sweets. Each flavor comes in a different colored wrapper, numbered 1 to 12. Business is booming, and you've just received a large order

You have several empty candy packets, each capable of holding up to 10 pieces of candy.  Your customers are picky, and they much prefer packets containing only a single flavor of candy (a "single-flavor" packet). However, you may not have enough packets to make every packet single-flavor.

**Challenge**

Given the number of candy packets you have (P), and the quantity of each flavor (F[1] through F[12]), figure out the smallest possible number of packets that will end up containing multiple flavors ("mix-flavor" packets).

F = [7,24,...,11]

- Flavor 1 (F[1]): 7 pieces
- Flavor 2 (F[2]): 24 pieces
- ...
- Flavor 12 (F[12]): 11 pieces

Calculate this minimum number of mix-flavor packets for a given number of packets (P) and candy quantities (F[1,2,..12]).

## Input Format

- First line will be an integer representing P
- Second line will be an integer array representing F[]

## Output Format

- Output should be an integer (the minimum number of mix-flavor packets for the given inputs)

## Constraints

- You have to use up all the candy
- No box can hold more than 10 pieces
- Sum of (F[1], F[2], ... F[12]) =< 10P

### Sample Input 0

```
8
1 2 3 4 5 6 7 8 9 10 11 12
```

### Sample Output 0

```
4
```
