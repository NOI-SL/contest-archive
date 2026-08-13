---
title: "Pebbles 3"
year: 2024
category: finals
round: "Final Round — Day 1"
sortkey: "3-finals-1-01"
index: 1
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka 2024 - Day 1"
contest_slug: "noi-2024-day-1"
contest_url: "https://www.hackerrank.com/contests/noi-2024-day-1"
problem_slug: "pebbles-3-1"
problem_url: "https://www.hackerrank.com/contests/noi-2024-day-1/challenges/pebbles-3-1"
---

Alice has a thread with $$n$$ pebbles and wants to separate them. As her good friend, you offered to help her, But you need to do it in the minimum possible effort.

You can break the thread in multiple steps. At each step, you need to select one of the existing threads and break it. Initially, there is only one thread with pebbles from $$0$$ to $$n-1$$. Then you can choose where to break that thread. The cost of breaking depends only on the start and end of the thread, not on the breaking point.

If you have a pebble thread from $$i^{th}$$ pebble to the $$j^{th}$$ pebble, breaking it requires effort $$C(i,j$$)

$$C(i,j) = (k_i + k_j)$$

$$k$$ is an integer array of length $$n$$.

After you break the initial thread, you will have two threads. If you break the initial thread at point $$l$$, you will get two threads: from $$i$$ to $$l$$ and $$l+1$$ to $$j$$. Then you can pick any of these to perform the next operation. 

You task is to repeatedly do break operations until you get $$n$$ threads each containing only a single pebble.

Find the minimum effort to separate all pebbles in the thread.

## Input Format

First line contains single integer $$n$$

Second line contains $$n$$ space seperated integers $$k_i$$ ($$0 \leq i \leq n-1 \text{ (0 - indexed)}$$)

## Output Format

- Single integer, minimum effort possible.

## Constraints

- $$k_i \leq 10^9$$
- $$n <= 2*10^2$$

#### **Subtasks**

- subtask 1 - **20 pts**
	- All $$k_i$$ are equal
- subtask 2 - **20 pts**
	- $$k_i \leq k_{i+1} \text{ for all } 0 \leq i \leq n-1 \text{ (0 - indexed)}$$ 
- subtask 3 - **30 pts**
	- $$n <= 10$$
- subtask 4 - **30 pts**
	- No additional constraints
    
    
#### **Limits**
- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
4
5 1 3 2
```

### Sample Output 0

```
14
```
