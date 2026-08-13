---
title: "Help Alina!"
year: 2023
category: monthly
round: "February 2023"
sortkey: "2-monthly-02-03"
index: 3
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - February 2023"
contest_slug: "noi-2023-feb"
contest_url: "https://www.hackerrank.com/contests/noi-2023-feb"
problem_slug: "decode-and-multiply"
problem_url: "https://www.hackerrank.com/contests/noi-2023-feb/challenges/decode-and-multiply"
---

Enter the world of Alina Starkov, the ingenious Sun Summoner, who has unearthed a long-forgotten script belonging to none other than the infamous Shadow Summoner, General Kirigan. What mysteries lie within this enigmatic text, filled with a bewildering string of **symbols, characters, and numbers?**

But fear not, dear reader, for Alina's sharp mind and astute intellect have identified the **numbers as the key** to the Shadow Summoner's lockers, harboring his deepest, darkest magic. Yet, a puzzle still remains - **each number must be multiplied by another in the script** and a **single script** contains **two lines (s1 and s2)**.Will you help Alina crack the code and uncover the secrets of Kirigan's lockers?

So, what are you waiting for? Step into the world of Alina Starkov and unlock the hidden magic within!

## Input Format

You are given two strings **s1** and **s2**.

First line contains **s1** and the second line contains **s2**.

## Output Format

Output a **string** containing the multiplication of the two numbers in each string.


**Explanation**
```c
/*
2$u$c#s%c*a%c$m0.2!3
#3$4%5&*
  
	2023 = number in --> s1
	345 = number in -->s2
	2023*345	
   
697935
*/ 
```

## Constraints

**1 <= s1.length, s2.length <= 200**

Both **s1** and **s2** **do not contain any leading zero** after removing unnessasary characters, **except the number 0 itself.**

There won't be strings like "@$a0%2f23"

### Sample Input 0

```
da1d2d5
^$4&5^6dadwsfa
```

### Sample Output 0

```
57000
```
