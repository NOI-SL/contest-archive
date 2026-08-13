---
title: "The Cyber Heist"
year: 2026
category: finals
round: "Final Round — Day 2"
sortkey: "3-finals-2-03"
index: 3
max_score: 100
difficulty: "Medium"
contest_name: "noi-2026-day-2"
contest_slug: "noi-2026-day-2"
contest_url: "https://www.hackerrank.com/contests/noi-2026-day-2"
problem_slug: "the-cyber-heist"
problem_url: "https://www.hackerrank.com/contests/noi-2026-day-2/challenges/the-cyber-heist"
---

A legendary data runner, "Cipher," is attempting to extract a highly sensitive file from the heavily fortified MegaCorp network. The network consists of various servers connected by two-way data streams. Cipher needs to route their connection from their personal terminal (node $$S$$) to the central mainframe (node $$W$$) where the file is stored.

Each data stream has a base traversal time required to bypass its standard encryption and route the packets. 

However, MegaCorp has deployed hidden Intrusion Detection Systems (IDS) on specific servers, known as "watchtower nodes". If Cipher's connection routes through any watchtower node, the network's active defense protocols are triggered, putting the system on high alert. Once the network is on high alert, the encryption overhead is massively increased, and the traversal time for **all subsequent data streams Cipher crosses is doubled**.

Your task is to calculate the **minimum total time** required for Cipher to route their connection from their **starting terminal (node $$S$$) to the mainframe (node $$W$$)**, taking into account the watchtower nodes and their effect on traversal times.

## Input Format

- The first line contains two integers $$N$$ and $$M$$, the number of servers (nodes) and data streams (edges) in the network.
- The second line contains two integers $$S$$ and $$W$$, the start terminal node and the target mainframe node.
- The third line contains an integer $$K$$, the number of watchtower nodes.
- The fourth line contains $$K$$ distinct integers representing the watchtower nodes.
- The next $$M$$ lines each contain three integers $$u$$, $$v$$, and $$w$$, representing an undirected data stream between servers $$u$$ and $$v$$ with a base traversal time of $$w$$.

## Output Format

Output a single integer — the minimum total time required for Cipher to reach the mainframe $$W$$ from the starting node $$S$$.

## Constraints

- $$1 \leq N \leq 10^5$$
- $$1 \leq M \leq 2 \times 10^5$$
- $$1 \leq S, W, u, v \leq N$$
- $$0 \leq K \leq N$$
- $$1 \leq w \leq 10^9$$
- The graph may contain multiple edges and self-loops.
- The graph is connected such that there is at least one path from $$S$$ to $$W$$.

### Sample Input 0

```
8 10
1 8
2
3 6
1 2 4
1 3 2
2 4 1
3 4 5
2 5 7
3 6 2
4 7 3
5 7 2
6 7 1
7 8 4
```

### Sample Output 0

```
12
```
