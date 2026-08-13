---
title: "I'll buy you anything"
year: 2023
category: monthly
round: "March 2023"
sortkey: "2-monthly-03-04"
index: 4
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - March 2023"
contest_slug: "noi-2023-mar"
contest_url: "https://www.hackerrank.com/contests/noi-2023-mar"
problem_slug: "blah-blah-blah"
problem_url: "https://www.hackerrank.com/contests/noi-2023-mar/challenges/blah-blah-blah"
---

One day friend A went to his friend B's house and found N balls lying around, each with a value A[i] written on it. Being the ball lover that he was, he decided to put them all in a bucket.

But just as he was about to have some bucket-filling fun, B appeared out of nowhere like a math-loving superhero and said, "Hold up, boy! I'll buy you anything you want if you let me put some math in this party."

Confused but intrigued, A listened as B explained that if the bucket is empty, he can put a ball in it for free. But if it's not empty, he has to pick one ball from inside the bucket and another from outside and put them both in. The cost of doing this is GCD(a[i],a[j]). 
A asked what GCD meant, and B chuckled and gave him a quick lesson. "It's the biggest number that can divide both those values evenly," he said.
A's eyes lit up at the possibility of getting some sweet swag from his friend. he wanted to maximize the total cost, while B was hoping to minimize it. The battle was on.

So, how much did he end up getting from B?

## Input Format

The first line contains an integer $$N$$.  The second line contains $$N$$ space-separated integers denoting the elements of array $$A$$.

## Output Format

Print the Maximum total cost.

## Constraints

$$0 \lt N \le 100000$$  
$$1 \lt A_i \le 10 ^ 5$$

### Sample Input 0

```
3
4 6 9
```

### Sample Output 0

```
5
```
