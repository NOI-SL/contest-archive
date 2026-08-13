---
title: "The Epidemic"
year: 2020
category: monthly
round: "March 2020"
sortkey: "2-monthly-03-03"
index: 3
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - March 2020"
contest_slug: "noi-2020-mar"
contest_url: "https://www.hackerrank.com/contests/noi-2020-mar"
problem_slug: "the-epidemic"
problem_url: "https://www.hackerrank.com/contests/noi-2020-mar/challenges/the-epidemic"
---

An epidemic has out broken in the world and many people are getting infected day by day. Scientists who are studying about this epidemic have already found that this is caused by a virus (not a computer virus) and they have already found the pattern of the growth of this virus.  
For simplicity we will brief the growth pattern as follows.

1. First a virus cell enters human body in ***day 1***
2. This cell grows for ***five*** days
3. After five days (from ***6th*** day onwards) this cell is a ***grown cell***
4. This ***grown cell*** make ***three*** new virus cells ***everyday*** thereafter
5. These new cells grow in a similar way
6. After ***10*** days (from 11th day onwards) the new cells born in day ***6*** are ***grown*** and they also start making more new cells.
7. Assume ***no cells die*** within the period we consider  
  
The pattern of the growth in first ***12*** days is shown in the following table
|                Day              | 1 | 2 | 3 | 4 | 5 | 6 | 7 |  8 |  9 | 10 | 11 | 12 |
|:--------------------------------|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:--:|:--:|:--:|:--:|:--:|
| **Grown Cells**                 | 0 | 0 | 0 | 0 | 0 | 1 | 1 |  1 |  1 |  1 |  4 |  7 |
| **New Born Cells for This Day** | 0 | 0 | 0 | 0 | 0 | 3 | 3 |  3 |  3 |  3 | 12 | 21 |
| **Total Child Cells**           | 1 | 1 | 1 | 1 | 1 | 3 | 6 |  9 | 12 | 15 | 24 | 42 |
| **Total Cells**                 | 1 | 1 | 1 | 1 | 1 | 4 | 7 | 10 | 13 | 16 | 28 | 49 |
  
Predicting the number of virus cells in a patient at a given time is crucial when treating the disease. Since the pattern increases very rapidly after ***10*** days, it is difficult to predict the numbers. Therefore, a computer program is needed to predict the virus cell count in any day.  
  
You are given the number of days(***D***) passed after the patient is infected. You are supposed to predict the number of grown virus cells and child virus cells.

## Input Format

A single integer ***D***, the number of days.

## Output Format

A single integer, the total number of virus cells.

## Constraints

- **1 $$\leq$$ D $$\leq$$ 90**  
  &nbsp;  
   
#### **Limits**
- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
10
```

### Sample Output 0

```
16
```

### Sample Input 1

```
12
```

### Sample Output 1

```
49
```
