---
title: "Array query-1"
year: 2023
category: monthly
round: "February 2023"
sortkey: "2-monthly-02-04"
index: 4
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - February 2023"
contest_slug: "noi-2023-feb"
contest_url: "https://www.hackerrank.com/contests/noi-2023-feb"
problem_slug: "arrayquery-1"
problem_url: "https://www.hackerrank.com/contests/noi-2023-feb/challenges/arrayquery-1"
---

You're given two arrays $$A$$ and $$B$$ of sizes $$N$$ and $$M$$ respectively. $$C$$ is an array of size $$N * M$$, which consist of $$A_i + B_j$$ for all $$1 \le i \le N$$ and $$1 \le j \le M$$. You have to answer $$Q$$ queries such that for $${Q_i}^{th}$$ query, you have to print how many values of array $$C$$ are greater than $${X_i}^{th}$$  smallest element and smaller than $${Y_i}^{th}$$ smallest element or greater than $${Y_i}^{th}$$  smallest element and smaller than $${X_i}^{th}$$ smallest element of array $$C$$. The problem is divided into two subtasks depends on the constraints. Initially $$P$$ will be given to indicate the which subtask the problem belongs to.

## Input Format

The first line contains three space-separated integers $$N,\ M$$ and $$P$$. The second line contains $$N$$ space-separated integers denoting the elements of array $$A$$. The third line contains $$M$$ space-separated integers denoting the elements of array $$B$$. The fourth line contains $$Q$$. Each of the next $$Q$$ lines contain two space-separated integers $$X$$ and $$Y$$.

## Output Format

Print number of values for each query on separate line.

## Constraints

$$0 \le P \le 1$$  
$$0 \lt X_i\ ,\ Y_i \le N * M$$ 

When $$P = 0$$

$$0 \lt A_i\ ,\ B_j \le 10000$$  
$$0 \lt N \le 5000$$  
$$0 \lt M \le 10 ^ 5$$  
$$0 \lt Q \le 10 ^ 6$$  

When $$P = 1$$  

$$0 \lt A_i\ ,\ B_j \le 10 ^ 8$$  
$$0 \lt N\ ,\ M \le 10 ^ 5$$  
$$0 \lt Q \le 50$$

### Sample Input 0

```
2 2 0
1 2
2 3
2
1 4
2 4
```

### Sample Output 0

```
2
0
```
