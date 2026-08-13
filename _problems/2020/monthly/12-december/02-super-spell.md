---
title: "Super Spell"
year: 2020
category: monthly
round: "December 2020"
sortkey: "2-monthly-12-02"
index: 2
max_score: 100
difficulty: "Easy"
contest_name: "National Olympiad in Informatics Sri Lanka - December 2020"
contest_slug: "noi-2020-dec"
contest_url: "https://www.hackerrank.com/contests/noi-2020-dec"
problem_slug: "super-spell"
problem_url: "https://www.hackerrank.com/contests/noi-2020-dec/challenges/super-spell"
---

Little Ron is struggling in his first year at Hogwarts magic school. Prof. Snape was not happy with his performance. So, he decided to give Ron a small exercise to complete in his mid-year vacation.  

Ron has a collection of ***n*** spells. He has to select **exactly one character** from each spell and make a new spell by concatenating each selected character. From the set of possible spells that can be formulated the spell which is **[lexicographically smallest](https://en.wikipedia.org/wiki/Lexicographic_order)** is called the super spell.  

Ron got to know that he can score more if he can come up with the super spells. As Ron is not good at his studies, he needs your assistance. Help Ron with finding the super spell for each collection of spells.

## Input Format

The first line of input will be a single integer ***m***, the number of spell collections that Ron will be given.  
The next lines will be as follows.  

- For each spell collection, the first line will be **n**, the number of spells in that collection.  
- Next **n** lines will be the spells of that collection.

## Output Format

Output ***m*** lines, a line for each super spell.

## Constraints

- **1 $$\leq$$ m $$\leq$$ 100** 
- **1 $$\leq$$ n $$\leq$$ 1000** 
- The maximum length of any spell in any collection would be 100  
- All the spells will be in lowercase  

#### **Limits**
- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
2
3
asdfsdf
sdfsdfb
sfsdfd
2
xyztxc
pqurstwxe
```

### Sample Output 0

```
abd
ce
```
