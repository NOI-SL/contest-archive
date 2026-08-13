---
title: "Kamal's Village"
year: 2026
category: finals
round: "Final Round — Day 2"
sortkey: "3-finals-2-01"
index: 1
max_score: 100
difficulty: "Medium"
contest_name: "noi-2026-day-2"
contest_slug: "noi-2026-day-2"
contest_url: "https://www.hackerrank.com/contests/noi-2026-day-2"
problem_slug: "kamals-village"
problem_url: "https://www.hackerrank.com/contests/noi-2026-day-2/challenges/kamals-village"
---

Kamal's Village NetworkIn a rural district of Sri Lanka, there are $$N$$ isolated villages.   
Currently, the paths between them are overgrown, making travel impossible. Kamal, a local rural development officer, wants to connect all these villages.   
He can fund the following construction projects any number of times:  
1. Pay $$X_i$$ rupees to build a Railway Station in village $$i$$.  
2. Pay $$Y_i$$ rupees to build a Bus Depot in village $$i$$.  
3. Pay $$Z_i$$ rupees to clear and pave a direct Gravel Road between village $$A_i$$ and village $$B_i$$.  
  
Kamal’s goal is to make sure that a villager can travel between any two different villages $$U$$ and $$V$$.   
A villager can travel using any combination of the following methods:  
If two villages both have Railway Stations, villagers can take the train directly between them.  
If two villages both have Bus Depots, villagers can take an express bus directly between them. If two villages are connected by a Gravel Road, villagers can walk or take a tuk-tuk directly between them.  
Find the minimum total cost Kamal must spend so that every village is connected to the transport network.

## Input Format

**Input Format**  
The input is provided from Standard Input in the following format:  
The first line contains two space-separated integers, $$N$$ (the number of villages) and $$M$$ (the number of possible gravel roads). The second line contains $$N$$ space-separated integers, $$X_1, X_2, \dots, X_N$$, where $$X_i$$ is the cost to build a Railway Station in village $$i$$. The third line contains $$N$$ space-separated integers, $$Y_1, Y_2, \dots, Y_N$$, where $$Y_i$$ is the cost to build a Bus Depot in village $$i$$. The next $$M$$ lines each contain three space-separated integers, $$A_i, B_i, \text{ and } Z_i$$, representing a potential Gravel Road connecting village $$A_i$$ and village $$B_i$$ with a construction cost of $$Z_i$$.

## Output Format

Output Format
Print a single integer representing the minimum total cost Kamal needs to pay to ensure that every village is connected to every other village in the network.

## Constraints

$$2 \le N \le 2 \times 10^5$$  
$$1 \le M \le 2 \times 10^5$$  
$$1 \le X_i \le 10^9$$  
$$1 \le Y_i \le 10^9$$  
$$1 \le A_i < B_i \le N$$  
$$1 \le Z_i \le 10^9$$  
$$(A_i, B_i) \neq (A_j, B_j)$$ for all $$i \neq j$$ (There is at most one road between any pair of cities).  
All values in the input are integers.

### Sample Input 0

```
3 1
1 100 100
100 1 100
1 2 10
```

### Sample Output 0

```
111
```

### Sample Input 1

```
3 1
1 1 1
10 10 10
1 2 100
```

### Sample Output 1

```
3
```
