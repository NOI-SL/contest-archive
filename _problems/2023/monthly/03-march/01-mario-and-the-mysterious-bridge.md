---
title: "Mario and the Mysterious Bridge"
year: 2023
category: monthly
round: "March 2023"
sortkey: "2-monthly-03-01"
index: 1
max_score: 100
difficulty: "Hard"
contest_name: "National Olympiad in Informatics Sri Lanka - March 2023"
contest_slug: "noi-2023-mar"
contest_url: "https://www.hackerrank.com/contests/noi-2023-mar"
problem_slug: "mario-and-the-mysterious-bridge"
problem_url: "https://www.hackerrank.com/contests/noi-2023-mar/challenges/mario-and-the-mysterious-bridge"
---

Our super famous Mario likes to travel a lot. One day on his way, he has found a strange bridge that helps to cross from a to b.

This bridge consists with wooden blocks such that some of them are colored and some are discolored. These colorful ones can be either **red** or **blue**. When the Mario jumps to a red wooden block he gets **teleported forward** the number of blocks written in the particular red block. ( *if mario is in the red block no 2 and the number on the block 2 is 13, mario advances to the block no 15(**13+2)***). When mario jumps into a blue block he gets **teleported backwards** the no of the blocks written on that particular block. ( *if mario is on the blue block no 10 and the number on the block is 4, mario teleports to block no 6(**10-6**)*). Given the max distance mario can jump **J** (if j=3, mario can jump either 1,2 or 3 blocks each turn ) and locations of red and blue blocks and the number on each block , and also given the broken blocks, find the minimun no of jumps that required to reach the last block.

Mario starts at block no **1** and he ends at block no  **N**.


![image]({{ "/assets/problems/d2c44c7f-1674412428-694d6e271a-MarioAndTheMyst-min.png" | relative_url }})

## Input Format

1.First line contains the five integers **N,R,B,C, J**

2.Second line contains **R no of** interger pairs (x,y) such that x denotes the **red block no** and y denotes the number written in block x.

3.Third line contains **B no of** interger pairs (a,y) such that a denotes the **blue** block no and y denotes the number written in block a.

4.fourth line contains **C** no of intergers denoting the broken block indexes



*
- **N - index of end block**

- **R- no of red blocks**

- **B-no of blue blocks**

- **C-no of broken blocks**

- **J-maximum distance mario can jump**
*

## Output Format

output a single integer denoting the **minimum no of jumps** required to reach the end block **N**

## Constraints

1. starting and ending blocks cannot be broken.
2. Theres always a way to reach the end of the bridge.
3. If mario jumps or teleported on a red or blue block he must teleport according to block number( *he cannot stay on a red or blue block without teleporting*).
4. Mario cannot land on a broken block under any circumstance
5. 0<N,J<500

### Sample Input 0

```
36 5 5 3 2
2 13 5 2 9 18 18 11 25 10
17 13 20 14 24 8 32 2 34 22
2 7 9
```

### Sample Output 0

```
13
```
