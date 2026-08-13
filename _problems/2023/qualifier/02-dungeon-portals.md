---
title: "Dungeon Portals"
year: 2023
category: qualifier
round: "Selection Test"
sortkey: "1-qualifier-02"
index: 2
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - Screening Test 2023"
contest_slug: "noi-2023-selection-test"
contest_url: "https://www.hackerrank.com/contests/noi-2023-selection-test"
problem_slug: "dungeon-portals"
problem_url: "https://www.hackerrank.com/contests/noi-2023-selection-test/challenges/dungeon-portals"
---

You are assisting your friend who is trying to develop a dungeon crawling game. Your friend has created a dungeon layout generator that creates a set of rooms(represented by x and y coordinates) with Portals in some of them. These portals that only works in one direction decides how the player can advance in the dungeon. Every room can have only one portal at a time with a fixed destination and some rooms do not have portals at all. Your task is to find out whether a player starting at the room at $$[1,1]$$ can reach a reward room via the given portals.

If a reward room can be reached, print `FINISH X,Y` where `X,Y` are the coordinates of the reward room reached.

Print `LOOP` if following the portals leads to a loop.

Print `STOP X,Y` if a room without a portal is reached by following the portals, where `X,Y` are the coordinates of the last room the player would end up in

## Input Format

one line containing $$p$$(the number of rooms with portals) and $$r$$(the number of reward rooms)  
$$p$$ lines each containing 4 integers each: $$x_{s}\ y_{s}\ x_{d}\ y_{d}$$ where $$x_s,y_s$$ are coordinates of a room with a portal and $$x_d,y_d$$ are the coordinates of the room the portal will send the player to.  
$$r$$ lines containing 2 integers each: $$x_f\ y_f$$ where $$x_f,y_f$$ are coordinates of a reward room.

## Output Format

One line containing a `FINISH X,Y`, `LOOP` or `STOP X,Y` message as given in the problem statement

## Constraints

$$1\le p \le10000$$  
$$1\le r \le10000$$  
$$0 \le x,y \le 10000$$

### Sample Input 0

```
11 3
1 1 1 2
4 5 4 4
1 4 2 4
3 3 3 2
2 2 2 3
3 2 4 2
3 5 3 4
4 3 4 4
2 3 3 3
4 2 4 3
1 2 2 2
2 4
4 4
3 4
```

### Sample Output 0

```
FINISH 4,4
```
