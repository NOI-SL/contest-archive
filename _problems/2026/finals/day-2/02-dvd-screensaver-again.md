---
title: "DVD Screensaver (Again)"
year: 2026
category: finals
round: "Final Round — Day 2"
sortkey: "3-finals-2-02"
index: 2
max_score: 100
difficulty: "Medium"
contest_name: "noi-2026-day-2"
contest_slug: "noi-2026-day-2"
contest_url: "https://www.hackerrank.com/contests/noi-2026-day-2"
problem_slug: "dvd-screensaver-again"
problem_url: "https://www.hackerrank.com/contests/noi-2026-day-2/challenges/dvd-screensaver-again"
---

During the qualifier round, you spent hours watching a classic DVD screensaver bounce around a television screen. Watching a single logo bounce forever got boring, so you decided to make things more interesting. Now, you can launch multiple DVDs, each with its own assigned color (not necessarily different).

<img src="{{ "/assets/problems/f551a50c-giphy.gif" | relative_url }}" width="300" alt="DVD Screensaver">

The screen is a rectangle with integer coordinates from $$(0,0)$$ to $$(N,M)$$, inclusive. Every point with integer coordinates on this grid initially has color $$0$$.

A DVD logo is treated as a single point. When a DVD is launched, it starts from an integer coordinate $$(x,y)$$ **that lies exactly on at least one boundary of the screen** ($$x = 0$$, $$x = N$$, $$y = 0$$, or $$y = M$$) and moves in one of the four diagonal directions:


* `1`: North-East $$(x+1, y+1)$$
* `2`: North-West $$(x-1, y+1)$$
* `3`: South-East $$(x+1, y-1)$$
* `4`: South-West $$(x-1, y-1)$$

The logo moves perfectly along its diagonal path. As it arrives at any integer coordinate point (including its starting point), it paints that point with its assigned color. If a point is traversed by multiple logos, its color is overwritten by the most recent traversal.

When the logo reaches a boundary of the screen, it instantly bounces. A bounce simply means the logo shifts to the perpendicular diagonal trajectory (for example, changing from a North-East to a South-East trajectory if hitting the top boundary $$y = M$$), ensuring its path always remains at a 45-degree angle to the edges. If the logo hits exactly in one of the four corners, it reverses its trajectory completely and travels back along the exact same diagonal line it arrived on. 

We track the logo by the number of boundary bounces it completes. A bounce is counted the moment the logo touches any boundary line. **Note that the logo's initial starting position on a boundary does not count as a bounce.** (Touching a corner during its travel counts as exactly one bounce).

You are given $$Q$$ queries and you must process them in the given order. There are two types of queries:

* **Type 1 (Launch):** `1 x y d B C` — A DVD logo of color $$C$$ is launched from integer coordinates $$(x, y)$$ in direction $$d$$. It travels until it completes exactly $$B$$ bounces, at which point it stops. 
* **Type 2 (Inspect):** `2 x y` — Output the current color of the integer coordinate point $$(x, y)$$.

## Input Format

The first line contains three space-separated integers $$N$$, $$M$$, and $$Q$$, representing the screen dimensions and the number of queries.

The next $$Q$$ lines each describe a query in the format specified above.

* If the query is of Type 1, it contains 6 space-separated integers: `1 x y d B C`
* If the query is of Type 2, it contains 3 space-separated integers: `2 x y`

## Output Format

For each Type 2 query, print a single integer on a new line representing the current color of the queried point.

## Constraints

* $$2 \le N, M \le 10^5$$
* $$1 \le Q \le 10^5$$
* $$0 \le x \le N$$
* $$0 \le y \le M$$
* For all Type 1 queries, either $$x = 0$$, $$x = N$$, $$y = 0$$, or $$y = M$$ is guaranteed to be true.
* $$d \in \{1, 2, 3, 4\}$$
* $$1 \le B \le 10^9$$
* $$1 \le C \le 10^9$$

### **Subtasks**

**Subtask 1 (11 points)**

* $$N, M, Q, B \le 200$$

**Subtask 2 (14 points)**

* $$N, M \le 10^5$$
* $$Q \le 2000$$
* The total number of squares visited across all Type 1 queries does not exceed $$2 \times 10^6$$.

**Subtask 3 (20 points)**

* $$N = M$$ (The grid is a square)

**Subtask 4 (22 points)**

* For all Type 1 queries, $$C = 1$$ (All launched DVDs are the exact same color)

**Subtask 5 (33 points)**

* No additional constraints.

### Sample Input 0

```
5 5 4
1 0 2 1 2 7
2 2 4
1 5 3 4 1 9
2 4 2
```

### Sample Output 0

```
7
9
```

### Sample Input 1

```
4 4 3
1 0 2 1 1 7
2 1 3
2 0 0
```

### Sample Output 1

```
7
0
```
