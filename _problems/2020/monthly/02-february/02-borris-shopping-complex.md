---
title: "Mr. Borris’s Shopping Complex"
year: 2020
category: monthly
round: "February 2020"
sortkey: "2-monthly-02-02"
index: 2
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - February 2020"
contest_slug: "noi-2020-feb"
contest_url: "https://www.hackerrank.com/contests/noi-2020-feb"
problem_slug: "borris-shopping-complex"
problem_url: "https://www.hackerrank.com/contests/noi-2020-feb/challenges/borris-shopping-complex"
---

In a shopping complex dedicated to **cake** and **pencils**, there are ***M*** shops numbered from ***0*** to ***M-1***. Each shop is either a **cake shop** or a **pencil shop**.

***N*** merchants trade with these shops. Each merchant trades with all (& only) the shops numbered from ***A<sub>i</sub>*** to ***B<sub>i</sub>*** (both inclusive).

Each mechant should pay a fee to Mr. Borris, the owner of the shopping complex for trading with the shops in his shopping complex.

For merchant ***i***, the fee ***F<sub>i</sub>*** is calculated as,  
***F<sub>i</sub>*** = (***number of cake shops he traded with***) x (***number of pencil shops he traded with***)

Mr. Borris knows the shops the merchants are to trade with. (i.e. ***A<sub>i</sub>*** and ***B<sub>i</sub>*** values for all ***i*** are given).

Mr. Borris now has to decide which of the shops are going to be cake shops and which are going to be pencil shops. Place the shops so that the total revenue from the fees (***ΣF<sub>i</sub>***) is maximized. 
(i.e. for each x, (***0 $$<$$ x $$<$$ M-1***) you need to decide whether ***x<sup>th</sup>*** shop is a cake shop or a pencil shop so that ***ΣF<sub>i</sub>*** is maximized.)

Output the maximum revenue Mr. Borris can earn from fees (maximized ***ΣF<sub>i</sub>***)  [modulo](https://en.wikipedia.org/wiki/Modulo_operation) ***10<sup>9</sup>+7***.

## Input Format

First line of the input contains 2 integers, ***M*** and ***N***.  
***N*** lines will follow, with each having 2 integers, ***A<sup>i</sup>*** and ***B<sup>i</sup>***.

## Output Format

One integer.  (maximized ***ΣFi***) modulo ***10<sup>9</sup>+7***.

## Constraints

- **0 $$<$$ M $$<$$ 10<sup>16</sup>**
- **0 $$<$$ N $$<$$ 50000**
- **0 $$\leq$$ A<sup>i</sup> $$\leq$$ B<sup>i</sup> $$\leq$$ M**
  &nbsp;  
   
#### **Limits**
- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
6 2
2 5
0 0
```

### Sample Output 0

```
4
```
