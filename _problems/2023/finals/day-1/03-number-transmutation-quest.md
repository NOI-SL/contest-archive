---
title: "Number Transmutation Quest"
year: 2023
category: finals
round: "Final Round — Day 1"
sortkey: "3-finals-1-03"
index: 3
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka 2023 - Day 1"
contest_slug: "noi-2023-day-1"
contest_url: "https://www.hackerrank.com/contests/noi-2023-day-1"
problem_slug: "number-transmutation-quest"
problem_url: "https://www.hackerrank.com/contests/noi-2023-day-1/challenges/number-transmutation-quest"
---

Once upon a time, in the land of Numeria, there existed a mysterious power known as Matrix Transmutation. Legend had it that this power could transform matrices by rearranging their elements according to a specific set of rules.

In Numeria, there lived a young mathematician named Alex. Known for their exceptional problem-solving skills, Alex was chosen to embark on a quest to master the art of Matrix Transmutation. The ultimate goal of this quest was to transmute a set of matrices into new formations, adhering to the rules of transmutation.

Alex's first challenge was presented by the wise sage of Numeria, who handed them a set of matrices. Each matrix had a unique dimension, denoted by the number of rows ***(R)*** and columns ***(C)***. These matrices were populated with distinct integers ranging from ***1*** to ***RxC***, inclusive.

The task assigned to Alex was to form new matrices, following the rules of Matrix Transmutation. These rules were straightforward but demanded careful arrangement of numbers. According to the rules, if two integers in a matrix shared a **common side** (either horizontally or vertically), they **must not** share a common side in the new matrix.

Eager to prove their skills, Alex studied the matrices intently, pondering over the possible arrangements. With each matrix, they had to devise a new formation that satisfied the rules of transmutation. However, Alex knew that sometimes it might be impossible to achieve a valid arrangement given the constraints.

Alex's journey was filled with multiple test cases, each consisting of a matrix to transmute. The wise sage challenged them with various dimensions, presenting matrices of different sizes. Alex needed to come up with a valid transmutation for each matrix or declare it impossible by outputting ***-1***.

## Input Format

First line contains a single integer ***T*** - the number of test cases

For each test case:

- The first line contains two space-separated integers ***R*** and ***C*** the number of rows and the number of columns in matrix, respectively. 
- Each of the next ***R*** lines contains ***C*** space-separated integers ***a<sub>ij</sub>*** ***(1 $$\leq$$ a<sub>ij</sub> $$\leq$$ RxC)***, the ***j<sup>th</sup>*** integer of the ***i<sup>th</sup>*** row in matrix.

## Output Format

- **1 $$\leq$$ T $$\leq$$ 100**
- **1 $$\leq$$ R,C $$\leq$$ 10<sup>5</sup>**
- Sum of **RxC** over all test cases does not exceed **10<sup>5</sup>**
   
#### **Limits**
- **Time Limit**: 2s
- **Memory Limit**: 256MB

## Constraints

For each test case:

- If it is not possible to construct the matrix following the above rules, output a single integer ***-1***. 
- Otherwise, output ***R*** lines, each containing ***C*** space-separated integers ***b<sub>ij</sub>*** ***(1 $$\leq$$ b<sub>ij</sub> $$\leq$$ RxC)***, representing the elements of the new matrix. Each integer should represent the ***j<sup>th</sup>*** integer of the ***i<sup>th</sup>*** row in the new matrix.

### Sample Input 0

```
1
3 3
1 2 3
4 5 6
7 8 9
```

### Sample Output 0

```
6 1 8
7 5 3
2 9 4
```
