---
title: "Tsunami Alert"
year: 2020
category: qualifier
round: "Selection Test"
sortkey: "1-qualifier-01"
index: 1
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - Screening Test 2020"
contest_slug: "noi-2020-selection-test"
contest_url: "https://www.hackerrank.com/contests/noi-2020-selection-test"
problem_slug: "tsunami-alert"
problem_url: "https://www.hackerrank.com/contests/noi-2020-selection-test/challenges/tsunami-alert"
---

*Pico* is a small island in *planetX*. People who currently live on this planet only use social media to connect with their friends. One unfortunate day, you receive a warning alert about a Tsunami that can affect many parts of the island. You have to warn people living on the island to reach safe sites as soon as possible.  
  
You are working at the Government Disaster Management Unit. Since you’re busy, you only have time to warn a single person. Once you send the warning, the receiver will share the warning with his/her friends through the social network. The friends will then again share it with their friends. This will happen until all possible persons are informed through friendship connections. (*Assume that everyone who receives the warning message will share it with all his/her friends immediately .*)  
  
But as you see, there can be certain clusters of people who will not receive this message because they do not have any connections with the people who receive the message.  
  
Your goal is to maximize the number of people who will receive the warning message by wisely choosing the right person to send the initial message. Since you are working in the government, you can easily connect with anyone on the island.  
  
You need to print a single integer indicating the maximum number of people who will ultimately receive your message.  
  
Note: Friendship is bi-directional. If ***A*** is friends with ***B***, ***B*** is also friends with ***A***.

## Input Format

First line contains the number of people in the Island except you. These people are indexed from ***0*** to ***N-1***  
The next ***2 &ast; N*** lines follow the details about the social media friends of the people in order. Two lines are dedicated to describe the friends of each person as follows.  

- First line of these two lines contains ***n<sub>p</sub>*** , the number of friends of ***p<sup>th</sup>*** person 
- The next line contains ***n<sub>p</sub>*** space separated integers. If ***p<sup>th</sup>*** person has no friends this line will contain ***-1***.

## Output Format

One line containing the maximum number of people who will ultimately receive your message.

## Constraints

- ***1 $$\leq$$ N $$\leq$$ 10<sup>3</sup>***  
- ***0 $$<$$ A<sub>i</sub> $$<$$ 10<sup>3</sup>***  
   
#### **Limits**
- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
5
2
1 2
2
0 2
2
1 2
1
4
1
3
```

### Sample Output 0

```
3
```

### Sample Input 1

```
10
1
1
2
0 2
2
1 3
2
2 4
1
3
1
6
2
5 7
2
6 8
1
7
0
-1
```

### Sample Output 1

```
5
```
