---
title: "Turing Baths"
year: 2020
category: monthly
round: "December 2020"
sortkey: "2-monthly-12-04"
index: 4
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - December 2020"
contest_slug: "noi-2020-dec"
contest_url: "https://www.hackerrank.com/contests/noi-2020-dec"
problem_slug: "turing-baths"
problem_url: "https://www.hackerrank.com/contests/noi-2020-dec/challenges/turing-baths"
---

Mr. Turing (the computer scientist who helped allies win [the second world war](https://www.youtube.com/watch?v=nuPZUUED5uk) and proposed [a universal model for computers](https://www.youtube.com/watch?v=dNRDvLACg5Q)) has a friend name Mr. Grinch, who has an obsession with personal hygiene. For the sake of this question, we will assume that Mr. Grinch has a limited number of activities.  

- **G** : Go into the bathroom (after opening the bathroom door)  
- **G** : Go out of the bathroom (close the bathroom door on his way out)  
- **O** : Switch on (start) the shower  
- **F** : Switch off (stop) the shower  
- **S** : Apply shampoo  
- **C** : Apply conditioner  
- **D** : Dry his hair  
- **A** : Buy a refill for shampoo bottle  
- **B** : Buy a refill for conditioner botttle  

Mr. Grinch has some weird personal rules. He would never apply conditioner without washing away shampoo. He would never leave the house without checking if he closed the shower and bathroom door. Even though his conditioner works for both wet and dry hair, he would never dry his hair with anything on it. It would also be quite stupid to try drying his hair with a towel under the shower.  

His Shampoo and Conditioner bottles can hold enough for two usages each. While he can take his towel out of the bathroom to dry his hair, he doesn't want to take shampoo or conditioner bottles outside and make a mess.  

Mr. Turing will be given a sequence of actions. He has to figure out if that is something Mr. Grinch would do. To do that, he wants to write a computer program and he's seeking your help to do it.  

In the start, the person doing the actions is outside the bathroom. Both shampoo and conditioner bottles are filled and the shower is switched (stopped) off.

## Input Format

The first line contains a single integer ***T***, the number of test cases.  
***2T*** lines will follow, with ***2*** lines for each testcase.  

- The first line contains a single integer ***N***, the number of characters in the sequence.  
- The second line contains a string of ***N*** charcters, with ***i<sup>th</sup>*** of them being ***S<sub>i</sub>***, the actions done by the person.

## Output Format

The output should have ***T*** lines, one line per testcase.  

- If those were done by Mr. Grinch, print ***'Y'***
- If not, print ***'N'&nbsp;*** followed by the number of operations that can be done by Mr. Grinch.

## Constraints

- **1 $$\leq$$ T $$\leq$$ 1000** 
- **1 $$\leq$$ N $$\leq$$ 1000**
- ***S<sub>i</sub>*** is one of these values (***'G'***, ***'O'***, ***'F'***, ***'S'***, ***'C'***, ***'D'***, ***'A'***, ***'B'***)

#### **Limits**
- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
3
9
GOFSOFDCG
6
GSOCFD
7
GSCOFDG
```

### Sample Output 0

```
Y
Y
N 2
```

### Sample Input 1

```
3
12
GOSGGCSDFSOG
12
GOSGGCSFDSOG
18
GOSGGCSFDGAGSOCCFD
```

### Sample Output 1

```
N 7
N 9
N 15
```
