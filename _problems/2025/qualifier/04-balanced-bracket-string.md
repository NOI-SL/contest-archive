---
title: "balanced-bracket-string"
year: 2025
category: qualifier
round: "Qualifier Round"
sortkey: "1-qualifier-04"
index: 4
max_score: 100
difficulty: "Medium"
contest_name: "NOI 2025 Qualifier Round"
contest_slug: "noi-2025-qualifier-round"
contest_url: "https://www.hackerrank.com/contests/noi-2025-qualifier-round"
problem_slug: "balanced-bracket-string"
problem_url: "https://www.hackerrank.com/contests/noi-2025-qualifier-round/challenges/balanced-bracket-string"
---

You are given a string consisting of the characters `(`, `)`, `{`, `}`, `[`, and `]` only. Your task is to check if the brackets in the string are balanced. If they are balanced, print `YES`; otherwise, print `NO`.

A string of brackets is considered balanced if:

1. Each opening bracket (`(`, `[`, or `{`) has a corresponding closing bracket (`)`, `]`, or `}`) of the same type.
2. The pairs of brackets are correctly nested — that is, you cannot close a bracket before its matching opening bracket.

## Examples of balanced strings

-   `()`
-   `[]`
-   `{[]}`

## Examples of unbalanced strings

-   `((]`

## Input Format

The input consists of a single line containing a string of brackets.

## Output Format

Print `YES` if the brackets are balanced, or `NO` otherwise.

## Constraints

-   The length of the string is between 1 and 100 characters.
-   The string contains only the characters `(`, `)`, `{`, `}`, `[`, and `]`.

### Sample Input 0

```
([]{})
```

### Sample Output 0

```
YES
```

### Sample Input 1

```
{[()])
```

### Sample Output 1

```
NO
```
