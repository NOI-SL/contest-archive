---
title: "Quarantine-centers"
year: 2021
category: monthly
round: "April 2021"
sortkey: "2-monthly-04-05"
index: 5
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - April 2021"
contest_slug: "noi-2021-apr"
contest_url: "https://www.hackerrank.com/contests/noi-2021-apr"
problem_slug: "quarantine-centers"
problem_url: "https://www.hackerrank.com/contests/noi-2021-apr/challenges/quarantine-centers"
---

With recent rise of in the pandemic, most Sri Lankans wants to return to SL. Unfortunately, there are a limited number of hotels to quarantine the incoming citizens. In addition, government has made a new regulation as to passengers from only one aircraft can be quarantined in a hotel at a time.

Since the hotels are filling up soon, the goernment has relaxed the quarantine regulations. Now, the number of quarantine days is dependent on the country. For example, a country like Israel (where most inhabitants are vaccinated) requires a smaller quarantine length while India (where many people are dying) requires a longer quarantine.

There is a fixed amount of money that a hotel can charge per day per person.

## Input Format

The first line contains an integer $$T$$ denoting the number of testcases.

For each testcase, the following information is given.

$$R$$ (the number of rooms in your hotel), $$F$$ (the number of flight information available to you) and $$P$$ (the profit earned when a room is occupied for one day) are in a single line seperated by a space.

Then there are $$F$$ lines with three integers $$A_i$$ (the arrival date of the flight), $$Q_i$$ (the quarantine time required) and $$P_i$$ (the number of passengers in the flight).

## Output Format

Output the maximum money your hotel can earn.

## Constraints

$$0 < T \leq 20$$

$$0 < R \leq 2500$$

$$0 < F \leq 25000 $$

$$0 < P \leq 20 $$

$$0 < A,Q \leq 500000000$$

$$0 < P \leq 5000$$

### Sample Input 0

```
2
100 3 10
0 3 20
0 5 50
4 6 80
35 4 7
0 2 25
2 4 25
4 7 25
3 6 40
```

### Sample Output 0

```
5400
1820
```
