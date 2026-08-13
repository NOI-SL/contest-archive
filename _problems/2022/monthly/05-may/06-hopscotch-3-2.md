---
title: "Hopscotch 3"
year: 2022
category: monthly
round: "May 2022"
sortkey: "2-monthly-05-06"
index: 6
max_score: 100
difficulty: "Hard"
contest_name: "National Olympiad in Informatics Sri Lanka - May 2022"
contest_slug: "noi-2022-may"
contest_url: "https://www.hackerrank.com/contests/noi-2022-may"
problem_slug: "hopscotch-3-2"
problem_url: "https://www.hackerrank.com/contests/noi-2022-may/challenges/hopscotch-3-2"
---

Hopscotch is a popular playground game in which players toss a small object, called a lagger, into numbered triangles or a pattern of rectangles outlined on the ground and then hop or jump through the spaces and retrieve the object. It is a children's game that can be played with several players or alone.

Meet Nandula, a 22 years old kid, wants to play this game again. He recalls his mind. He thought of a new way to play this game using his analytical, logical, methodological, investigative, experimental skills. Since it's a lockdown season, he chose to play this game on the main road. He draws two rows of boxes (A, B) on the road and writes some random numbers in each box. Note that both the rows have an equal number of boxes (n).

Consider the boxes of row A as Ai and boxes of B as Bj. In this game Nandula has to jump to two boxes where the numbers are not coprime. Left leg must be on row A and the right leg on row B. Since Nandula is tall as a giraffe, never worry about how he could keep his legs on long distances. He will manage it. His goal is to maximize his jumps. Consider that once he jumps to a box, it will be considered a blocked box and will not be used again. Can you help him to find this maximum number of jumps. Note that a jump means placing both legs on two boxes.

## Input Format

The first line contains an integer n (number of boxes in each row).

The next two lines follow, each line containing n numbers separated by a single space. The format is shown below.

n <br>
A[0] A[1] ... A[n - 1] <br>
B[0] B[1] ... B[n - 1] <br>

## Output Format

Output S which is the maximum number of times the above operation can be made.

## Constraints

- 0 $$\lt$$ n $$\le$$ 10<sup>5</sup><br>
- 2 $$\le$$ A[i], B[i] $$\le$$ 10<sup>9</sup><br>

### Sample Input 0

```
4
2 5 6 7
4 9 10 12
```

### Sample Output 0

```
3
```
