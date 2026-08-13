---
title: "Petrol Queues"
year: 2022
category: finals
round: "Final Round — Day 2"
sortkey: "3-finals-2-02"
index: 2
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka 2022 - Day 2"
contest_slug: "noi-2022-day-2"
contest_url: "https://www.hackerrank.com/contests/noi-2022-day-2"
problem_slug: "petrol-queues"
problem_url: "https://www.hackerrank.com/contests/noi-2022-day-2/challenges/petrol-queues"
---

Dijkstra is visiting a country with a fuel crisis for his summer vacation. He is facing a lot of issues because of the Petrol shortages in the country. He attempts to overcome this situation by using his graph theory knowledge.

- $$N$$ is the number of cities (each with a fuel station except 0th city)
- $$q_i$$ is the petrol queue length at city $$c_i$$
- $$R$$ is the number of roads
- $$c_a$$ $$c_b$$ $$r_{ab}$$ is the cities $$c_a$$ and $$c_b$$ and the distance $$r_{ab}$$ between them by road.
- $$S$$ is the number of stops Dijkistra has to make.
- $$s_i$$ is a place Dijkistra has to stop.
- $$T$$ is the volume of the petrol tank.

You have to start from city $$0$$ with full volume of petrol in the tank $$T$$.

You can go to any city if there is a road connecting your current city and the next. However, you cannot move if you run out of petrol. It is okay to run out of petrol when you reach a city.

If you decide to fill your tank somewhere, you have to wait in the queue for $$q_i$$ hours.

You have to go to all the $$S$$ cities. You can go through the same city over and over. 

The fuel is measured in $$l$$, distance in $$km$$ and time in $$h$$. The vehicle uses $$1l$$ per every $$1km$$.

The total cost of the journey will be sum of the length of roads taken, time spent on queues, and the total fuel filled from cities (not counting the first full tank fill). Lesser the cost, higher your score will be.

**Note:** Don't try to get the full score. Use heurestics to improve your score.

## Input Format

A single integer $$N$$

$$N$$ lines containing a single integer each denoting $$q_i$$

A single integer $$R$$

$$R$$ lines each containing 3 integers $$c_a$$ $$c_b$$ and $$r_{ab}$$

A single integer $$S$$

$$S$$ lines containing a single integer each denoting $$s_i$$

A single integer $$T$$

## Output Format

A single integer $$L$$ denoting the length of the path.

$$L$$ lines with each containing two integers $$X_i$$ and $$Y_i$$ where $$X_i$$ is the next city in the path and $$Y_i$$ is the amount of fuel you fill at the particular city.

## Constraints

$$0 < N \leq 10000$$

$$0 < R \leq 1000000$$

$$0 < T \leq 1000$$

$$r_{ab} \leq T$$

$$0 < S \leq 2000$$

$$ s_i < s_{i+1}$$

#### **Limits**
- **Time Limit**: 2s
- **Memory Limit**: 512MB

### Sample Input 0

```
5
0
1
13
15
18
6
0 3 8
1 2 1
1 4 6
2 4 3
2 3 8
3 4 2
2
2
3
10
```

### Sample Output 0

```
3
3 6
2 8
3 0
```

### Sample Input 1

```
6
0
4
14
7
14
19
7
0 2 4
0 3 6
0 1 7
1 4 7
1 2 9
2 5 3
2 4 3
2
1
4
10
```

### Sample Output 1

```
2
1 4
4 0
```
