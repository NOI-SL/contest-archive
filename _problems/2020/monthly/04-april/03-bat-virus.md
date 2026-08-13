---
title: "Bat Virus"
year: 2020
category: monthly
round: "April 2020"
sortkey: "2-monthly-04-03"
index: 3
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - April 2020"
contest_slug: "noi-2020-apr"
contest_url: "https://www.hackerrank.com/contests/noi-2020-apr"
problem_slug: "bat-virus"
problem_url: "https://www.hackerrank.com/contests/noi-2020-apr/challenges/bat-virus"
---

Neverland is a country with ***N*** cities (indexed from ***0*** to ***N-1***). The cities are connected to each other by a network of ***R*** two-way roads.  
  
Two cities are considered to be neighbors if they’re directly connected by a two-way road.  
  
To an unfortunate turn of events, the country got struck by a mysterious bat virus. Initially (on day ***D<sub>1</sub>***), patients with the virus were reported from some cities in the country. The virus spreads in a weird, but interesting way.
  
Consider a city ***C<sub>0</sub>*** , with ***C<sub>1</sub>*** , ***C<sub>2</sub>*** , ***C<sub>3</sub>*** , ***C<sub>4</sub>*** , ..., ***C<sub>t</sub>*** neighbor cities. On day ***D<sub>i</sub>*** , let’s say there are ***P<sub>0</sub>*** , ***P<sub>1</sub>*** , ***P<sub>2</sub>*** , ***P<sub>3</sub>*** , ***P<sub>4</sub>*** , ..., ***P<sub>t</sub>*** patients corresponding to each city.
Then number of patients in ***C<sub>0</sub>*** on day $$D_{(i+1)} = max( C_0, \frac{C_1}{2}, \frac{C_2}{2}, \frac{C_3}{2}, \frac{C_4}{2}, ..., \frac{C_t}{2})$$  
  
Given the road network and initial conditions of virus, your task is to find the maximum number of bat-virus patients that will be recorded in the country (***P<sub>max</sub>***), and the number of days (***D<sub>max</sub>***) it will take for ***P<sub>max </sub>*** to appear first.

## Input Format

First line contains two space seperated integers ***N*** and ***R***. (Number of Cities, and the number of two-way roads)  
***R*** lines follow, with ***i<sup> th</sup>*** line having two space seperated integers ***S<sub>i</sub>*** and ***E<sub>i</sub>*** , the index of two cities connected by the road ***R<sub>i</sub>*** .  
Next line contains a single integer ***M***, the initial number of cities where the virus appeared.  
***M*** lines follow, with ***j<sup> th</sup>*** of them having two space seperated integers ***C<sub>j</sub>*** and ***P<sub>j</sub>*** , the index of the city, and the number of patients reported respectively.

## Output Format

Two integers, ***D<sub>max</sub>*** and ***P<sub>max</sub>***

## Constraints

- **1 $$\leq$$ N $$\leq$$ 2*10<sup>4</sup>**
- **1 $$\leq$$ R $$\leq$$ 5*10<sup>4</sup>**
- **1 $$\leq$$ M $$\leq$$ 5*10<sup>3</sup>**
- **0 $$\leq$$ S<sub>i</sub>, E<sub>i</sub>, C<sub>j</sub> $$\leq$$ N-1**
- **0 $$\leq$$ P<sub>j</sub> $$\leq$$ 3*10<sup>7</sup>**
- **0 $$\leq$$ i $$\leq$$ R**
- **0 $$\leq$$ j $$\leq$$ M**
- **S<sub>i</sub> $$\neq$$ E<sub>i</sub>**
- A single city can be connected to ***1*** city at minimum and ***N-1*** cities at maximum.  
- There are no isolated cities.  
   
#### **Limits**
- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
6 5
0 1
1 2
2 3
3 4
4 5
2
0 100
4 5
```

### Sample Output 0

```
6 196
```
