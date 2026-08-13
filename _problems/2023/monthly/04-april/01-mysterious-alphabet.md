---
title: "Mysterious Alphabet"
year: 2023
category: monthly
round: "April 2023"
sortkey: "2-monthly-04-01"
index: 1
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - April 2023"
contest_slug: "noi-2023-apr"
contest_url: "https://www.hackerrank.com/contests/noi-2023-apr"
problem_slug: "mysterious-alphabet"
problem_url: "https://www.hackerrank.com/contests/noi-2023-apr/challenges/mysterious-alphabet"
---

Once upon a time, in the ancient city of Babylon, there lived a wise scholar named Eshnunna. Eshnunna was renowned throughout the land for his incredible knowledge of language and grammar. People came from far and wide to seek his advice on matters of speech and writing.

One day, a group of young students came to Eshnunna seeking his guidance. They had been studying the ancient texts of the Sumerians and were unsure if a particular sentence they had come across was grammatically correct.

In language of Sumerians it's quite simple to identify weather a sentence is valid , in Sumerian language there is no grammer you can you words of the alphabet as much as you want and in anyorder. (there can be any number of spaces in between , at the end )

Here your task is to determine weather a sentence is correct according to the language of Sumerians.In Sumerian language a letter can be a string. And a word is made concatenating one or more letters

## Input Format

First line contains integer pair N and T , wher N is the number of strings in alphabet and T is no of sentences to check.
Next N lines contains letters of the alphabet (in this language letter is a string).
Next T lines contains sentences (string ) to be checked weather its valid or not.

## Output Format

Print T lines denoting weather each given sentece is correct or not.
If correct print "TRUE" else print "FALSE"

## Constraints

```cpp
0<<T<60.
0<N<60
0<length(N[i])<20
0<length(T[i])<20
```

### Sample Input 0

```
3 3
ucsc
acm
2023
ucscucsc acm 20232023
20232023
acmacmucsc20
```

### Sample Output 0

```
TRUE
TRUE
FALSE
```
