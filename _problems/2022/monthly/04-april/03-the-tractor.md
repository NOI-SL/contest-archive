---
title: "The Tractor"
year: 2022
category: monthly
round: "April 2022"
sortkey: "2-monthly-04-03"
index: 3
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - April 2022"
contest_slug: "noi-2022-apr"
contest_url: "https://www.hackerrank.com/contests/noi-2022-apr"
problem_slug: "the-tractor"
problem_url: "https://www.hackerrank.com/contests/noi-2022-apr/challenges/the-tractor"
---

There is a remote controlled tractor in a field. consider the field as a grid of plots, with **n** rows and **m** columns. Some plots of the field can be cultivated and others are empty.

The tractor can move only to the empty plots within the field. The tractor can be instructed to go up, down, left or right (one plot at a time). 

However due to a malfunction every instruction given is processed as follows:

- Next move should not be the one given in the instruction
- Moving to a cultivated plot is restricted.
- If a move is impossible stay in the same plot.

There is a garage somewhere in the field and it has the tools needed to fix the tractor.
Mark the plots in the field where it is possible to move the tractor to the garage within a finite number of instructions if the tractor starts in that plot.

## Input Format

- The first line has no of test cases - $$t$$  .
- Then there will be $$t$$ test cases
    - The first line of each test case has two integers $$n$$ and $$m$$  
    - The $$i$$-th line of the next $$n$$ lines has the description of the $$i$$-th row of the  field. Each row has $$m$$ elements which can be one of three types:
        - '.' — empty 
        - '#' — cultivated 
        - 'L' — garage

## Output Format

After finding the empty plots that the tractor can be forced to the garage, print the field and use a plus symbol ('+') to indicate a plot that the tractor can be forced to the garage after some moves.

## Constraints

- $$1 \le t \le 1000$$
- $$1 \le n, m \le 10^6$$; 
- $$n \cdot m \le 10^6$$
- The field contains exactly one garage. 
- Sum of cells ($$n \cdot m$$) over all testcases doesn't exceed $$10^6$$.

### Sample Input 0

```
4
3 4
....
.L..
....
1 7
...L.#.
1 1
L
4 8
...#....
.....##L
......#.
........
```

### Sample Output 0

```
....
.L..
....
+++L+#.
L
...#++++
.....##L
......#+
......++
```
