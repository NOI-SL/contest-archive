---
title: "나를 보게 삶은 짧아"
year: 2022
category: monthly
round: "May 2022"
sortkey: "2-monthly-05-05"
index: 5
max_score: 100
difficulty: "Hard"
contest_name: "National Olympiad in Informatics Sri Lanka - May 2022"
contest_slug: "noi-2022-may"
contest_url: "https://www.hackerrank.com/contests/noi-2022-may"
problem_slug: "player-456"
problem_url: "https://www.hackerrank.com/contests/noi-2022-may/challenges/player-456"
---

Squid Game is an annual game series, that hundreds of cash-strapped contestants accept an invitation to compete in children's games for a tempting prize, but the stakes are deadly.

This game takes place on an uninhabited island. As a result, all of the chosen players must be secretly transported to the island. All participants are instructed to report to a pickup location where they will be picked up by a group of vans. A single pickup location can accommodate a large number of participants, and a single van can carry a large number of players to the hidden island. In addition, the van may pick up any number of participants from a single location.

![image]({{ "/assets/problems/6cd1f73e-1633771885-980f67763a-3485cff5-7d72-42e9-98f8-a019b500ae7f_ea94c24a.jpg" | relative_url }})

The front man (organizer of the game) decided to equip each van with an **RHDC** (Realtime Human Detection and Counting) system. The RHDC system can track the number of players both before the van arrives at the pickup point (**BP**) and after the vehicle has picked up the players (**AP**). The **difference between AP and BP** will be sent to the squid game headquarters after the vehicle picks up the players from a pickup point. 

Your task is to find the number of possible ways that (**OUTPUT**) amount of players could be on the van before the first pickup location. Assume that a van can accommodate **P** players. and the van must stop at **L** different pickup locations. If the situation is ambiguous, output 0.

## Input Format

Input will consist of two lines.

- The first line contains two integers which represent **L** and **P** respectively 
- The second line consists of a list [X<sub>1</sub>, X<sub>2</sub>, X<sub>3</sub>…...X<sub>i</sub>...X<sub>n</sub>].where X<sub>i</sub> represents the output of RHDC system after the i-th pickup location.

## Output Format

A single integer that represents the **OUTPUT**

## Constraints

- 0 < **P** < 10<sup>10</sup>
- 0 < **L** < 10<sup>4</sup>
- -10<sup>7</sup> < **X<sub>i</sub>** < 10<sup>7</sup>

### Sample Input 0

```
4 6
2 1 1 -4
```

### Sample Output 0

```
3
```
