---
title: "New Facebuk"
year: 2020
category: monthly
round: "June 2020"
sortkey: "2-monthly-06-02"
index: 2
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - June 2020"
contest_slug: "noi-2020-jun"
contest_url: "https://www.hackerrank.com/contests/noi-2020-jun"
problem_slug: "new-facebuk"
problem_url: "https://www.hackerrank.com/contests/noi-2020-jun/challenges/new-facebuk"
---

You’re building a social network like Facebook, called “New Facebuk”. For this social network, you’re introducing a new method of connecting people.

When a person registers on New Facebuk, you ask their favorite sport and their hobby. Then your magical algorithm is going to add this new user to a set of groups (new or existing) based on the two inputs received at registration.

For any group with **size > 1**, any person in the group must have **at least one** other person with the **same hobby** or the **same favorite sport**.

- A new group can be formed with a newly registered user
- An existing group can be expanded by adding members to it **sequentially** , given that the above condition holds.

Since you’re still at the testing phase of this new social network, you want to explore how big the groups can get in different communities. Being a contestant at NOI 2020, there’s no better time to test this out than during a practice contest! 

Given a list with ***N*** users, along with their hobbies and favorite sports, find out the size of the largest group you can make.

**(To make it easy for you to process the input, the hobbies and sports are coded into integers of their own domains)**

## Input Format

First line contains a single integer ***N***, the total number of users.
Each of the next **N** lines contain two integers, ***H*** and ***S*** corresponding to the hobby and the favorite sport of each user.

## Output Format

A single line containing the **size of the largest group** you can make with the given list of users.

**Note: Size of group = Number of users in that group**

## Constraints

- **1 $$\leq$$ N $$\leq$$ 10<sup>6</sup>**
- **0 $$\leq$$ H,S $$\leq$$ 499**

### Sample Input 0

```
5
1 1 
2 5 
3 3 
4 4 
4 5 
```

### Sample Output 0

```
3
```
