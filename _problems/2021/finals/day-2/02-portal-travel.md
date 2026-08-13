---
title: "Portal Travel"
year: 2021
category: finals
round: "Final Round — Day 2"
sortkey: "3-finals-2-02"
index: 2
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka 2021 - Day 2"
contest_slug: "noi-2021-day-2"
contest_url: "https://www.hackerrank.com/contests/noi-2021-day-2"
problem_slug: "portal-travel"
problem_url: "https://www.hackerrank.com/contests/noi-2021-day-2/challenges/portal-travel"
---

You manage a travel agency that lets people travel through portals.  
Each portal has a token (a string that contains only A-Z characters)  

The travel cost through a portal ***A*** to ***B*** is the cost of transforming the token of portal ***A*** to portal ***B***, Calculated as follows:  
  
- **1pt**: Add 1 character  
- **1pt**: Remove 1 character  
- **1pt**: Replace 1 character  
  
As a portal travel agent, you have access to a magic character that you can use at most
twice for each transaction. You can use this magic character for free, to replace an existing character.  

Given the tokens of the portals your customers want to travel through, calculate the
minimum travel fee you can get for them.

## Input Format

First line contains the token for **portal A**  
Second line contains the token for **portal B**

## Output Format

Single line containing the minimum travel fee you can get for them.

## Constraints

If token lengths for portals **A** & **B** are **N** & **M**, respectively. 

- **1 $$\leq$$ N, M $$\leq$$ 10<sup>4</sup>**

#### **Subtasks**  

1. **For 20% of the test cases**: 1 $$\leq$$ N, M $$\leq$$ 25   
1. **For the next 20% of the test cases**: 1 $$\leq$$ N, M $$\leq$$ 500   
3. **For the remaining test cases**: No additional constraints. 
        
#### **Limits**  

- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
AHDKCY
KHLCYX
```

### Sample Output 0

```
2
```
