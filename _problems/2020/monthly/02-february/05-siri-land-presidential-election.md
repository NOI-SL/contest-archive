---
title: "Siri Land's Presidential Election"
year: 2020
category: monthly
round: "February 2020"
sortkey: "2-monthly-02-05"
index: 5
max_score: 0
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - February 2020"
contest_slug: "noi-2020-feb"
contest_url: "https://www.hackerrank.com/contests/noi-2020-feb"
problem_slug: "siri-land-presidential-election"
problem_url: "https://www.hackerrank.com/contests/noi-2020-feb/challenges/siri-land-presidential-election"
---

# There's a problem with this question and submissions to this task won't be counted for the final score. Read the notification for more info.  
  
   
Siri Land is a peaceful and technologically advanced country. The Election Commissioner of Siri Land has called a Presidential Election. Since too many people are contesting, instead of a lengthy voting sheet the election commission has proposed an electronic system. As you are a young smart programmer the Election Commission seeks your help in implementing an algorithm which counts the votes and finds the winner fast.  
  
##### **Election rules**
  
1. There are ***n*** number of contestants  
2. Voters can choose first preference and second preference  
3. Firstly, the first preferences are counted. If one contestant is able to take more than ***50%*** of votes he will be the winner   
4. If the first preference does not choose the winner, **all the contestants except the highest two vote gainers**(say A, B) will be eliminated.  
5. Then the second preference is counted. If the second choice of the eliminated votes are received by A or B that relevant counts are also being added to A,B contestants.  
6. If the above count also ties, then the winner is chosen by tossing a coin  

For simplicity the names are ignored in our counting system. Contestants are numbered from ***1*** to ***n***

## Input Format

First line contains 2 integers, ***n*** (number of contestants) & ***m*** (number of voters).  
***m*** lines follow, each with two space separated integers ***p<sub>1</sub>*** (first preference) and ***p<sub>2</sub>*** (second preference)  
  
Assume all the voters have given both preference

## Output Format

If there's a wining contestant, the program should out put the ***number of the winning contestants***.
If no one wins, the program should output "***Toss a coin and find the winner***"

## Constraints

- **1 $$\leq$$ n $$\leq$$ m $$\leq$$ 10<sup>16</sup>**
- **1 $$\leq$$ p<sub>1</sub>, p<sub>2</sub> $$\leq$$ n**
  &nbsp;  
   
#### **Limits**
- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
5
10
1 2
1 3
1 4
2 1
3 1
1 5
2 3
2 5
3 2
4 3
```

### Sample Output 0

```
1
```

### Sample Input 1

```
4
4
1 2
1 2
3 2
4 3
```

### Sample Output 1

```
Toss a coin and find the winner
```
