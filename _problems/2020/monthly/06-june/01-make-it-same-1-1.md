---
title: "Make It Same"
year: 2020
category: monthly
round: "June 2020"
sortkey: "2-monthly-06-01"
index: 1
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - June 2020"
contest_slug: "noi-2020-jun"
contest_url: "https://www.hackerrank.com/contests/noi-2020-jun"
problem_slug: "make-it-same-1-1"
problem_url: "https://www.hackerrank.com/contests/noi-2020-jun/challenges/make-it-same-1-1"
---

You are given two arrays ***a*** and ***b*** with ***m*** elements. If you can convert ***b*** (array) to ***a*** (array) after doing the operations described below, output **“Yes”** otherwise output **“No”** (**Without quotes**).

1. select an integer ***k*** **(1 $$\leq$$ k $$\leq$$ m/2)**.
2. swap the prefix of length k with the suffix of length ***k***.
3. You can do these operations any number of times(Possibly zero).


For an example if b={1,2,3,4,5,6}

- If you choose k=1, after swapping , b={6,2,3,4,5,1}
- If you choose k=2, after swapping , b={5,6,3,4,1,2}
- If you choose k=3, after swapping , b={4,5,6,1,2,3}

## Input Format

The first line contains one integer ***n*** — the number of test cases.

The first line of each test case contains a single integer ***m*** — nuumber of elements in the arrays.

The second line of each test case contains m integers a<sub>1</sub>, a<sub>2</sub>, ..., a<sub>m</sub> (**1 $$\leq$$ a<sub>i</sub> $$\leq$$ 10000**) — elements of array a.

The third line of each test case contains m integers b<sub>1</sub>, b<sub>2</sub>, ..., b<sub>m</sub> (**1 $$\leq$$ b<sub>i</sub> $$\leq$$ 10000**) — elements of array b.

## Output Format

For each test case, print **"Yes"** (**Without quotes**) if you can convert ***b*** (array) to ***a*** (array). Otherwise print **"No"** (**Without quotes**).

## Constraints

- **1 $$\leq$$ n $$\leq$$ 500**
- **1 $$\leq$$ m $$\leq$$ 1000**
- **1 $$\leq$$ a<sub>i</sub> , b<sub>i</sub> $$\leq$$ 10000**  
   
#### **Limits**
- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
5
2
1 2
2 1
3
1 2 3
1 2 3
3
1 2 4
1 3 4
4
1 2 3 2
3 1 2 2
3
1 2 3
1 3 2
```

### Sample Output 0

```
Yes
Yes
No
Yes
No
```
