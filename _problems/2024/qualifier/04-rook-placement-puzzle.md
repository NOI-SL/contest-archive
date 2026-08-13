---
title: "Rook Placement Puzzle"
year: 2024
category: qualifier
round: "Qualifier Round"
sortkey: "1-qualifier-04"
index: 4
max_score: 100
difficulty: "Medium"
contest_name: "NOI 2024 Qualifier Round"
contest_slug: "noi-2024-qualifier-round"
contest_url: "https://www.hackerrank.com/contests/noi-2024-qualifier-round"
problem_slug: "rook-placement-puzzle"
problem_url: "https://www.hackerrank.com/contests/noi-2024-qualifier-round/challenges/rook-placement-puzzle"
---

**Story**

You are presented with a chessboard (N x N squares) and a bag overflowing with black rooks. Someone has already placed some white rooks (p of them) on the board in a seemingly random arrangement.

You are tasked with figuring out the maximum number of rooks such that none of these selected rooks are protected by each other. The number should be valid even if the arrangement is changed. 

Then, you are tasked with figuring out the maximum number of black rooks that you can place on the board by rearranging white rooks and positioning black rooks such that no black rook is attacked by a white rook.

**Challenge**

Given the size of the chessboard (N) and the number of white rooks that has been already placed (p), determine the maximum number of white rooks that are always unprotected from each other. Also, find the maximum number of black rooks to be placed on the board by rearranging the formations such that no black rook is attacked by a white rook.

## Input Format

- First line will be an integer for chessboard size (N)
- second line will be an integer for number of Rooks (P)

## Output Format

- First line should be the maximum number of unprotected rooks
- Second line should be the maximum number of black rooks that could be placed

## Constraints

- A same color rook protects horizontally and vertically across the entire row and column it occupies
- An opposite color rook attacks horizontally and vertically across the entire row and column it occupies

- N < 1000
- P < 1000000

### Sample Input 0

```
8
20
```

### Sample Output 0

```
3
12
```
