---
title: "Perfect Power Pairs"
year: 2025
category: finals
round: "Final Round — Day 2"
sortkey: "3-finals-2-01"
index: 1
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics 2025 day 2"
contest_slug: "noi-2025-day-2"
contest_url: "https://www.hackerrank.com/contests/noi-2025-day-2"
problem_slug: "perfect-power-pairs"
problem_url: "https://www.hackerrank.com/contests/noi-2025-day-2/challenges/perfect-power-pairs"
---

Deep within the obsidian spires of Arithmia, you serve as the king’s humble numeromancer. One stormy eve, the Royal Archivist unveils a scroll of ancient runes—an array of enchanted integers—and beseeches you to uncover every pair whose union sparks a perfect $$k$$th-power. Fail, and the library’s arcane wards may shatter!


You are given ($$n$$) positive integers ($$a_1, a_2, \dots, a_n$$) and an integer ($$k \ge 2$$). Count the number of pairs ($$(i, j)$$) with ($$1 \le i < j \le n$$) such that there exists an integer ($$x$$) satisfying
$$a_i \cdot a_j = x^k$$

## Input Format

The first line contains two integers ($$n$$) and ($$k$$)

The second line contains ($$n$$) integers ($$a_1, a_2, \dots, a_n$$)

## Output Format

Print a single integer—the number of suitable pairs.

## Constraints

- $$2 \le n \le 10^5,\quad 2 \le k \le 100$$
- $$1 \le a_i \le 10^5$$

**Subtask 1 - 25 pts**

- $$2 \le n \le 100,\quad 2 \le k \le 100$$
- $$1 \le a_i \le 10^5$$

### Sample Input 0

```
6 3
1 3 9 8 24 1
```

### Sample Output 0

```
5
```
