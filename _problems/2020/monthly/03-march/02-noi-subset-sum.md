---
title: "Subsets Sum"
year: 2020
category: monthly
round: "March 2020"
sortkey: "2-monthly-03-02"
index: 2
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - March 2020"
contest_slug: "noi-2020-mar"
contest_url: "https://www.hackerrank.com/contests/noi-2020-mar"
problem_slug: "noi-subset-sum"
problem_url: "https://www.hackerrank.com/contests/noi-2020-mar/challenges/noi-subset-sum"
---

You are given a  [set](https://en.wikipedia.org/wiki/Set_(mathematics)) of ***N*** positive integers (***set A***). Find the number of [subsets](https://en.wikipedia.org/wiki/Subset) that have their sums equal to ***S***.  
Subsets may have any number of integers between ***1*** to ***N*** (***inclusive***).  
***Note: A set will not consist of repeated elements***

*Example 1*  
```
If A = {1, 2, 5, 10, 12} & S = 12,  
Then subsets are,  
{2, 10} & {12}
```  
   
*Example 2*  
```
If A = {1, 2, 3, 4, 5} & S = 5,  
Then subsets are,  
{1, 4}, {2, 3} & {5}
```

## Input Format

First line contains 2 integers, ***N*** & ***S***.   
Next line contains ***N*** space seperated integers(integers of the set A), with the **i<sup>th</sup>** of them being ***A<sub>i</sub>***.

## Output Format

***Number of subsets*** that have their sums equal to ***S***.

## Constraints

- **1 $$\leq$$ N, S $$\leq$$ 1000**
- **1 $$\leq$$ A<sub>i</sub> $$\leq$$ 1000**  
  &nbsp;  
   
#### **Limits**
- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
5 12
1 2 5 10 12
```

### Sample Output 0

```
2
```

### Sample Input 1

```
5 5
1 2 3 4 5
```

### Sample Output 1

```
3
```
