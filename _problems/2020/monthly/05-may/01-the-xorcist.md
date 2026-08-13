---
title: "The XORcist"
year: 2020
category: monthly
round: "May 2020"
sortkey: "2-monthly-05-01"
index: 1
max_score: 100
difficulty: "Hard"
contest_name: "National Olympiad in Informatics Sri Lanka - May 2020"
contest_slug: "noi-2020-may"
contest_url: "https://www.hackerrank.com/contests/noi-2020-may"
problem_slug: "the-xorcist"
problem_url: "https://www.hackerrank.com/contests/noi-2020-may/challenges/the-xorcist"
---

After a long journey, a treasure hunter finally reaches a cave containing an enormous treasure. Unfortunately for him, he finds out that the cave entrance is guarded by a demon.  
  
The treasure hunter looks through the map for a clue on how to defeat the demon, and finds an encoded message. The message, when decoded can be used as a spell to defeat the demon.  
  
The encoded message has a list of integers followed by another list of pairs of integers. After much experimentation he figures out how to decode the spell using the integers.
 
- The initial list corresponds to an array of integers ***A***.
- Each pair ***(l, r)*** in the following list corresponds to a character in the spell, where the character can be obtained by
	1. Calculating the integer ***n***, where ***n*** is the [**bitwise XOR**](https://en.wikipedia.org/wiki/Bitwise_operation#XOR) of all integers from ***A<sub>l</sub>*** to ***A<sub>r</sub>***
	2. Calculating the character which corresponds to the  [**ASCII code**](https://www.rapidtables.com/code/text/ascii-table.html) given by $$(n\ mod\ 94) + 33$$.
    
Help the treasure hunter defeat the demon.

## Input Format

First line contains a single integer ***N***, the number of elements in the array ***A***.  
Second line contains ***N*** space separated integers, elements of the array ***A***.  
Third line contains a single integer ***K***, the number of characters in the spell.  
***K*** lines follow, each containing a pair of integers ***(l, r)*** which corresponds to a character in the spell.

## Output Format

A single string, the ***spell*** to defeat the demon.

## Constraints

- ***1 $$\leq$$ N,K $$\leq$$ 10<sup>5</sup>***
- ***1 $$\leq$$ A<sub>i</sub> $$\leq$$ 10<sup>9</sup>***
- ***0 $$\leq$$ l $$\leq$$ r $$\leq$$ N***  
   
#### **Limits**
- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
11
20512528 20512567 20512627 20512568 20512630 20512576 20512523 20512581 20512532 20512607 20512540
10
0 1
1 2
2 3
5 6
3 4
4 5
6 7
7 8
8 9
9 10
```

### Sample Output 0

```
HelloWorld
```
