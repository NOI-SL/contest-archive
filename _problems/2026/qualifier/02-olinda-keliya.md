---
title: "Olinda Keliya"
year: 2026
category: qualifier
round: "Qualifier Round"
sortkey: "1-qualifier-02"
index: 2
max_score: 100
difficulty: "Medium"
contest_name: "NOI 2026 Qualifier Round"
contest_slug: "noi-2026-qualifier-round"
contest_url: "https://www.hackerrank.com/contests/noi-2026-qualifier-round"
problem_slug: "olinda-keliya"
problem_url: "https://www.hackerrank.com/contests/noi-2026-qualifier-round/challenges/olinda-keliya"
---

During the Sinhala and Tamil New Year, two siblings are playing a strategic variation of the traditional game *Olinda Keliya* using bright red Olinda seeds. 

Instead of a traditional board, they have carved a long, straight groove into a piece of wood with $$N$$ small pits in a row, numbered $$1$$ to $$N$$ from left to right. Initially, the $$i^{\text{th}}$$ pit contains $$A_i$$ Olinda seeds. 

The players take turns. In a single turn, a player must choose a pit $$i$$ (where $$1 \le i < N$$) that currently contains at least one Olinda seed. The player picks up exactly one seed from pit $$i$$ and drops it into the adjacent pit to the right, pit $$i+1$$. 

Pit $$N$$ is the "Maha" (Great) pit. Once a seed is dropped into the Maha pit, it has reached its final destination and cannot be moved again.

The game ends when all the Olinda seeds on the board have been moved to the Maha pit (pit $$N$$). A player loses the game if it is their turn and they cannot make a valid move. The other player is then declared the winner.

Assuming both siblings play optimally, determine whether the First Player or the Second Player will win based on the starting arrangement of the seeds.

## Input Format

The first line contains a single integer, $$T$$, representing the number of test cases.

For each test case:

* The first line contains a single integer, $$N$$, representing the number of pits.
* The second line contains $$N$$ space-separated integers $$A_1, A_2, \dots, A_N$$, representing the initial number of Olinda seeds in each pit.

## Output Format

For each test case, print a single line containing `First` if the first player wins, or `Second` if the second player wins.

## Constraints

* $$1 \le T \le 100$$
* $$2 \le N \le 10^5$$
* $$0 \le A_i \le 10^9$$
* It is guaranteed that the sum of $$N$$ over all test cases does not exceed $$2 \cdot 10^5$$.

### Sample Input 0

```
3
3
1 1 0
4
0 2 0 0
2
8 0
```

### Sample Output 0

```
First
Second
Second
```
