---
title: "Top gun "
year: 2023
category: qualifier
round: "Selection Test"
sortkey: "1-qualifier-01"
index: 1
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - Screening Test 2023"
contest_slug: "noi-2023-selection-test"
contest_url: "https://www.hackerrank.com/contests/noi-2023-selection-test"
problem_slug: "top-gun"
problem_url: "https://www.hackerrank.com/contests/noi-2023-selection-test/challenges/top-gun"
---

You're in the cockpit of an **F-18 Super Hornet,** flying through treacherous mountain terrain. Suddenly, a UAV drone spots an enemy **Lockheed Martin F-22 Raptor,** but its location is uncertain due to malfunction. And the jets are flying through mountain areas, so the radar system of both planes does not work. It’s up to you as Malindu's wingman to keep alert. Suddenly, the F-22 comes into view, just **D meters to your right** and **heading north(F22 doesn't spot you).** But with its advanced speed and weapons, you only have one shot at taking it down.Only way **F-22** can spot you is you fire the missile and you miss the shot. Can you make the shot before it spots you? With knowledge of your own **F-18's max speed V** and the **F-22's speed U**, and your **missile range R,** the fate of the mission rests on your decision: **SHOOT** or **DON'T**.

## Input Format

- first you are given the no of test cases
- Second line you are given 4 space separated decimal numbers **U,V,D,R**

- U- F-22 Max speed
- V-your max speed
- D-distance
- R- Firing Range of your Missile

## Output Format

Print either "SHOOT" or "DON'T" in each line

## Constraints

- **U>V**
- **U,V are given in Kilometers per hour (Kmph)**
- **D,R are given in Kilometers(KM)**

### Sample Input 0

```
2
1000 800 10 5
800 500 4 5
```

### Sample Output 0

```
DONT
SHOOT
```

### Sample Input 1

```
1
750 520.54 3.2 2.5
```

### Sample Output 1

```
SHOOT
```
