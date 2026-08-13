---
title: "Cats and Dogs"
year: 2022
category: finals
round: "Final Round — Day 1"
sortkey: "3-finals-1-03"
index: 3
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka 2022 - Day 1"
contest_slug: "noi-2022-day-1"
contest_url: "https://www.hackerrank.com/contests/noi-2022-day-1"
problem_slug: "cats-and-dogs-7"
problem_url: "https://www.hackerrank.com/contests/noi-2022-day-1/challenges/cats-and-dogs-7"
---

Suvin introduced a game played by two players, Cat and Dog, on an undirected connected graph. The players take alternate turns. The graph has $$N$$ nodes $$(0, 1, 2, … ,N-1)$$, and $$E$$ edges. Two nodes $$u$$ and $$v$$ are called adjacent if there is an edge between $$u$$ and $$v$$.

The **Cat starts** at node $$1$$, and goes first. The **Dog starts** at node $$2$$ and goes second. The **Cat’s house** is at node $$0$$. During each player’s turn, they must travel along one edge of the graph, to an adjacent node.

Furthermore, it is not allowed for the Dog to travel to Cat’s house at node $$0$$.

The game ends when either of the following three ways are met:

1. If ever the Dog occupies the same node as the Cat, the Dog wins
2. If ever the Cat reaches its House, the Cat wins
3. If ever, a game position is repeated, the game is a draw

Given the graph, and assuming both players play optimally, your task is to determine the winner of each game.

Example game positions:

- (Cat on Node 5, Dog on Node 3, current turn being the Cat’s turn)
- (Cat on Node 5, Dog on Node 3, current turn being the Dog’s turn)
- (Cat on Node 0, Dog on Node 5, current turn being the Cat’s turn)

## Input Format

The first line contains an integer $$T$$, denoting the number of games.

Then for each game $$t_i$$:

- The first line contains two integers $$N$$, and $$E$$
- Next $$E$$ lines contain two integers $$u$$, and $$v$$, denoting an edge between node $$u$$ and $$v$$

## Output Format

For each game $$t_i$$:
Print a single word:

- **CAT** if Cat wins the game
- **DOG** if Dog wins the game 
- **DRAW** if game is a draw

## Constraints

- $$1 \leq T \leq 10$$
- $$3 \leq N \leq 50$$
- $$N-1 \leq E \leq N * (N-1) / 2$$

#### **Limits**
- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
2
4 3 
0 1
0 3
2 3
6 7
0 2
0 5
1 3
2 4 
2 5
3 4
3 5
```

### Sample Output 0

```
CAT
DRAW
```
