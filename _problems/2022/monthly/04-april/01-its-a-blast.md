---
title: "It's a Blast"
year: 2022
category: monthly
round: "April 2022"
sortkey: "2-monthly-04-01"
index: 1
max_score: 100
difficulty: "Easy"
contest_name: "National Olympiad in Informatics Sri Lanka - April 2022"
contest_slug: "noi-2022-apr"
contest_url: "https://www.hackerrank.com/contests/noi-2022-apr"
problem_slug: "its-a-blast"
problem_url: "https://www.hackerrank.com/contests/noi-2022-apr/challenges/its-a-blast"
---

After escaping Bane’s prison, Batman finds out that Bane has set up a nuclear bomb in Gotham City. The bomb is connected to a series of wires that can trigger a nuclear reaction. These wires range from Type-0 to Type-9 wires. In order to prevent a nuclear reaction and save the city, Batman has to carefully cut off the wires such that the sum of types of uncut wires is even. 

However, if Batman is unable to cut the wires accordingly, or if the final wire in the uncut configuration is even, Batman will have to fly the bomb several miles up in the air and detonate the bomb - sacrificing himself in the process - to save the city.

Decide whether there is a feasible configuration that can diffuse the bomb, or whether Batman will have to sacrifice himself.

## Input Format

- ***t*** - the number of test cases

- ***n*** - the number of wires in the configuration

- ***s*** - a string representing the configuration of wires in the bomb, with each digit representing the type of wire

## Output Format

For each ***s***, print a possible configuration of uncut wires such that the bomb is in a diffused state if any exist (note that it is possible for multiple such configurations to exist) , or -1 if Batman has to sacrifice himself

## Constraints

- 1 $$\leq$$ t $$\leq$$ 1000

- 1 $$\leq$$ n $$\leq$$ 3000

- s contains no leading zeros

- The sum of n values for a given t $$\leq$$ 3000

### Sample Input 0

```
4
4
5422
3
929
5
62778
1
0
```

### Sample Output 0

```
-1
929
6277
-1
```
