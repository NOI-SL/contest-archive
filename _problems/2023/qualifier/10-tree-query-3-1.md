---
title: "Tree query - 3"
year: 2023
category: qualifier
round: "Selection Test"
sortkey: "1-qualifier-10"
index: 10
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - Screening Test 2023"
contest_slug: "noi-2023-selection-test"
contest_url: "https://www.hackerrank.com/contests/noi-2023-selection-test"
problem_slug: "tree-query-3-1"
problem_url: "https://www.hackerrank.com/contests/noi-2023-selection-test/challenges/tree-query-3-1"
---

You are given a tree consisting of $$N$$ nodes. You have to answer $$Q$$ queries. In each query, you have to find whether there is a node $$Y$$ in distance >= $$K$$ from node $$X$$.

## Input Format

The first line contains an integer $$N$$ denotes the number of nodes. The next $$N - 1$$ line contains $$2$$ space-separated integers denoting the connection between nodes. The next line contains $$Q$$. Each of the next $$Q$$ lines contain two space-separated integers $$X$$ and $$K$$.

## Output Format

If there is a node, print "YES" else print "NO".

## Constraints

$$2 \le N \le 10 ^ 5$$    
$$0 \lt Q \le 10 ^ 5$$  
$$0 \lt K \lt N$$

### Sample Input 0

```
4
0 1
1 2
2 3
4
0 2
0 3
3 3
1 3
```

### Sample Output 0

```
YES
YES
YES
NO
```
