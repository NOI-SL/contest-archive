---
title: "Calculate Payment"
year: 2022
category: monthly
round: "February 2022"
sortkey: "2-monthly-02-03"
index: 3
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - February 2022"
contest_slug: "noi-2022-feb"
contest_url: "https://www.hackerrank.com/contests/noi-2022-feb"
problem_slug: "calculate-payment"
problem_url: "https://www.hackerrank.com/contests/noi-2022-feb/challenges/calculate-payment"
---

You have got a loan of value ***L*** from your friend. But due to bad financial decisions, you don't have any money with you to payback the loan. But you have ***I*** number of items, that you own. Your friend has agreed to take your items instead of money for your loan. And he has given a value for each item you own. Now you want to figure out how many combinations of items that you can give to your friend to resolve the debt.  
  
The value of an item is defined by a single integer value, ***i***. There won’t be multiple items with the same value.  
A combination is a list of items that you are gonna give to your friend. A combination can have any number of items between ***1*** and ***I***.  

Given the value for each item & the amount you took as the loan(***L***), you have to find out the number of ways you can create a list of items that are worth excatly ***L***.

## Input Format

First line contains 2 integers, ***I*** & ***L***.   
Next line contains ***I*** space seperated integers(value of each item), with the **i<sup>th</sup>** of them being ***I<sub>i</sub>***.

## Output Format

***Number of ways*** that you can create a list of items that are worth ***L*** amount.

## Constraints

- **1 $$\leq$$ I, L $$\leq$$ 1000**
- **1 $$\leq$$ I<sub>i</sub> $$\leq$$ 1000**  
  &nbsp;  
   
#### **Limits**
- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
5 32
6 8 14 24 32
```

### Sample Output 0

```
2
```

### Sample Input 1

```
6 100
10 20 30 40 50 60
```

### Sample Output 1

```
5
```
