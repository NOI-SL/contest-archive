---
title: "Old Watch"
year: 2023
category: monthly
round: "January 2023"
sortkey: "2-monthly-01-04"
index: 4
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - January 2023"
contest_slug: "noi-2023-january"
contest_url: "https://www.hackerrank.com/contests/noi-2023-january"
problem_slug: "old-watch"
problem_url: "https://www.hackerrank.com/contests/noi-2023-january/challenges/old-watch"
---

When you were younger, you had a _digital_ watch you were very fond of. It had 4 modes you selected with a button that could:

- tell the time in the 24hours format (`0000` to `2359`)
- tell the temperature of your suroundings from `000` to `100`
- tell the current month of the year (`01`to `12`)
- tell the current day of the week (`1` to `7`).

One day while cleaning your room, you find this watch and wonder whether it still works.
The mode the watch is in can be identified by counting the number of digits that are visible **from the right** (leading spaces are important).

- 4 digits means it's in `24hr` mode
- 3 digits means it's in `Temperature` mode
- 2 digits means it's in `Month` mode
- 1 digit means it's in `Day` mode

From the Information given, it's obvious that there are some values that woudn't make sense in each mode(ex : `2567` isn't a valid time for `24hr` even though there are 4 digits). In all such cases, we consider the watch to be in `Broken` mode.

if there are gaps between the digits, it is also considered to be in `Broken` mode(ex: `0 10` is `Broken`). 

If the screen shows anything other than a digit or a space, the watch is considered to be in `Malfunctioning` mode. (\*when a malfunnctioning character is there, it doesn't matter if the digits and spaces make sense or not in any other mode. It will be considered malfunctioning) 

If the screen shows nothing at all, the watch is considered to be in `Dead` mode.

Identify the mode the watch is in for every test case and print it out.

## Input Format

One line containing $$t$$, the number of testcases

followed by $$t$$ lines containing 4 characters each (a character can be a digit from 0 to 9, a space or any other character).

## Output Format

$$t$$ lines each Containing the mode of the given test case

## Constraints

$$1 \lt t \le 100000$$

testcases can have leading spaces(see sample testcase).

### Sample Input 0

```
6
1247
 070
  13
   2
 .10
 1 1
```

### Sample Output 0

```
24hr
Temperature
Broken
Day
Malfunctioning
Broken
```
