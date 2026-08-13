---
title: "R-01's Forest Expedition"
year: 2023
category: monthly
round: "April 2023"
sortkey: "2-monthly-04-02"
index: 2
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - April 2023"
contest_slug: "noi-2023-apr"
contest_url: "https://www.hackerrank.com/contests/noi-2023-apr"
problem_slug: "r-01s-forest-expedition"
problem_url: "https://www.hackerrank.com/contests/noi-2023-apr/challenges/r-01s-forest-expedition"
---

In a dense forest robot named R-01 is assigned to do some specific tasks. The robot was designed to gather data about the forest's ecosystem, including the different species of plants and animals that lived there.

To navigate the dense forest terrain, R-01 was equipped with wheels and a powerful computer system that allowed it to analyze the environment and plan its route accordingly. However, R-01 had a specific task to complete – to reach the other end of the forest to collect data on the endangered species of butterflies that lived there.

The forest was spread over a vast area and was divided into a grid system **(height h x width w)**, which made R-01's task easier. R-01's journey began at the **top-left corner** of the grid, and its destination is the **bottom-right corner.** 

R-01's wheels allowed it to move either **right or down** at any point in time, and it had to make sure it chose the correct direction to avoid getting stuck or lost. 
Your task is to find the **total unique paths** that R-01 can take.

The engineers who devided the forest into grids have ensured that the total possible unique paths are less than or equal to **2 * 1000000000.**


Let **h=4** and **w=6**. The grid into which the forest is divided can be illustrated as follows.

![image]({{ "/assets/problems/c2dd4791-1681623265-d1256f8722-Capture.JPG" | relative_url }})

## Input Format

Two space seperated integers **h** and **w.**

## Output Format

Return an integer representing the number of unique paths

## Constraints

**1 <= h, w <= 100**

### Sample Input 0

```
6 10
```

### Sample Output 0

```
2002
```
