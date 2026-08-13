---
title: "Teleporting Bridges"
year: 2020
category: finals
round: "Final Round — Day 1"
sortkey: "3-finals-1-02"
index: 2
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka 2020 - Day 1"
contest_slug: "noi-2020-day-1"
contest_url: "https://www.hackerrank.com/contests/noi-2020-day-1"
problem_slug: "teleporting-bridges"
problem_url: "https://www.hackerrank.com/contests/noi-2020-day-1/challenges/teleporting-bridges"
---

There are ***M*** known worlds in a ***two-dimensional*** universe. Each world contains one or more cities, and each city will be located in one of those ***M*** worlds. A city is a ***point in the 2D universe*** that is represented by an integer coordinate ***(x,y)***. No more than 1 city will share the same coordinate. There are ***N*** cities in the universe and some of those cities are also called ***Megacities***. Each world has ***at least one Megacity***. 

The distance between two cities is the ***euclidean distance*** (the distance of the straight line) between the two points. All the cities in the universe are laid out satisfying the following conditions:

- ***Distance between any two cities (Megacities are also cities) of any given world < 10,000***
- ***Distance between any two cities from different worlds >= 10,000***

As the founder of The Porting Company, your goal is to provide teleporting infrastructure so that people can teleport between any two cities in the universe. You achieve that by building a set of teleporting bridges. A teleporting bridge can be constructed between any two cities in the same world, or between any two Megacities. 

People can teleport from city S to city E if at least one of the following conditions are satisfied:  
  
 - if there is a teleporting bridge between city ***S*** and city ***E***
 - for a given sequence of q cities (say ***c1, c2, …., cq***) there exists ***q+1*** teleporting bridges between ***(S,c1), (c1,c2), (c2, c3), …., (cq-1, cq), (cq,E)*** where ***q >= 1***

The cost of constructing a teleporting bridge between two cities is the square of the distance between the two cities. i.e. if the distance is ***d***, then the cost id ***d<sup>2</sup>***. 

Your task is to derive the ***minimum total cost*** to construct teleporting bridges so that people can teleport between ***any pair of cities*** in the universe.

## Input Format

The first line contains an integer ***M***, the number of worlds.

Each pair of next ***2M*** lines will contain information about ***M*** worlds.

- The first line of each pair of lines contains space-separated integers representing Megacities. The first number is the number of Megacities ***P***. Next ***2P*** numbers represent ***(x,y)*** coordinates of those Megacities. 
- The second line of each pair of lines contains space-separated integers representing other cities. The first number is the number of cities ***C*** which are not Megacities. Next ***2C*** numbers represent ***(x,y)*** coordinates of those cities.

## Output Format

The ***minimum total cost*** to construct teleporting bridges.

## Constraints

- **1 $$\leq$$ M, the number of worlds $$\leq$$ 100**  
- **1 $$\leq$$ Number of cities in a world $$\leq$$ 1000**  
- **1 $$\leq$$ Number of Megacities $$\leq$$ 1000**  
- **-10<sup>7</sup> $$\leq$$ X, Y $$\leq$$ 10<sup>7</sup>** where ***(X,Y)*** are the integer coordinates of cities.   
  
At least ***25%*** of test cases will have only ***1 world***.  
At least ***25%*** of cases will have only ***1 city*** in each world.  
  
   
#### **Limits**
- **Time Limit**: 2s
- **Memory Limit**: 256MB

### Sample Input 0

```
2
1 0 0
2 1 0 -1 0
2 0 100000 0 100002
0
```

### Sample Output 0

```
10000000006
```
