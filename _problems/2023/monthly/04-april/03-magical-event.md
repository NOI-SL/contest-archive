---
title: "Magical Event"
year: 2023
category: monthly
round: "April 2023"
sortkey: "2-monthly-04-03"
index: 3
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - April 2023"
contest_slug: "noi-2023-apr"
contest_url: "https://www.hackerrank.com/contests/noi-2023-apr"
problem_slug: "magical-event"
problem_url: "https://www.hackerrank.com/contests/noi-2023-apr/challenges/magical-event"
---

There are $$n$$ magicians performing a spell in a prestigious event. Magicians must form $$m$$ groups. Each magician must be included in a group and one magician can only be included in only one group. Magicians of each group must be adjacent. (In the given order of the input) 

$$i^{th}$$ magician has a spell power of $$p_i$$. When a magician is a part of the group, their spell power becomes $$p_{i}*s$$, where $$s$$ is the size of their group.

The owner of this event actually don't like this performance and conspires to reduce the total power of all magicians. Owner has the authority to divide magicians in to groups as previously stated. Find and output the minimum possible total power after forming groups.

## Input Format

- First line contains two space seperated integers $$n$$ and $$m$$
- Second line contains $$n$$ space seperated integers $$p_0 ...p_{n-1}$$

## Output Format

- The minimum possible total power as an integer.

## Constraints

- $$2 <= n <= 10^{4}$$
- $$1 <= m <= 10^{3}$$
- $$1 <= p_i <= 10^9$$

**Subtask 1 - 40 pts**

- $$2 <= n <= 10^{2}$$
- $$1 <= m <= 10^{2}$$

**Subtask 2 - 20 pts**

- $$2 <= n <= 10^{3}$$
- $$1 <= m <= 10^{2}$$

**Subtask 3 - 40 pts**

- No aditional constraints

### Sample Input 0

```
3 2
10 20 30
```

### Sample Output 0

```
90
```
