---
title: "Suvin's Game of Cards"
year: 2020
category: finals
round: "Final Round — Day 1"
sortkey: "3-finals-1-03"
index: 3
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka 2020 - Day 1"
contest_slug: "noi-2020-day-1"
contest_url: "https://www.hackerrank.com/contests/noi-2020-day-1"
problem_slug: "suvins-game-of-cards"
problem_url: "https://www.hackerrank.com/contests/noi-2020-day-1/challenges/suvins-game-of-cards"
---

Since Suvin has no friends, he has invented a new one player card game.

He has a collection of 100 packs of cards. He puts all these together, shuffles them and deals two rows of cards. Each row will have a random number of cards.

Only the ***4 suits[H(♥), D(♦), C(♣), S(♠)]*** of the cards matter in this game.

Here is an example of two rows dealt.  
```
H C C D  
H D S S D
```  
  
He needs to make both rows to be of same length while maximizing the total reward. But, each change to the rows has a cost. The final reward is equal to the sum of rewards of each pair of cards.  A pair of cards is the two cards in the same column.

For instance if the two rows are
```
H C C D
H D S D
```

The the pairs are ***(H, H), (C, D), (C, S), (D, D)***

The rewards for each combination of suits is given in the input.

The moves he can make are to remove a card and to change a card. The cost of changing and removing a card of each suit is given.

## Input Format

First line contains a string representing the first row and the second line is the string representing the second row.
The next ***4*** lines give a character and two integers separated by space, representing the suit, the cost of changing a card of that suit to any other suit, and the cost of removing a card of that suit, respectively.
The following ***10*** lines give two characters and an integer separated by a space, representing the combination suits and the reward for a pair of that combination.

## Output Format

Output the maximum of reward - cost you can get.

## Constraints

- **1 $$\leq$$ Length of a row $$\leq$$ 100**

### Sample Input 0

```
HCCD
HDSSD
S 1 1
H 2 1
D 1 2
C 2 2
S S 5
S H 0
S D 0
S C 0
H H 5
H D 0
H C 0
D D 5
D C 0
C C 5
```

### Sample Output 0

```
17
```
