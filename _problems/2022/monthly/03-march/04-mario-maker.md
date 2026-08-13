---
title: "Mario Maker"
year: 2022
category: monthly
round: "March 2022"
sortkey: "2-monthly-03-04"
index: 4
max_score: 100
difficulty: "Hard"
contest_name: "National Olympiad in Informatics Sri Lanka - March 2022"
contest_slug: "noi-2022-mar"
contest_url: "https://www.hackerrank.com/contests/noi-2022-mar"
problem_slug: "mario-maker"
problem_url: "https://www.hackerrank.com/contests/noi-2022-mar/challenges/mario-maker"
---

You are building a Super Mario game with your friend Luigi. You are in-charge of character design while Luigi is in-charge of world-building. However, Luigi suddenly falls sick and is unable to move! You have to get the game out before GameCon or your initial investment will all go to waste!

You have no choice but to complete the half-baked world Luigi left behind. Luigi has left you a note on the day before he was hospitalized. The note says,

"All you have to do is to add the bricks where necessary. Each level contains an ***N*** number of brick columns. At most ***K*** new bricks can be added to each column, each on top of the other. Two consecutive columns should have at least a single newly laid brick in each column, sharing a common side. Bricks added to the first and last columns should either touch the ground or touch a brick placed by Luigi. The maximum gap you can leave between new bricks and the initial bricks (or the ground) in a column is ***K-1***. Follow these instructions carefully! My masterpiece is in your hands!"

You figure that it might be much easier to write a program that tests whether it is possible to add bricks to a given level as specified by Luigi. Given ***N***, ***K***, and an array ***A*** of length ***N***, have the program output whether it is possible for you to add more bricks to a given level.

## Input Format

- The first line contains a single integer ***T*** denoting the number of levels.
- The first line of each level contains two integers ***N***, and ***K*** separated by a space.
- Second line of each test case contains a list of ***N*** integers, corresponding to the array **A**, separated by spaces.

## Output Format

- Print **“YES”** if it’s possible to lay out the bricks as specified by Luigi. **“NO”** if it is impossible.

## Constraints

- 1 $$\leq$$ ***T*** $$\leq$$ 10<sup>4</sup> 
- 2 $$\leq$$ ***N*** $$\leq$$ 2x10<sup>5</sup> 
- 2 $$\leq$$ ***K*** $$\leq$$ 10<sup>8</sup> 
- 0 $$\leq$$ ***A<sub>i</sub>*** $$\leq$$ 10<sup>8</sup>

### Sample Input 0

```
3
6 3
0 0 2 5 2 2
2 3
0 2
3 2
3 0 2
```

### Sample Output 0

```
YES
YES
NO
```
