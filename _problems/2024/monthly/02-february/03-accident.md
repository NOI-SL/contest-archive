---
title: "Accident?"
year: 2024
category: monthly
round: "February 2024"
sortkey: "2-monthly-02-03"
index: 3
max_score: 100
difficulty: "Hard"
contest_name: "NOI 2024 february monthly contest"
contest_slug: "noi-2024-feb"
contest_url: "https://www.hackerrank.com/contests/noi-2024-feb"
problem_slug: "accident"
problem_url: "https://www.hackerrank.com/contests/noi-2024-feb/challenges/accident"
---

There is a field with $$N$$ cars, and each car pointing towards direction $$D_i$$. Your task is to check, if all the cars starts at the same time, will there be any accidents or not.  
**Note: Travelling together won't be considered as an Accident.**

## Input Format

The first line contains an integer $$N$$ denotes the number of cars. The next $$N$$ lines contains two space-separated integers $$(X_i, Y_i)$$ denoting the values of coordinates of the car. The next line contains $$N$$ space-separated $$(D_i)$$ integers denoting the direction the $$i$$^th car is pointing at.

## Output Format

Print "YES" if the accident occurs, else print "NO".

## Constraints

$$1 \lt N \le 10 ^ 5$$  
$$0 \lt X_i\ ,\ Y_i \le 200$$  
$$D = ['N','S','E','W']$$  
Time Limit: $$2$$ sec  
Memory Limit :$$512$$ MB

### Sample Input 0

```
3
9 9
9 9
9 9
E S S
```

### Sample Output 0

```
YES
```
