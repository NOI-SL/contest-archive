---
title: "String decoder "
year: 2023
category: qualifier
round: "Selection Test"
sortkey: "1-qualifier-07"
index: 7
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - Screening Test 2023"
contest_slug: "noi-2023-selection-test"
contest_url: "https://www.hackerrank.com/contests/noi-2023-selection-test"
problem_slug: "string-decoder-1"
problem_url: "https://www.hackerrank.com/contests/noi-2023-selection-test/challenges/string-decoder-1"
---

One day, as Rob was leisurely strolling through the picturesque campus of UCSC, he stumbled upon an inconspicuous door hidden amidst the towering trees. Intrigued by the air of mystery surrounding it, Rob's curiosity got the better of him, and he couldn't resist exploring what lay beyond. Little did he know that this seemingly ordinary door would transport him into an unexpected adventure. As he stepped through the threshold, the door closed behind him, trapping him inside an unknown world filled with secrets waiting to be unraveled. Now, with no way to return, Rob must summon his wit, courage, and resourcefulness to navigate through the enigmatic corridors and uncover the mysteries that lie within, hoping to find a way back to the familiar world he left behind.
Suddenly he found that there is a mysterious word S written in the door and also some other instrusctions which he later realized that can be used to decode the password from the string. S contains of lower case english letters . and the instructions are in are some operations to shift the characters of the string where each query consist of 3 elements first element represents the starting index of letter and second element represents the ending index of the element and the thrid element represent 'F' or 'B', where uppercase 'F' represents forward and uppercase 'B' represents backwards. According to each query letters should be shifted by one either Forward or Backward Derection. (if 'z' is shifter forward it will be 'a' and if 'a' is shifted backwards it will be 'z').

your task is to process the string according to all the queries and print the final string.

## Input Format

- first line contains string **S**
- second line contains integer T denoting no of queries
- in each of next 3 lines denotes integers x y z where x-start index y-end index z-direction

## Output Format

- print the processed string

## Constraints

- 1<=S.length<=10^4
- 0<= start<=end<s.length
- 1<= no of queries <=1000

### Sample Input 0

```
ucsc                                
2
0 0 F
0 3 B
```

### Sample Output 0

```
ubrb
```
