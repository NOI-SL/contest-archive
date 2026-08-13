---
title: "Back to the 90's"
year: 2023
category: qualifier
round: "Selection Test"
sortkey: "1-qualifier-03"
index: 3
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - Screening Test 2023"
contest_slug: "noi-2023-selection-test"
contest_url: "https://www.hackerrank.com/contests/noi-2023-selection-test"
problem_slug: "back-to-the-90s"
problem_url: "https://www.hackerrank.com/contests/noi-2023-selection-test/challenges/back-to-the-90s"
---

In a captivating scenario, Malindu finds himself in a peculiar situation after playing games in the UCSC computer lab. As punishment, he becomes trapped within the virtual realm of a classic 90's game called "Falling Bricks", a game where square bricks fall one after the other  with its retro graphics and nostalgic charm. The game challenges Malindu to guess the maximum height of bricks that he can reach. If he can guess the maximum height, then he will be able to teleport back to the present.
Each brick is dropped into a large box where the left wall acts as the y axis and the floor acts as the x axis. (you can consider the room as 2-D platform). Bricks are fallen from the sky and a square brick can either come to rest on the upper surface of another square brick or on the X-axis. It is important to note that if a square merely brushes against the left or right side of another square, it does not qualify as landing on it. Once the object successfully lands, it becomes immobile and cannot be relocated.

You are given an array of pairs where in each pair the first element denotes left most postion of the brick and second element represents side length of the brick. Brick is dropped with left edge alligned with the x coordinates.

## Input Format

- 
First line contains no of bricks N. 

- 
Next N lines contains integer pairs where first integer denotes left most postion of the i th brick and second integer denotes the side length of the brick.

## Output Format

Print a single integer denoting the maximum height, the bricks can reach.

## Constraints

- **1 <= N <= 1000**
- **1 <= x-axis, y-axis <= $$2 \cdot 10^9$$**
- **1 <= length of a side <= $$10^9$$**

### Sample Input 0

```
3
1 2
2 3
7 3
```

### Sample Output 0

```
5
```
