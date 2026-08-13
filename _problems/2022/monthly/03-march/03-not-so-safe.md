---
title: "Not So Safe"
year: 2022
category: monthly
round: "March 2022"
sortkey: "2-monthly-03-03"
index: 3
max_score: 100
difficulty: "Hard"
contest_name: "National Olympiad in Informatics Sri Lanka - March 2022"
contest_slug: "noi-2022-mar"
contest_url: "https://www.hackerrank.com/contests/noi-2022-mar"
problem_slug: "not-so-safe"
problem_url: "https://www.hackerrank.com/contests/noi-2022-mar/challenges/not-so-safe"
---

The year is 2077. You are a member of the Valentinos gang, tasked with breaking into Imperial Bank and cracking open a safe. Imperial Bank uses safes built by ‘AllSafe’. 
AllSafe safes of size ***n*** contain a ***nxn*** square formation of cells, each containing a unique digit ranging from **1** to ***n<sup>2</sup>***, which when arranged in the right order unlocks the safe. 

However, your gang has received information that AllSafe safes have a glitch in them. A key component of this glitch is Limbo cells. Two cells are in Limbo if the digits inside them differ by ***1***.

Two cells of a nxn square formation of cells are adjacent to each other when they have a common side, i.e cell ***(x,y)*** is adjacent to cells ***(x,y-1)***, ***(x-1,y)***, ***(x, y+1)*** and ***(x+1, y)***.

AllSafe safes can be cracked if the cells are arranged such that no two adjacent cells are in Limbo. You are required to find in advance a square matrix nxn cell configuration that will crack the safe of size ***n***. Note that there can be multiple cell configurations that will crack the safe.

## Input Format

- The first line contains a single integer ***t***, denoting the number of test cases.
 - Next ***t*** lines contains an integer ***n*** denoting the size of the safe ***n***.

## Output Format

-  For each test case, if it is **impossible** to find a such configuration output ***-1***.
-  Otherwise the ouput the cell configuration of the ***nxn*** matrix.

## Constraints

- 1 $$\leq$$ ***t*** $$\leq$$ 100
- 1 $$\leq$$ ***n*** $$\leq$$ 100

### Sample Input 0

```
3
1
2
3
```

### Sample Output 0

```
1 
-1
1 6 2 
7 3 8 
4 9 5 
```
