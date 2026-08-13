---
title: "Best Pile"
year: 2023
category: monthly
round: "February 2023"
sortkey: "2-monthly-02-05"
index: 5
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - February 2023"
contest_slug: "noi-2023-feb"
contest_url: "https://www.hackerrank.com/contests/noi-2023-feb"
problem_slug: "best-pile"
problem_url: "https://www.hackerrank.com/contests/noi-2023-feb/challenges/best-pile"
---

There is a $$n*m$$ grid with square cells. There are blocks with a sqaure base and an arbitrary integer height $$h$$ on some cells.

Pile of blocks is a set of blocks in which, every block shares a grid cell wall with at least one other block of the set. Therefore, each block must be a part of only one pile.

Output the open surface area of the pile with the highest open surface area.

Notes:
- A part of a surface is considered hidden if it's covered by another block.
- Underside of a block is considered hidden
- Consider the width of a cell as 1 unit and height is also given in this unit

subtasks:
 
- each pile fills only 1 cell - 5 pts
- there is only one pile in the whole grid - 45 pts
- No extra constraints - 50 pts

## Input Format

first line contains two integers $$n$$ and $$m$$
each of next $$n$$ lines contains $$m$$ integers, height $$h$$ of the block in that cell. (0 if the cell is empty)

## Output Format

single integer - maximum found surface area

## Constraints

$$n<10^2$$

$$m<10^2$$

$$h<10^6$$
