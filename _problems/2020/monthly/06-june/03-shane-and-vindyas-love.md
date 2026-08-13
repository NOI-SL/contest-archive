---
title: "Shane and Vindya’s Love"
year: 2020
category: monthly
round: "June 2020"
sortkey: "2-monthly-06-03"
index: 3
max_score: 0
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - June 2020"
contest_slug: "noi-2020-jun"
contest_url: "https://www.hackerrank.com/contests/noi-2020-jun"
problem_slug: "shane-and-vindyas-love"
problem_url: "https://www.hackerrank.com/contests/noi-2020-jun/challenges/shane-and-vindyas-love"
---

Shane and Vindya are a romantic couple who are constantly in touch with each other. But Vindya’s father doesn’t approve this affair. Although Vindya’s father always blames, her feelings are too strong and therefore she cannot stop sending text messages with Shane.

Luckily Vindya’s father allowed Vindya to use a simple cellphone which does not have an internet connection. But Vindya’s father gave her a warning that if she would send love messages(SMS) then her mobile phone would be taken back. Shane, an intelligent young boy suggested a secret encoding system that Vindya and himself can use to send and receive messages. They simply add many random letters in the message and then jumble the letters of different words together (shown in example) so anyone else will not be able to read the messages. But they do not jumble the letters of the same words and thus order of the letters in a certain word is preserved. 

After several months Vindya’s father was suspicious abouth Vindya and started to read her text messages. Obviously he couldn’t read them. But he realized this is a secret code and wanted to see if these messages are love letters. In order to do so he came up with a clever technique

Count the maximum possible number of times the words “love” and ”like” (lovely words) have appeared in the message. In other words, he can eliminate some of the letters such that the above words are created. But the letters should be eliminated in such a way that it maximizes the total number of above words in the extracted message.

Your task is to help Vindya’s father find out the number of times the above words might have appeared in the message. If there are multiple combinations of words you can extract from the given message you have to give the largest answer.

## Input Format

N – First Line contains N which gives the number of letters in the given message
S – Second Line contains S which gives you a String representing the message. For simplicity all the spaces and ‘\n’(endline characters) are eliminated. Furthermore,the entire message is given in lowercase alphabetic letters.

## Output Format

A single integer containing the number of times the lovely words might have appeared in the message.

## Constraints

- **1 $$\leq$$ N $$\leq$$ 10<sup>7</sup>**

### Sample Input 0

```
20
exlaiodvkeslilsakbse
```

### Sample Output 0

```
2
```
