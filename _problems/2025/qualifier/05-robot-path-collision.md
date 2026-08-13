---
title: "robot-path-collision"
year: 2025
category: qualifier
round: "Qualifier Round"
sortkey: "1-qualifier-05"
index: 5
max_score: 100
difficulty: "Medium"
contest_name: "NOI 2025 Qualifier Round"
contest_slug: "noi-2025-qualifier-round"
contest_url: "https://www.hackerrank.com/contests/noi-2025-qualifier-round"
problem_slug: "robot-path-collision"
problem_url: "https://www.hackerrank.com/contests/noi-2025-qualifier-round/challenges/robot-path-collision"
---

A robot is placed on an infinite 2D grid at coordinates `(0,0)` facing north. You are given `N` commands of three possible types:

1. `MOVE x` — The robot moves forward `x` steps in the direction it is currently facing.
2. `LEFT` — The robot turns left 90 degrees (counterclockwise) without moving from its spot.
3. `RIGHT` — The robot turns right 90 degrees (clockwise) without moving from its spot.

Your task is to determine if the robot’s path ever crosses itself. Formally, the path crosses itself if the robot visits any grid cell more than once at any point during the entire sequence of commands.

-   If the path does cross itself, print `YES`.
-   If it never crosses itself, print `NO`.

Important Details and Examples:

-   The robot starts at position `(0,0)` and that cell is considered visited at the beginning.
-   A crossing occurs if at any point, the robot steps onto a grid cell that has already been visited.
-   Turning left or right does not change the robot’s coordinates—only its direction.

## Input Format

A single integer $$N$$ — the number of commands.

Followed by $$N$$ lines, each describing a command:

-   `MOVE x` where $$x$$ is a positive integer, or
-   `LEFT`
-   `RIGHT`

## Output Format

Print `YES` if the robot’s path ever crosses itself, or `NO` otherwise.

## Constraints

-   $$1 \le N \le 10^4$$ (number of commands)
-   For MOVE x commands, $$1 \le x \le 100$$
-   The robot starts at $$(0,0)$$ facing north.
-   No other commands appear besides MOVE, LEFT, and RIGHT.

### Sample Input 0

```
4
MOVE 3
LEFT
MOVE 2
RIGHT
```

### Sample Output 0

```
NO
```
