---
title: "The Brackets"
year: 2022
category: qualifier
round: "Selection Test"
sortkey: "1-qualifier-03"
index: 3
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - Screening Test 2022"
contest_slug: "noi-2022-selection-test"
contest_url: "https://www.hackerrank.com/contests/noi-2022-selection-test"
problem_slug: "the-brackets"
problem_url: "https://www.hackerrank.com/contests/noi-2022-selection-test/challenges/the-brackets"
---

## **The Brackets**

You are given a sequence of brackets containing only '('s and ')'s

We can choose any portion (i.e a substring) of the original sequence and reverse it. 

Example : If we decide to reverse the characters from positions 3 to 5 of the original string 

$$S=$$"`(()(()))`", it will be converted to to $$S=$$"`(((())))`".

A perfect bracket sequence is both balanced and contains exactly k prefixes that are also balanced.

For example, if $$k=3$$, then "`()(())()`" is a prefect sequence.

We want to make the sequence perfect by performing at most $$n$$ of operations. Note that operations are performed consecutively.

**Note**

- An answer is guaranteed to exist
- There is no need to minimize the number of operations
- Any way to make the sequence perfect in $$n$$ operations or less is accepted

### **Extra definitions**

**Balanced bracket sequence**

A balanced bracket sequence is a bracket sequence that can be transformed into a correct arithmetic expression by inserting characters '1' and '+' between the original characters of the sequence. For example, bracket sequences '()()' and '(())' are correct. The resulting expressions of these sequences are '(1)+(1)' and '((1+1)+1)'. However, '(', ')(', and '(' are incorrect bracket sequences.

**Prefix of a string**

A prefix is a collection of characters at the beginning of a string. For instance, "col" is a prefix of “colombo”.

## Input Format

- First line contains integer $$t$$ - number of test cases. 

Then there will be $$t$$ test cases. For each test case,

- The first line contains two integers $$n$$ and $$k$$
- The second line contains a bracket sequence($$S$$) of length $$n$$

## Output Format

For each test case

- Print the integer m - the number of operations (There is no need to minimize m)
- In next m lines, print the operations using two integers l and n ($$1 \le l \le r \le n$$) , representing each reverse operation
- After perfoming the operations, the bracket sequence should be regular
- If multiple such answers are possible, print any

## Constraints

- $$1 \le t \le 100$$
- $$1 \le k \le \dfrac{n}{2}$$
- $$2 \le n \le 2000$$, $$n$$ is even

#### **Limits**
- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
4
2 1
)(
10 2
()(())()()
2 1
()
12 3
)))()()()(((
```

### Sample Output 0

```
1
1 2
5
2 3
3 4
4 7
5 9
2 6
0
8
1 4
2 6
3 8
4 10
5 11
6 12
2 7
4 8
```
