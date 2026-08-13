---
title: "Dilshan's Juice Bar's Menu"
year: 2021
category: monthly
round: "February 2021"
sortkey: "2-monthly-02-03"
index: 3
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - February 2021"
contest_slug: "noi-2021-feb"
contest_url: "https://www.hackerrank.com/contests/noi-2021-feb"
problem_slug: "dilshans-juice-bars-menu"
problem_url: "https://www.hackerrank.com/contests/noi-2021-feb/challenges/dilshans-juice-bars-menu"
---

Dilshan is an aspiring chef who is planning to open his own juice bar. He has a list of ingredients with ***I*** number of items. The list also contains the sweetness value for each ingredient. Now he wants to divide the menu of his juice bar based on the sweetness value of each juice. So, he has created ***C*** number of sections for his menu. He wants to find out how many types of juices he can prepare that falls under each section in his menu, using the available ingredients.
  
The sweetness of an ingredient is defined by a single integer value, ***i***. There won’t be multiple ingredients with the same sweetness value.  
A juice is prepared by adding equal amounts of one or more ingredients together. The sweetness value of a juice is the sum of sweetness values of each ingredient of that juice. A juice can have any number of ingredients between ***1*** and ***I***.  
A menu section is defined by 2 integers, the starting sweetness value (***S***) & ending sweetness value (***E***) for that section.  
  
Given the sweetness value for each ingredient & the starting and ending values for each section, you have to find out the number of juices that can be created for each menu section.

## Input Format

First line contains 2 integers, ***I*** & ***C***.   
Next line contains ***I*** space seperated integers(sweetness value of each ingredient), with the **i<sup>th</sup>** of them being ***I<sub>i</sub>***.  
***C*** lines follow, with the **j<sup>th</sup>** of them having 2 integers, ***S<sub>j</sub>*** and ***E<sub>j</sub>***, the starting and ending sweetness value for the **j<sup>th</sup>** section.

## Output Format

***C*** lines, with **j<sup>th</sup>** of them having a single number, the ***Number of juices*** that can be created for the **j<sup>th</sup>** section in the menu.

## Constraints

- **1 $$\leq$$ I $$\leq$$ 20**
- **1 $$\leq$$ C $$\leq$$ 10<sup>6</sup>**
- **1 $$\leq$$ I<sub>i</sub> $$\leq$$ 10<sup>8</sup>**  
- **0 $$\leq$$ S<sub>j</sub> $$<$$ E<sub>j</sub> $$\leq$$ 10<sup>8</sup>**  
  &nbsp;  
   
#### **Limits**
- **Time Limit**: 2s
- **Memory Limit**: 256MB

### Sample Input 0

```
5 4
3 4 7 12 16
1 4
7 8
10 20
100 150
```

### Sample Output 0

```
2
2
11
0
```

### Sample Input 1

```
5 2
1 2 3 4 5
1 5
7 8
```

### Sample Output 1

```
9
6
```
