---
title: "COVID-19 and Cards 1"
year: 2020
category: qualifier
round: "Selection Test"
sortkey: "1-qualifier-05"
index: 5
max_score: 100
difficulty: "Hard"
contest_name: "National Olympiad in Informatics Sri Lanka - Screening Test 2020"
contest_slug: "noi-2020-selection-test"
contest_url: "https://www.hackerrank.com/contests/noi-2020-selection-test"
problem_slug: "covid-19-and-cards-1"
problem_url: "https://www.hackerrank.com/contests/noi-2020-selection-test/challenges/covid-19-and-cards-1"
---

Feeling lonely staying at home for a long time, Sumudu invented an interesting card game that she can play alone. The game is as follows:

- Take a deck of cards containing ***52*** cards, with ***13*** from each suit. *(**13** clubs ♣, **13** diamonds ♦, **13** hearts ♥ and **13** spades ♠)*
- Choose a random number ***T*** and randomly remove ***T*** cards from the deck
- Take the remaining ***52 - T*** cards to hand
- Pick a starting card and place it on the table
- Pick a card from hand and place it on top of the previously placed card
- Repeat the previous step as much as you want (of course you need to stop once you run out of cards in hand)
- Once you’re done placing cards, take the stack of cards on the table and calculate the score  
  
#### **Calculating the score:**

Each card carries some points. The final score is the sum of points of the cards, or zero if the stack does not obey the following rules.  
  
#### **Rules:**

1. The ordering precedence of the cards is ***J > 9 > A > 10 > K > Q > 8 > 7 > 6 > 5 > 4 > 3 > 2***
2. A card of lower precedence cannot be placed on top of a card of higher precedence
3. A red card cannot be followed by another red card, but a black card can be followed by another black card  
  
#### **Example points table:**

![image]({{ "/assets/problems/25b93cb7-1597446155-e65b759ea5-1597430671-d04d529456-Capture.png" | relative_url }})

#### **Task:**

Given ***52 - T*** cards and the points awarded for each card, determine the maximum score that Sumudu can get.  
  
*Note: Order of precedence of cards is fixed (described above). But the points awarded for different cards will vary (given as input), per test case.*

## Input Format

The first line contains ***13*** integers ( ***P<sub>i</sub>*** ), denoting the number of points for cards, from highest precedence to lowest precedence order.  
Second-line contains an integer ***T***, denoting the number of cards removed from the original deck.  
The third line contains two space-separated integers ***R*** and ***B*** ; ***R*** is the number of remaining ***RED*** cards, ***B*** is the number of remaining ***BLACK*** cards.  
The fourth line contains ***R*** space-separated strings, with the rank of each ***RED*** card.  
The fifth line contains ***B*** space-separated strings, with the rank of each ***BLACK*** card.

## Output Format

Print a single integer ***S***, denoting the maximum score that Sumudu can get.

## Constraints

- **0 $$\leq$$ T $$\leq$$ 51**  
- **0 $$\leq$$ P<sub>i</sub> $$\leq$$ 10<sup>4</sup>**  
   
#### **Limits**
- **Time Limit**: 2s
- **Memory Limit**: 512MB

### Sample Input 0

```
60 55 50 40 35 25 20 18 14 10 8 5 2
47
3 2
A 9 4
J 10
```

### Sample Output 0

```
163
```
