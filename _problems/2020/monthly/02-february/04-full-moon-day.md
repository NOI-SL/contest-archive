---
title: "Full Moon Day"
year: 2020
category: monthly
round: "February 2020"
sortkey: "2-monthly-02-04"
index: 4
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - February 2020"
contest_slug: "noi-2020-feb"
contest_url: "https://www.hackerrank.com/contests/noi-2020-feb"
problem_slug: "full-moon-day"
problem_url: "https://www.hackerrank.com/contests/noi-2020-feb/challenges/full-moon-day"
---

In a galaxy far, far away, there’s a planet named Planet-X.  This planet has ***M*** months per year and ***D*** days per month. However, unlike planet Earth it has ***N*** number of moons. Each moon takes a different number of days (***X<sub>n</sub>***) to orbit Planet-X. So, on this planet a day is called a Full Moon day, if all the moons get its lunar phase as Full Moon on that day. ( A lunar phase of a moon is the shape of the sunlit portion of the moon i.e. the visible portion of the moon )  

Given a date of a full moon day(***D<sub>1</sub>***), your task is to find whether the 2nd date(***D<sub>2</sub>***) is a full moon day. If it’s not a full moon day, find ***C***, the number of days to the closest full moon day.

## Input Format

First line contains **3** integers, ***M***, ***D*** & ***N***.  
Next line contains ***N*** integers, ***X<sub>1</sub>***, ***X<sub>2</sub>***, ..., ***X<sub>n</sub>***  
Next line contains **3** integers, ***y<sub>1</sub>***, ***m<sub>1</sub>***, ***d<sub>1</sub>***. The year, month and date of ***D<sub>1</sub>*** respectively.  
Last line contains **3** integers, ***y<sub>2</sub>***, ***m<sub>2</sub>***, ***d<sub>2</sub>***. The year, month and date of ***D<sub>2</sub>*** respectively.

## Output Format

If ***D<sub>2</sub>*** is a Full Moon Day, print “***FULL MOON DAY***”.  
If not, print a single positive integer ***C***, the number of days to the closest full moon day.

## Constraints

If the number of days between D1 & D2 is Z,  
  
- **1 $$\leq$$ M, D $$\leq$$ 10<sup>4</sup>**
- **1 $$\leq$$ N $$\leq$$ 10<sup>2</sup>**
- **1 $$\leq$$ X<sub>n</sub> $$\leq$$ M * 3**
- **1 $$\leq$$ Z $$\leq$$ 10<sup>8</sup>**
- **1 $$\leq$$ y<sub>1</sub>, y<sub>2</sub> $$\leq$$ 10<sup>8</sup>**
- **1 $$\leq$$ m<sub>1</sub>, m<sub>2</sub> $$\leq$$ M**
- **1 $$\leq$$ d<sub>1</sub>, d<sub>2</sub> $$\leq$$ D**
  &nbsp;  
   
#### **Limits**
- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
12 30 1
28
2019 12 10
2020 1 8
```

### Sample Output 0

```
FULL MOON DAY
```

### Sample Input 1

```
5 10 2
2 3
2019 1 1
2019 2 2
```

### Sample Output 1

```
1
```
