---
title: "The Perfect Fuel Queue"
year: 2022
category: qualifier
round: "Selection Test"
sortkey: "1-qualifier-06"
index: 6
max_score: 100
difficulty: "Hard"
contest_name: "National Olympiad in Informatics Sri Lanka - Screening Test 2022"
contest_slug: "noi-2022-selection-test"
contest_url: "https://www.hackerrank.com/contests/noi-2022-selection-test"
problem_slug: "the-perfect-fuel-queue"
problem_url: "https://www.hackerrank.com/contests/noi-2022-selection-test/challenges/the-perfect-fuel-queue"
---

Due to the current fuel shortage in Sri Lanka, CEYPETCO needs an effective way to distribute the limited stocks of fuel they have.

To do this, a queue is formed alongside the road where it is arranged in a single line so that it will not affect the traffic in the area. There are $$v$$ vehicles and $$q$$ queue-slots available in the queue. One queue-slot can have multiple vehicles.

The minister of fuel and energy says that it will be cost effective to distribute fuel if there is at least one vehicle in every queue-slot and there is at least one continuous segment of queue-slots that contains exactly $$n$$ number of vehicles.

The fuel queue formation is said to be perfect if it is cost-effective for any arrangement of the queue where there are no empty queue-slots within.

The minister needs your urgent help to determine whether the queue formation is perfect or not.

## Input Format

The first line contains a single integer $$t$$, the number of test cases.

The first and only line of each test case contains three integers $$v$$, $$q$$, and $$n$$

## Output Format

For each test case, print **YES**, if the fuel queue formation is perfect, or **NO** otherwise.

## Constraints

- $$1{\space\leq\space}t{\space\leq\space}10$$<sup>$$5$$</sup>
- $$1{\space\leq\space}q,v,n{\space\leq\space}10$$<sup>$$18$$</sup>
- $$q{\space\leq\space}v$$

#### **Limits**
- **Time Limit**: 2s
- **Memory Limit**: 256MB

### Sample Input 0

```
5 
1 1 1
7 7 8
10 4 10
200 100 300
5289 217 5522
```

### Sample Output 0

```
YES
NO
YES
NO
NO
```
