---
title: "The Race for the Throne: A Presidential Quest Across Sri Lanka"
year: 2024
category: finals
round: "Final Round — Day 1"
sortkey: "3-finals-1-02"
index: 2
max_score: 100
difficulty: "Hard"
contest_name: "National Olympiad in Informatics Sri Lanka 2024 - Day 1"
contest_slug: "noi-2024-day-1"
contest_url: "https://www.hackerrank.com/contests/noi-2024-day-1"
problem_slug: "the-race-for-the-throne-a-presidential-quest-across-sri-lanka"
problem_url: "https://www.hackerrank.com/contests/noi-2024-day-1/challenges/the-race-for-the-throne-a-presidential-quest-across-sri-lanka"
---

In the tropical paradise of Sri Lanka, the presidential election season is upon us, and the air is buzzing with excitement and anticipation. Each candidate is vying for the hearts and minds of the people, and grand gestures are the order of the day. From donating properties worth millions to public institutions to promising new infrastructure projects, the candidates are leaving no stone unturned.

However, the current ruler, President Dilan, has a unique and ambitious plan to showcase his commitment to the nation's prosperity. With the economy showing signs of recovery, President Dilan announces the launch of a new, revolutionary airline service. This service will transport passengers free of charge among a network of newly established airports, each located in a different city. But there’s a catch – the service won’t begin until President Dilan visits each airport and personally inaugurates it.

###**The Challenge of the Highways and Airports**

President Dilan is based in Colombo, the bustling capital city. To complete his mission, he must travel to each city with an airport and perform the opening ceremony. The cities are connected by a complex web of highways, each with a toll that must be paid. Moreover, once he opens an airport, he can use flights between the already inaugurated airports to minimize the toll costs. The goal is clear: visit all the designated airports while minimizing the total travel cost.

###**The Quest**

The kingdom has **$$n$$ cities**, each identified by a unique number from $$1$$ to $$n$$, with Colombo always being city number $$1$$. There are **$$m$$ highways** connecting different cities, ensuring there is a path from each city to any other city using these highways. Additionally, **$$k$$ of these cities have the new airports** that need to be inaugurated. Once President Dilan opens an airport, he can use the free airline service to travel between any of the already inaugurated airports. Your task is to help President Dilan plan his journey in the most cost-effective manner.

###**Your Mission**

Harness the power of algorithms to map out the optimal path for President Dilan. He depends on you to make the most strategic and cost-effective decisions. The future of Sri Lanka’s connectivity lies in your hands!

## Input Format

- The first line contains two integers: **$$n$$** (the number of cities) and **$$m$$** (the number of highways)
- The next $$m$$ lines each contain three integers $$a, b, \text{ and } c$$, representing a highway connecting city $$a$$ to city $$b$$ with a toll cost of $$c$$.
- The following line contains **$$k$$**, the number of cities with airports
- The next line contains $$k$$ integers, each denoting a city that has an airport.

## Output Format

- A single integer, representing the **minimum cost** required for President Dilan to visit all the airports starting from Colombo.

## Constraints

- $$1 \leq n \leq 100000$$
- $$0 \leq m \leq 100000$$
- $$1 \leq k \leq n$$
- $$1 \leq c \leq 10^9$$

   
#### **Limits**
- **Time Limit**: 2s
- **Memory Limit**: 256MB

### Sample Input 0

```
4 3
1 2 1
2 3 5
2 4 10
3
2 3 4
```

### Sample Output 0

```
16
```
