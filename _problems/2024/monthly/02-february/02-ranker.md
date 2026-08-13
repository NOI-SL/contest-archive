---
title: "Ranker"
year: 2024
category: monthly
round: "February 2024"
sortkey: "2-monthly-02-02"
index: 2
max_score: 100
difficulty: "Medium"
contest_name: "NOI 2024 february monthly contest"
contest_slug: "noi-2024-feb"
contest_url: "https://www.hackerrank.com/contests/noi-2024-feb"
problem_slug: "ranker"
problem_url: "https://www.hackerrank.com/contests/noi-2024-feb/challenges/ranker"
---

You are given the rank 
**R**
you want to find, followed by the names of students and their corresponding marks in a particular coding challenge. Your task is to determine the name of the student who achieved the specified rank.

## Input Format

- The first line contains an integer **R** representing the rank you want to find.
- The second line contains space-separated strings, each string representing the name of a student.
- The third line contains space-separated integers or floats, each number representing the marks scored by the corresponding student. There can be duplicate marks.

## Output Format

Print the name of the student who achieved the **Rᵗʰ** rank in the class.

- If there are multiple students with the same score, print their names in alphabetical order, each on a separate line.

## Constraints

- The number of students, N will be between 1 and 1000 inclusive.
- Each student's name will consist only of alphabetical characters and will have a length between 1 and 20 characters.
- Each student's score will be an flaot between 0 and 100, inclusive.
- The input will always be valid; there is no need to handle invalid inputs.
- At least one student with the given rank exists.
- If two students have the same marks, the next rank is not skipped.

### Sample Input 0

```
2
Yashed Senura Nethmi Terence Ayash
95 85 90 75 90
```

### Sample Output 0

```
Ayash
Nethmi
```

### Sample Input 1

```
3
Alice Bob Charlie David
80 70 80 90
```

### Sample Output 1

```
Bob
```
