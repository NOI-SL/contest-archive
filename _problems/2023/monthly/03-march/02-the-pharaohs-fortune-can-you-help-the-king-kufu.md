---
title: "Mission: Impossible – Dead Reckoning"
year: 2023
category: monthly
round: "March 2023"
sortkey: "2-monthly-03-02"
index: 2
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - March 2023"
contest_slug: "noi-2023-mar"
contest_url: "https://www.hackerrank.com/contests/noi-2023-mar"
problem_slug: "the-pharaohs-fortune-can-you-help-the-king-kufu"
problem_url: "https://www.hackerrank.com/contests/noi-2023-mar/challenges/the-pharaohs-fortune-can-you-help-the-king-kufu"
---

**Ethan Hunt and the IMF team** must track down a terrifying new weapon that threatens all of humanity if it falls into the wrong hands. With control of the future and the fate of the world at stake, a deadly race around the globe begins.

He and his team must generate  **secret words** to encrypt the details of a misson to  locate a terrifying new weapon that poses a threat to all of humanity. The secret words will be used to unlock critical information about the weapon's locations. These **secret words are generated using two words str1 and str2.**

To generate the secret word, **follow the rules**  as below:

1. Match each character in two strings, str1 and str2, one by one. (e=l,t=i,h=s ...)
2. **Similar characters will be grouped together** based on the **equivalence relation: reflexivity, symmetry, and transitivity.**
3. For each character in the word containing classified data D, find the **first most letter alphabetically** in each similar character set from **str1** and **str2**.
4. If a character in **D** is **not present in str1 or str2,** **it remains unchanged** in the secret word.

Your task is to create program that takes three inputs: **str1**, **str2**, and **D**, and returns the **secret word** to complete the mission.


```cpp
Example:
- str1=ethanhunt
- str2=lisafaust    
- l=operationsecret

- Similar character sets : {e,l},{i,t},{a,f,h,s,n}
- Secret word : operaiioaaecrei
```

## Input Format

First two lines contain **str1** and **str2**.

Next line contains **D**.

## Output Format

- Print **the secret word** in the console.

## Constraints

- All the strings contain **lowercase** letters.
- **str1.length==str2.length**
- **1<=** str1.length,str2.length,D.length **<=1000**

### Sample Input 0

```
ethanhunt
lisafaust
operationsecret
```

### Sample Output 0

```
operaiioaaecrei
```

### Sample Input 1

```
underwater
parachutes
gabriel
```

### Sample Output 1

```
gabcial
```
