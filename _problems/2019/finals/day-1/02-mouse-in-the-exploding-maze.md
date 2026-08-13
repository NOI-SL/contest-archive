---
title: "Mouse in the Exploding Maze "
year: 2019
category: finals
round: "Final Round — Day 1"
sortkey: "3-finals-1-02"
index: 2
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - Day 1"
contest_slug: "noi-2019-day-1"
contest_url: "https://www.hackerrank.com/contests/noi-2019-day-1"
problem_slug: "mouse-in-the-exploding-maze"
problem_url: "https://www.hackerrank.com/contests/noi-2019-day-1/challenges/mouse-in-the-exploding-maze"
---

There is a mouse stuck inside a maze. You have to write a program to help the mouse to exit the maze given the maze, starting position of the mouse and exit locations.

At the start, the mouse is in the starting cell. Mouse spends **a minute** in a cell before moving. At the end of every minute the mouse can decide to either **stay** in the current cell or **move** to a neighboring (**up**, **right**, **down**, **left**) cell. The motion happens instantly, and it’ll stay the next minute in the next cell. The mouse can not step outside the maze and also mouse cannot step into a blocked cell.

But unlike the previous maze, this maze have cells with **bombs** in them!  The mouse **can’t stay** in a cell that has a **bomb** when the bomb is **ON**, but the mouse **can stay** in a cell with a bomb when the bomb is **OFF**. The bombs that are **ON** will be **turned off** in the **next step** by the bomb squad. But the problem is that terrorists will **turn all the switched off bombs ON** in **every step** as well. So they just keep **turning ON and OFF, every minute;** the change happens at the end of the **minute instantly**.

A maze is a two-dimensional grid having **R** rows and **C** columns, having **RxC** cells inside it. Each cell can either be a **free cell,** a **blocked cell** or a **cell with a bomb** that can be in either **ON state** or **OFF state.** The mouse cannot go into a blocked cell or a cell that has a bomb in the ON state. Starting cell and exit cells will always be free cells without any bombs, so that the mouse can go.

Find the **shortest time** for the mouse to move into one of the exit cells.

## Limits  
Time Limit: 1s  
Memory Limit: 256MB

## Input Format

The first line of the input has **2** integers **R** and **C** respectively, separated by a space. **R** is the number of rows in the maze and **C** is the number of columns in the maze. 
Next **R** lines have **C** characters each representing the **RxC gird**. Each character represents a cell. Each character can be one of the following representing:

- **“.”** (dot/full stop) - An empty cell
- **“#”** - A blocked cell
- **“S”** (capital s) - The starting cell
- **“E”** (capital e) - An exit cell
- **“N”** (capital n) - A Bomb that is ON
- **“F”** (capital f) - A Bomb that is OFF

## Output Format

Output just **one integer** representing your answer, the **shortest time in minutes** for the mouse to reach from starting cell to one of the exit cells.  
If the mouse can’t reach an exit then output **-1**.

## Constraints

- **1 $$\leq$$ R, C $$\leq$$ 20**

### Sample Input 0

```
6 10
....S#E...
...###....
F..#E.....
#N###..###
.......#..
.......#..
```

### Sample Output 0

```
15
```

### Sample Input 1

```
6 10
.NN.S#....
.NN###....
.NN#E#....
#.####.###
.......#..
.........E
```

### Sample Output 1

```
-1
```
