---
title: "Run, Barry, Run!"
year: 2022
category: monthly
round: "May 2022"
sortkey: "2-monthly-05-02"
index: 2
max_score: 100
difficulty: "Easy"
contest_name: "National Olympiad in Informatics Sri Lanka - May 2022"
contest_slug: "noi-2022-may"
contest_url: "https://www.hackerrank.com/contests/noi-2022-may"
problem_slug: "run-barry-run-2"
problem_url: "https://www.hackerrank.com/contests/noi-2022-may/challenges/run-barry-run-2"
---

You are Barry Allen - the fastest man alive. You need to travel back in time to prevent a major catastrophe from taking place. You can only do this by opening up a Time Rift. A Time Rift will open up only if you achieve a very fast speed.

Looking around, you notice multiple terrains. Each terrain consists of slopes and plains. After running around the world millions of times, you know the gains in speed (in machs) you can achieve running down any given slope and the losses in speed after running up one. It's plain as day (pun intended) that there is no speed to be gained or lost running across a plain.

You have examined each terrain as ***N*** number of blocks. Each block has a value which is given as,

- a positive number representing the gain in speed running down a slope, 
- a negative number representing the loss incurred running up a given slope, and 
- 0 to represent a plain


After starting your run at any point of your choosing, what is the maximum speed you can reach **at the end of the terrain?** Choose where you start wisely.

## Input Format

First line contains the number of test cases ***T***.

For each of the ***T*** test cases,

- First line contains integer ***N***, denoting the number of blocks in the terrain.
- The next line contains ***N*** space seperated ***a<sub>i</sub>*** denoting the slope or plain.

## Output Format

- Print ***T*** lines.
- For every test case, print the maximum speed you gain.

## Constraints

- 1 $$\leq$$ ***T*** $$\leq$$ 10
- 1 $$\leq$$ ***N*** $$\leq$$ 10<sup>6</sup>
- -10<sup>7</sup> $$\leq$$ ***a<sub>i</sub>*** $$\leq$$ 10<sup>7</sup>
- Note that maximum speed doesn't exceed 10<sup>9</sup>

### Sample Input 0

```
2
3
0 3 -1
5
2 3 -4 1 -2
```

### Sample Output 0

```
2
0
```
