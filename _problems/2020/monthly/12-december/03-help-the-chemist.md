---
title: "Help the Chemist"
year: 2020
category: monthly
round: "December 2020"
sortkey: "2-monthly-12-03"
index: 3
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - December 2020"
contest_slug: "noi-2020-dec"
contest_url: "https://www.hackerrank.com/contests/noi-2020-dec"
problem_slug: "help-the-chemist"
problem_url: "https://www.hackerrank.com/contests/noi-2020-dec/challenges/help-the-chemist"
---

Mr. Rasayan is a chemist researching large molecules (when atoms are bound together molecules are formed). His recent researches include samples that have many molecules with varying lengths and he is interested in knowing the number of atoms in a molecule of each sample. Each sample consists of several molecules.  

Unfortunately, the instruments can only detect bonds and not atoms. (Bonds are the attraction between two nearby atoms that binds the two atoms). You are required to help Mr. Rasayan by counting the number of atoms in each molecule of a sample.  

Since neither chemist nor you can identify the atoms, the instrument is using a special numbering to each single atom. Each atom in the sample is given a number between ***0-1000***. Note that no two atoms are given the same number even if they are the same type. In addition, there are no atoms for some numbers between ***0-1000***.  

You are given the bonds between the atoms as pairs of numbers (***a<sub>i</sub>***, ***b<sub>i</sub>***) such that ***a<sub>i</sub>***, ***b<sub>i</sub>*** are integers from ***1-1000***. You are required to count the number of molecules and the number of atoms in each molecule.

## Input Format

First-line contains an integer ***M***, number of bonds detected by the instrument.   
***M*** lines follow, with the ***i <sup>th</sup>*** of them having two integers, ***a<sub>i</sub>*** and ***b<sub>i</sub>***, denoting the bond between atom ***a<sub>i</sub>*** and ***b<sub>i</sub>***.

## Output Format

First-line contains ***T***, Total number of molecules in the sample.  
The next ***T&nbsp;*** lines should output the atoms in each molecule sorted in ascending order.

## Constraints

- **1 $$\leq$$ M $$\leq$$ 10<sup>4</sup>**  
- **0 $$\leq$$ a<sub>i</sub>, b<sub>i</sub> $$\leq$$ 10<sup>4</sup>**  
   
#### **Limits**
- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
6
1 2
1 3
1 4
1 5
10 12
12 14
```

### Sample Output 0

```
2
3
5
```

### Sample Input 1

```
6
1 2
1 3
1 4
1 5
10 12
12 14
```

### Sample Output 1

```
2
3
5
```
