---
title: "Dilshan's Juice Bar"
year: 2021
category: monthly
round: "February 2021"
sortkey: "2-monthly-02-02"
index: 2
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - February 2021"
contest_slug: "noi-2021-feb"
contest_url: "https://www.hackerrank.com/contests/noi-2021-feb"
problem_slug: "dilshans-juice-bar"
problem_url: "https://www.hackerrank.com/contests/noi-2021-feb/challenges/dilshans-juice-bar"
---

Dilshan is an aspiring chef who is planning to open his own juice bar. He has a list of ingredients with ***I*** number of items. The list also contains the sweetness value for each ingredient. He wants to find out how many juices he can create of a specific sweetness value ***S***, using the available ingredients.  
  
The sweetness of an ingredient is defined by a single integer value, ***i***. There won’t be multiple ingredients with the same sweetness value.  
A juice is prepared by adding equal amounts of one or more ingredients together. The sweetness value of a juice is the sum of sweetness values of each ingredient of that juice. A juice can have any number of ingredients between ***1*** and ***I***.  

Given the sweetness value for each ingredient & the sweetness value required, you have to find out the number of juices that can be created for that sweetness value.

## Input Format

First line contains 2 integers, ***I*** & ***S***.   
Next line contains ***I*** space seperated integers(sweetness value of each ingredient), with the **i<sup>th</sup>** of them being ***I<sub>i</sub>***.

## Output Format

***Number of juices*** that can have a sweetness value of ***S***.

## Constraints

- **1 $$\leq$$ I, S $$\leq$$ 1000**
- **1 $$\leq$$ I<sub>i</sub> $$\leq$$ 1000**  
  &nbsp;  
   
#### **Limits**
- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
5 16
3 4 7 12 16
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
