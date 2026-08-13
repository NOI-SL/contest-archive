---
title: "Win the Quiz"
year: 2021
category: monthly
round: "March 2021"
sortkey: "2-monthly-03-01"
index: 1
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - March 2021"
contest_slug: "noi-2021-mar"
contest_url: "https://www.hackerrank.com/contests/noi-2021-mar"
problem_slug: "win-the-quiz"
problem_url: "https://www.hackerrank.com/contests/noi-2021-mar/challenges/win-the-quiz"
---

Suvin and his friends are participating an IT quiz. There are **Q** number of questions numbered from **1 to Q**. The questions have varying difficulties. 
All the members of Suvin's team can answer any question. But, the time taken to answer a question depends on the difficulty of the question. Assume if one member can solve a question in 1 minute, the other members can solve it within 1 minute as well.    

A question can **only** be solved by **one person**. And **all the questions** must be **solved** to win the quiz. A person can solve **any number of questions**, but that person can only solve **adjacent questions** (questions that are next to each other). Suvin's team can solve the questions in parallel. So, the **total time** taken to solve the quiz is the **total time of the member who spent the most time solving problems**. 
Suvin wants to figure out the best strategy to assign questions to his friends, so that his team can win the quiz by completing it in **least amount of time**.  

Write a program find the **least amount of time** required for Suvin's team to finish the quiz.

## Input Format

The first line of the input has **2** integers **Q** and **T** respectively, separated by a space. The number of questions and the number of teammates.  
Each of the following **Q** lines have a single integer, **D<sub>i</sub>** the number of minutes required to solve the **i<sup>th</sup>** question. There can be questions that can be solved immediately. (0 minutes required)

## Output Format

Output just **one integer**, the **total number of minutes** required to finish the quiz.

## Constraints

- **1 $$\leq$$ Q $$\leq$$ 10<sup>6</sup>**  
- **1 $$\leq$$ T $$\leq$$ 10<sup>3</sup>**  
- **1 $$\leq$$ D<sub>i</sub> $$\leq$$ 10<sup>3</sup>**
  
#### **Limits**
- **Time Limit**: 1s  
- **Memory Limit**: 256MB

### Sample Input 0

```
6 3
4
2
3
7
1
9
```

### Sample Output 0

```
9
```
