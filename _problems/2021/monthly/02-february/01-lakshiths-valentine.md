---
title: "Lakshith's Valentine"
year: 2021
category: monthly
round: "February 2021"
sortkey: "2-monthly-02-01"
index: 1
max_score: 100
difficulty: "Easy"
contest_name: "National Olympiad in Informatics Sri Lanka - February 2021"
contest_slug: "noi-2021-feb"
contest_url: "https://www.hackerrank.com/contests/noi-2021-feb"
problem_slug: "lakshiths-valentine"
problem_url: "https://www.hackerrank.com/contests/noi-2021-feb/challenges/lakshiths-valentine"
---

Lakshith is planning to celebrate the valentine’s day with his girlfriend. He wants to make a bouquet of flowers for his girlfriend. But the problem is, there are different types of flowers he can pick from. And he also doesn’t want to include more than one flower from each type. Now, Lakshith wants to figure out how many different types of bouquets he can create using the available flowers. Lakshith is seeking your help to find that.  

#### **Example:**
The flower shop has 6 types flowers. Carnations(**C**), Daisies(**D**), Gardenias(**G**), Lilies(**L**), Orchids(**O**) and Roses(**R**). Lakshith wants to create bouquets with **4** flowers in each bouquet.  
So, he can create **15** different bouquets.  
```
1.	C D G L
2.	C D G O
3.	C D G R
4.	C D L O
5.	C D L R
6.	C D O R
7.	C G L O
8.	C G L R
9.	C G O R
10.	C L O R
11.	D G L O
12.	D G L R
13.	D G O R
14.	D L O R
15.	G L O R
```

Given the number of different types of flowers available(***T***), and the number of flowers Lakshith wants to include in his bouquet(***F***), you have to find and output the number of different types of flower bouquets you can create.

Following formula can be used to calculate the different number of bouquets: 

$$\frac{1 \times 2 \times 3 \times ... (T - 1) \times T }{(1 \times 2 \times 3 \times ... (F - 1) \times F) \times (1 \times 2 \times 3 \times ... (T - F - 1) \times (T - F))}$$

For example when ***T = 6*** and ***F = 4***  
$$\frac{1 \times 2 \times 3 \times 4 \times 5 \times 6 }{(1 \times 2 \times 3 \times 4) \times (1 \times 2)} = \frac{720}{24 \times 2} = \frac{720}{48} = 15$$

When ***T = 6*** and ***F = 6***  
$$\frac{1 \times 2 \times 3 \times 4 \times 5 \times 6 }{(1 \times 2 \times 3 \times 4 \times 5 \times 6)} = \frac{720}{720} = 1$$

When ***T = 6*** and ***F = 1***  
$$\frac{1 \times 2 \times 3 \times 4 \times 5 \times 6 }{(1 \times 2 \times 3 \times 4 \times 5) \times 1} = \frac{720}{120} = 6$$

## Input Format

A single line, with two space separated integers, ***T*** & ***F***, the number of types of flowers, and the number of flowers in a bouqet.

## Output Format

Output a single integer, the number of different types of flower bouquets.

## Constraints

- **1 $$\leq$$ T $$\leq$$ 20**  
- **1 $$\leq$$ F $$\leq$$ T**  
  
#### **Limits**
- **Time Limit**: 1s  
- **Memory Limit**: 256MB

### Sample Input 0

```
6 4
```

### Sample Output 0

```
15
```

### Sample Input 1

```
6 6
```

### Sample Output 1

```
1
```

### Sample Input 2

```
6 1
```

### Sample Output 2

```
6
```
