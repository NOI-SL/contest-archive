---
title: "Hogwarts' Defense Against the Dark Arts"
year: 2023
category: monthly
round: "January 2023"
sortkey: "2-monthly-01-02"
index: 2
max_score: 100
difficulty: "Easy"
contest_name: "National Olympiad in Informatics Sri Lanka - January 2023"
contest_slug: "noi-2023-january"
contest_url: "https://www.hackerrank.com/contests/noi-2023-january"
problem_slug: "hogwarts-3"
problem_url: "https://www.hackerrank.com/contests/noi-2023-january/challenges/hogwarts-3"
---

**Hogwarts School of Witchcraft and Wizardry**, renowned for its education in the magical arts, offers a course in **Defense Against the Dark Arts**. The esteemed author and adventurer, **Gilderoy Lockhart**, has been appointed as the instructor for this course. 

In his first lecture he wants you to memorize the **spells (s)** in a way of a word **pattern (p)**. So with the spell and the word pattern given you have to identify whether they **match or not.** A match means a **complete bijection** between **a letter in the pattern and a word in the spell.** Can you find a way to solve it ?

*In mathematics, a bijection, also known as a bijective function, one-to-one correspondence, or invertible function, is a function between the elements of two sets, where each element of one set is paired with exactly one element of the other set, and each element of the other set is paired with exactly one element of the first set.*[[see more]](https://en.wikipedia.org/wiki/Bijection)

## Input Format

The first line contains **number of test cases n**.

Next **2n lines** contain **p and s for each test case**.

## Output Format

Print **true** or **false** in each line.

## Constraints

**p** contains only **lower case** letters.

**s** contains only **spaces and lower case** letters.

All the words in **s** are seperated by a **single space.**

***1<= p.length <=300***

***1<= s.length <=3000***

### Sample Input 0

```
2
abba
ascendio aguamenti aguamenti ascendio
bbbb
bombardo engorgio engorgio bombardo
```

### Sample Output 0

```
true
false
```

### Sample Input 1

```
2
aeea
ascendio episkey episkey ferula
aeeb
ascendio episkey episkey ferula
```

### Sample Output 1

```
false
true
```
