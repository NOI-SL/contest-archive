---
title: "The Crown Hub"
year: 2025
category: finals
round: "Final Round — Day 2"
sortkey: "3-finals-2-02"
index: 2
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics 2025 day 2"
contest_slug: "noi-2025-day-2"
contest_url: "https://www.hackerrank.com/contests/noi-2025-day-2"
problem_slug: "the-crown-hub"
problem_url: "https://www.hackerrank.com/contests/noi-2025-day-2/challenges/the-crown-hub"
---

In the majestic kingdom of **Graphoria**, there are `n` cities connected by `n - 1` bidirectional roads, forming a vast network of paths through mountains, rivers, and valleys. Each road has a toll cost, and each city has a population eagerly awaiting the grand **Royal Unity Festival** — where all citizens must travel to a single city to celebrate.

To host this historic event, the King will designate **one city** as the **Crown Hub**, where all citizens must gather. However, travel isn't cheap: every citizen must pay a cost equal to the **sum of tolls along their route to the hub**, multiplied by the number of people in their city.

Luckily the king is blessed with a divine favor.He may select up to k cities **(excluding the hub)** to serve as Divine Reimbursement Centers. These cities grant a magical effect: 

- For any citizen whose path to the hub passes through a Reimbursement Center, **the portion of tolls from their hometown to that center** is **refunded**.

The King wants to know the **best city to declare as the Crown Hub**, and **which Reimbursement Center to build**, so that the **total travel cost** for all citizens in the kingdom is minimized.

## Input Format

```
n k
p₁ p₂ ... pₙ

Next n - 1 lines follow:
u v c
...
```
- n  :- Number of cities 
- pᵢ :- Population of i th city
- (uᵢ, vᵢ, cᵢ) :- A bidirectional path connecting uᵢ and vᵢ with cost cᵢ

## Output Format

```
min_total_burden
```

A single integer: the **minimum total burden** after optimally choosing the hub and up to `K` Reimbursement Centers.

## Constraints

- `2 ≤ n ≤ 2 × 10⁵`
- `0 ≤ k ≤ 1`
- `1 ≤ pᵢ ≤ 100`
- `1 ≤ cᵢ ≤ 10⁶` 

### Subtasks
- Subtask 1 (10 points): k = 0, n ≤ 1000
- Subtask 2 (20 points): n ≤ 1000
- Subtask 3 (40 points): k = 0
- Subtask 4 (10 points): Every node has at most 2 neighbors
- No more subtasks

### Sample Input 0

```
5 1
2 1 3 4 2
1 2 3
1 3 2
3 4 4
3 5 1
```

### Sample Output 0

```
10
```
