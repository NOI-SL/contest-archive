---
title: "King Rawana’s Palace"
year: 2019
category: qualifier
round: "Selection Test"
sortkey: "1-qualifier-02"
index: 2
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - Screening Test"
contest_slug: "noi-2019-selection-test"
contest_url: "https://www.hackerrank.com/contests/noi-2019-selection-test"
problem_slug: "king-rawanas-palace"
problem_url: "https://www.hackerrank.com/contests/noi-2019-selection-test/challenges/king-rawanas-palace"
---

Kamal is a historian looking for King Rawana's Palace. According to the ancient texts, there are said to be an **_N_** number of gates, each protected by a puzzle. Kamal has found the first entrance and is asking for your help to figure out how to solve these puzzles.

In each gate there is a grid of **_2 columns_** and **_R rows_**. The first row has two numbers **S1** and **S2** in the first and second column respectively. The numbers in all other rows is the next greater natural number to the number directly above.

On top of each gate there are **_2 numbers_**, **_D1_** & **_D2_**. Near the gate there are **_4 piles_** of puzzle pieces. Each puzzle piece has a word on it. According to the ancient text you must fill each cell with a puzzle piece based on the following rules.

   1. **If the number in the cell is divisible by D1**, it should be filled with a piece from the first pile.
   2. **If the number in the cell is divisible by D2**, it should be filled with a piece from the second pile.
   3. **If the number in the cell is divisible by both D1 & D2**, it should be filled with a piece from the third pile.
   4. **If the cell cannot be filled with a piece from the first 3 piles**, it should be filled with a piece from the fourth pile.

Given the **_5 numbers_**, **_S1_**, **_S2_**, **_R_**, **_D1_** and **_D2_** and the words in each **_4 types_** of puzzle pieces, you must write a program to print the solution to the puzzle.

## Input Format

First line contains a single integer, **_N_**.
**_N_** lines follow, each with **_5 integers_** (**_S1_**, **_S2_**, **_R_**, **_D1_**, **_D2_** respectively), followed by a space and **_4 words_**, each separated by a space (words on the puzzle pieces on each pile, respectively).

## Output Format

For each gate print ***R*** lines - the solution for the puzzle.
Each line should contain two space separated words.

## Constraints

- ***1 $$\leq$$ N $$\leq$$ 2000***
- ***1 $$\leq$$ S1, S2 $$\leq$$ 10<sup>8</sup>***
- ***1 $$\leq$$ R $$\leq$$ 100***
- ***1 $$\leq$$ D1 $$\lt$$ D2 $$\leq$$ 10<sup>8</sup>***

### Sample Input 0

```
3
1 45 5 3 5 Fizz Buzz FizzBuzz Nil
4 13 10 2 7 Ba Bi Be Bu
49 23 5 5 10 Oong Greeng Kattu Eswah
```

### Sample Output 0

```
Nil FizzBuzz
Nil Nil
Fizz Nil
Nil Fizz
Buzz Nil
Ba Bu
Bu Be
Ba Bu
Bi Ba
Ba Bu
Bu Ba
Ba Bu
Bu Ba
Ba Bi
Bu Ba
Eswah Eswah
Kattu Eswah
Eswah Oong
Eswah Eswah
Eswah Eswah
```
