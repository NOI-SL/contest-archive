---
title: "Ball queries"
year: 2024
category: qualifier
round: "Qualifier Round"
sortkey: "1-qualifier-02"
index: 2
max_score: 100
difficulty: "Medium"
contest_name: "NOI 2024 Qualifier Round"
contest_slug: "noi-2024-qualifier-round"
contest_url: "https://www.hackerrank.com/contests/noi-2024-qualifier-round"
problem_slug: "ball-queries"
problem_url: "https://www.hackerrank.com/contests/noi-2024-qualifier-round/challenges/ball-queries"
---

There are $$N$$ buckets of balls in a row. The $${i}^{th}$$ bucket contains $$A_i$$ balls. You are given $$Q$$ queries. The $${i}^{th}$$ query consists of three integers $$l_i$$, $$r_i$$ and $$x_i$$ — take $$x_i$$ balls from all buckets with indices between $$l_i$$ and $$r_i$$. If some bucket contains less than $$x_i$$ balls, you just take all the remaining balls from this bucket.

Your task is to say for each bucket the index of query after which this bucket becomes empty

## Input Format

The first line of the input contains two integers $$N$$ and $$Q$$ the number of bucket of balls and the number of queries, respectively.

The second line of the input contains $$N$$ integers $$a_1,a_2,…,a_n$$ where $$a_i$$ is the number of balls in the $${i}^{th}$$ bucket.

The next $$Q$$ lines describe queries. The $${i}^{th}$$ query consists of three integers $$l_i$$, $$r_i$$ and $$x_i$$, where $$l_i$$ and $$r_i$$ are borders of the segment and $$x_i$$ is the number of balls you have to take.

## Output Format

Print $$N$$ integers — for each bucket in order of the input print the index of query after which this bucket becomes empty (or -1 if the bucket will not be empty after all queries).

## Constraints

$$1 \lt A_i \le 10 ^ 9$$  
$$1 \lt N\ ,\ Q \le 10 ^ 5$$  
$$1 \lt X_i \le 10^9$$  
$$1 \lt l_i\ ,\ r_i \le N$$

### Sample Input 0

```
2 2
1 1
1 1 1
1 2 1
```

### Sample Output 0

```
1 2
```
