---
title: "Sensor Calliberation"
year: 2026
category: qualifier
round: "Qualifier Round"
sortkey: "1-qualifier-05"
index: 5
max_score: 100
difficulty: "Medium"
contest_name: "NOI 2026 Qualifier Round"
contest_slug: "noi-2026-qualifier-round"
contest_url: "https://www.hackerrank.com/contests/noi-2026-qualifier-round"
problem_slug: "sensor-calliberation"
problem_url: "https://www.hackerrank.com/contests/noi-2026-qualifier-round/challenges/sensor-calliberation"
---

Bob is organizing the inventory for an upcoming robotics bootcamp. He has a box containing $$N$$ different ultrasonic sensors. Each sensor has a specific operating frequency, denoted by an integer $$A_i$$. 

To successfully calibrate the main control board, Bob needs to pair up the sensors. A pair of sensors $$i$$ and $$j$$ (where $$1 \le i < j \le N$$) is considered **perfectly calibrated** if the sum of their operating frequencies is exactly divisible by a target frequency $$K$$.

Given the frequencies of all $$N$$ sensors and the target frequency $$K$$, help Bob determine the total number of perfectly calibrated pairs he can form.

## Input Format

* The first line contains two space-separated integers, $$N$$ and $$K$$: the number of sensors and the target frequency.
* The second line contains $$N$$ space-separated integers $$A_1, A_2, \dots, A_N$$, representing the operating frequencies of the sensors.

## Output Format

* Print a single integer: the total number of perfectly calibrated pairs.

## Constraints

* $$1 \le N \le 2 \cdot 10^5$$
* $$1 \le K \le 10^5$$
* $$1 \le A_i \le 10^9$$

### Sample Input 0

```
6 5
2 8 3 10 5 7
```

### Sample Output 0

```
5
```
