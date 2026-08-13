---
title: "DVD Screensaver"
year: 2026
category: qualifier
round: "Qualifier Round"
sortkey: "1-qualifier-01"
index: 1
max_score: 100
difficulty: "Medium"
contest_name: "NOI 2026 Qualifier Round"
contest_slug: "noi-2026-qualifier-round"
contest_url: "https://www.hackerrank.com/contests/noi-2026-qualifier-round"
problem_slug: "dvd-screensaver"
problem_url: "https://www.hackerrank.com/contests/noi-2026-qualifier-round/challenges/dvd-screensaver"
---

You are watching a classic DVD screensaver bounce around a television screen. The screen is defined on a Cartesian plane bounded by the lines $$x = 0$$, $$x = W$$, $$y = 0$$, and $$y = H$$. 

<img src="{{ "/assets/problems/f551a50c-giphy.gif" | relative_url }}" width="300" alt="DVD Screensaver">


The DVD logo acts as a single point. Initially, at time $$t = 0$$, the logo is located at the bottom-left corner of the screen at exactly $$(0, 0)$$ and is moving towards the North-East direction. 

The logo always travels perfectly along diagonal lines. At any given moment, its path is a line inclined at exactly a 45-degree angle relative to the edges of the screen. In exactly one second, the logo travels along its current diagonal trajectory to the next diagonally adjacent point that has integer coordinates. 

When the logo reaches a boundary of the screen ($$x = 0$$, $$x = W$$, $$y = 0$$, or $$y = H$$), it instantly bounces. A bounce simply means the logo shifts to the perpendicular diagonal trajectory (for example, changing from a North-East to a South-East trajectory if hitting the top boundary), ensuring its path always remains at a 45-degree angle to the edges. If the logo hits exactly in one of the four corners, it reverses its trajectory completely and travels back along the exact same diagonal line it arrived on. Bouncing does not consume time.

Given the dimensions of the screen and a time $$T$$, your task is to calculate the exact integer coordinates of the DVD logo after exactly $$T$$ seconds.

## Input Format

The first line contains a single integer, $$N$$, representing the number of test cases.

Each of the following $$N$$ lines contains three space-separated integers: $$W$$, $$H$$, and $$T$$. These represent the width of the screen, the height of the screen, and the total time in seconds, respectively.

## Output Format

For each test case, output two space-separated integers on a new line representing the final $$X$$ and $$Y$$ coordinates of the logo.

## Constraints

* $$1 \le N \le 10^5$$
* $$2 \le W, H \le 10^9$$
* $$1 \le T \le 10^9$$

### Sample Input 0

```
3
10 8 15
5 5 8
100 100 200
```

### Sample Output 0

```
5 1
2 2
0 0
```
