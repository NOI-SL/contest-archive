---
title: "Petrol Queue"
year: 2022
category: qualifier
round: "Selection Test"
sortkey: "1-qualifier-05"
index: 5
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - Screening Test 2022"
contest_slug: "noi-2022-selection-test"
contest_url: "https://www.hackerrank.com/contests/noi-2022-selection-test"
problem_slug: "petrol-queue"
problem_url: "https://www.hackerrank.com/contests/noi-2022-selection-test/challenges/petrol-queue"
---

You are given an array a representing the petrol distribution of the petrol queue of $$n$$ vehicles. The $$0 th$$ position of the array represents the front of the queue. There is a **limited amount of petrol liters available** in the shed. The manager of the petrol shed wants to distribute the petrol in **non-increasing order** so the vehicles at the back never get more petrol than vehicles at the front.

But the pump attendant distributes the petrol the way he wants. So the manager asks you to make the distribution non-increasing by doing the following operation a **minimum number of times**.

At each operation you can select two adjacent positions $$i$$ and $$j$$ $$(|i-j|=1)$$ in the petrol queue where $$a_i>0$$ and $$a_j>0$$ and,

- Remove 1 liter from $$i^{th}$$ vehicle and pump 1 liter to the $$j^{th}$$ vehicle $$(a_i-1,a_j+1)$$ **OR**
- Remove 1 liter from $$j^{th}$$ vehicle and pump 1 liter to the $$i^{th}$$ vehicle $$(a_j-1,a_i+1)$$.


Your task is to **find the minimum number** of operations needed to make the petrol distribution non-increasing. There can be vehicles that do not get any petrol at all.

## Input Format

First line contains two integers $$n$$ and $$m$$, $$n$$ - number of vehicles in the petrol queue, $$m$$ -  available amount of petrol in liters

Second line contains $$n$$ integers $$a_0,a_1,a_2,...,a_{n-1}$$ representing the petrold distribution among the vehicles by the pump attendant. Sum of these $$n$$ integers equal to $$m$$.

## Output Format

Print a single integer representing the minimum number of operations required to make the petrol distribution non-increasing.

## Constraints

$$1 \leq n,m\leq 250$$

$$0 \leq a_i \leq m$$

#### **Limits**
- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
6 13
4 2 1 2 2 2
```

### Sample Output 0

```
2
```

### Sample Input 1

```
3 9
4 3 2
```

### Sample Output 1

```
0
```

### Sample Input 2

```
2 1
0 1
```

### Sample Output 2

```
1
```
