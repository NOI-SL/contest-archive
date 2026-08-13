---
title: "Chairs and Distancing: The Hotel Del Luna Case"
year: 2023
category: qualifier
round: "Selection Test"
sortkey: "1-qualifier-06"
index: 6
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - Screening Test 2023"
contest_slug: "noi-2023-selection-test"
contest_url: "https://www.hackerrank.com/contests/noi-2023-selection-test"
problem_slug: "chairs-and-distancing-the-hotel-del-luna-case"
problem_url: "https://www.hackerrank.com/contests/noi-2023-selection-test/challenges/chairs-and-distancing-the-hotel-del-luna-case"
---

During the past covid-19 pandemic, people were instructed to keep at least 1m apart. Consider the following incident, which occurred during the period. A hotel called **"Hotel del Luna"** features a seating area for guests who have checked in. Seating laws at the time stated that a person could not sit on a chair if there was someone to the **left, right, upper left, or upper right.** He can, however, sit if no one is **directly in front of or behind** him. Some of the seats were ruined one day due to heavy rain.

You’re requested to find whether the seating of guests are possible when the **number of guests  G** and the seating arrangement is given by **S number of strings** representing a matrix.
In the distribution of seats,the **broken seats** are denoted by **“*”** and the good ones are denoted by  **“+”**.

Note that the guests can’t sit on the damaged chairs.

## Input Format

The first line contains an integer **T** denoting the number of **testcases**.

For each test case line containing two space seperated integers indicates the **number of guests G** and the **number of strings S.**

Next **S lines** contain strings denoting the seating pattern.

## Output Format

Print **"YES" or "NO"** in seperate lines.


**Explanation**

Given below is a correct way of seating. 

Yellow L shapes denote good chairs and red symbols denote broken ones. A block with the emoji and L shape denote a valid way of seating.

[link to the seating image](https://ibb.co/sjWBxdL)

[link to the directions of seating positions relative to a person](https://ibb.co/Zxxczwy)

## Constraints

Seats are denoted only by **+** or ***** .

**1 <= S <= 8**

**1 <=  S[i].length()  <= 8**

### Sample Input 0

```
3
3 4
*+**+*
+****+
*+**+*
5 10
*+++*
+*+*+
++*++
+*+*+
*+++*
3 6
*+**+*
+****+
*+**+*
```

### Sample Output 0

```
YES
YES
NO
```
