---
title: "Prime Game "
year: 2022
category: finals
round: "Final Round — Day 1"
sortkey: "3-finals-1-01"
index: 1
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka 2022 - Day 1"
contest_slug: "noi-2022-day-1"
contest_url: "https://www.hackerrank.com/contests/noi-2022-day-1"
problem_slug: "the-prime-game-1-2"
problem_url: "https://www.hackerrank.com/contests/noi-2022-day-1/challenges/the-prime-game-1-2"
---

Ranith and Manil are two brothers. Manil is in eighth grade and he is good at maths. Ranith is in eleventh grade and he is a smart programmer who has past experience in the National Olympiad in Informatics. Last week the Ministry of Education declared a holiday week for their school and they started to play during the vacation.

But these smart brothers decided to spend the vacation in a meaningful way. Instead of wasting all their free time on social media or computer games, they thought of inventing a new game that gives them brain exercise.

Manil, the younger brother came up with an idea. Manil gives a list of $$N$$ natural numbers($$a_1$$,$$a_2$$,$$a_3$$,...,$$a_n$$) and he asks his brother to count the number of different rare subsequences of the original set. According to Manil a rare subsequences satisfies the below conditions,

- The subsequence has n numbers$$(2 \leq n \leq N)$$ of Manil’s original number set. 
- The product of all the n numbers in the subsequence is a prime number
- The subsequence is k spaced (equally spaced with separation of $$k$$ numbers) in the original list of numbers. (i.e, $$a_i$$,$$a_{i+k}$$,$$a_{i+2k}$$,...,$$a_{i+nk}$$)
- Two subsequences are said to be different if their original index sequences are different.

**Hint:-**
- Prime Number is a positive integer that is only divisible by one and the number itself.
- Natural Numbers are positive integers greater than or equal to one $$\{1,2,3,...\}$$.

Ranith, the programming kid says this game is too simple! He argues that this game can be automated using a computer program and can be solved for very large number sets. In this problem, you have to work as Ranith to solve the problem.

## Input Format

- The first line contains $$T$$, the number of test cases
- In the next $$2$$ x $$T$$ lines, each test case is expressed in two lines,
- $$N$$ $$K$$ - Two space separated integers describing the number of elements in Manil’s original number sequence and the number K mentioned in above conditions.
- $$N$$ Space separated integers describing the elements of Manil’s original number set.

## Output Format

- Output should contain $$T$$ lines.
- Each line should contain a single positive integer, the number of different rare subsequence of the particular test case.
- If this count is greater than $$10^9+5$$, output the answer modulo $$10^9+5$$

## Constraints

- $$1 \leq T \leq 100$$
- $$1 \leq N \leq 100,000$$
- $$1 \leq a_i \leq 100,000$$
- $$1 \leq K \leq 5$$

#### **Limits**
- **Time Limit**: 2s
- **Memory Limit**: 512MB

### Sample Input 0

```
5
4 2
1 2 7 4
7 3
3 11 5 1 7 3 1
8 1
1 2 6 1 1 5 19 1
10 5
1 2 4 8 5 3 1 12 2 2
4 1
1 1 2 2
```

### Sample Output 0

```
1
2
4
2
2
```

### Sample Input 1

```
1
4 1
1 3 1 3
```

### Sample Output 1

```
4
```
