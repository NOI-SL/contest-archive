---
title: "Helani's Card Game"
year: 2022
category: finals
round: "Final Round — Day 2"
sortkey: "3-finals-2-01"
index: 1
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka 2022 - Day 2"
contest_slug: "noi-2022-day-2"
contest_url: "https://www.hackerrank.com/contests/noi-2022-day-2"
problem_slug: "helanis-card-game"
problem_url: "https://www.hackerrank.com/contests/noi-2022-day-2/challenges/helanis-card-game"
---

Helani, one of your friends, came up with a new game of playing cards to play with you during the school vacation. Helani would pick **2** cards from the card-pack and you have to create a path between the two cards using the rest of the cards in the card-pack. But the problem is that each card has its own cost. Both you and Helani will play the game and while Helani tries to create a path that increases the cost, your target is to keep the cost as low as possible.  
  
After picking the starting and ending cards, you will have to select a card from the card-pack  and place it after the starting card. Then it will be Helani’s chance to pick a card. Likewise the game will continue until a path has been formed between the initially picked cards. To increase the cost, Helani will always pick the card that has the highest cost.  
  
A pack of playing cards has **52** cards. Each card belongs to one of the following suits [1].  

1. Diamonds (♦) - **D**  
2. Clubs (♣) - **C**  
3. Hearts (♥) - **H**  
4. Spades (♠) - **S**  
  
The face values of the cards can be denoted in the following manner.  

1. Ace - **A**  
2. 2 - **2**  
3. 3 - **3**  
4. 4 - **4**  
5. 5 - **5**  
6. 6 - **6**  
7. 7 - **7**  
8. 8 - **8**  
9. 9 - **9**  
10. 10 - **10**  
11. Jack - **J**  
12. Queen - **Q**  
13. King - **K**  
  

![image]({{ "/assets/problems/9a282dbf-1560570716-6c5c07ee14-Fotolia_23299310_Subscription_Monthly_M.jpg" | relative_url }})  
  
Each individual card can be identified by the letter of the suit followed by the value of the card.  
  
Eg:  
  
- King of Clubs - “**CK**”  
- Ace of Diamond - “**DA**”  
- 3 of Hearts - “**H3**”  
- 10 of Spades - “**S10**”  
  
When constructing a path, there can be only 1 change from the following 2 types of changes made to any consecutive pair of cards.  
  
1. Increase or decrease the value by 1. Ace(A) can be used to go from a King to 2 or vice versa.  
	Example:  
  
	- King to 2: K -> A -> 2 -> 3  
	- King to 10: K -> Q -> J -> 10  
      
2. Change the current suit to 1 suit higher or lower and go in a circle in the order given above in [1].  
	Example:  
  
	- Clubs -> Hearts -> Spades -> Diamonds  
	- Clubs -> Diamonds -> Spades -> Hearts  
  
![image]({{ "/assets/problems/e2baf500-1656805583-2c21ce67bc-asd.png" | relative_url }})  
Each letter represents a suit and arrows represent to which suit you can change from your current suit.  

For example, these are possible ways to go from 10 of Diamonds (D10) to 9 of Hearts (H9).  
	  
	

-   D10 -> C10 -> H10 -> H9
- 	D10 -> D9 -> S9 -> H9
- 	D10 -> DJ -> CJ -> CQ -> HQ -> HJ -> SJ -> S10 -> S9 -> H9
  
   
   
Your task is to write a program to play the card game with Helani to find a path from the **2** given cards, which has the minimum cost.  
If there are multiple paths with the minimum cost, the one with the minimum number of cards should be selected.   
It is guaranteed that there are no multiple paths that have the minimum cost and the same no. of cards.  

This is an interactive problem. You have to complete the `start_game` & `play_turn` functions given in the editor.  
  
The function `start_game` receives **2** strings: `start` & `end` describing the starting and ending cards, and 4 lists: `diamonds`, `clubs`, `hearts`, and `spades`, each with **13** integers, values of the cards in that suit according to the order given above. (A, 2, 3, 4, 5, 6, 7, 8, 9, 10, J, Q, K).  
  
The function `play_turn` will receive a single string `card`, describing the last card in the path. In the first turn, it will be the starting card. In the following turns, it will be the card picked by  Helani. You have to return a string describing the next card you are selecting to build the path. If the card you returned is an invalid option, the program will exit immediately.  

If the sum of the cost of the whole card pack is ***S***, the score for each test case is calculated based on the cost of the path, using the following formula,

$ score = Min(\frac{S -\ cost\ of\ the\ path\ +\ ideal\ cost\ of\ the\ path}{S}, 1) \times 100\%$

## Input Format

***You should not read from the standard input, or else your solution will be considered as invalid.***  
The `start_game` function will receive a 6 arguments, 

1. ***start*** ( ***string*** ) - starting card of the path  
2. ***end*** ( ***string*** ) - ending card of the path  
3. ***diamonds*** ( ***int[]*** ) - values of the cards of diamonds suit
4. ***clubs*** ( ***int[]*** ) - values of the cards of clubs suit
5. ***hearts*** ( ***int[]*** ) - values of the cards of hearts suit
6. ***spades*** ( ***int[]*** ) - values of the cards of spades suit
  
The `play_turn` function will receive a single argument, 

1. ***card*** ( ***string*** ) - the last card in the path

## Output Format

***You should not write anything to the standard output, or else your solution will be considered as invalid.***  

The `start_game` function should not return anything. 

The `play_turn` function should return a `string` describing the next card for the path.    
    
    
#### **Data Types**
- **C++**
	- ***string*** - ```string```
    - ***int[ ]*** - ```vector<int>```
   
#### **Notes**
- You can learn more about functions through the following links ([C/C++](https://www.tutorialspoint.com/cplusplus/cpp_functions.htm)

## Constraints

- **0 $$\leq$$ cost of a card $$\leq$$ 10<sup>5</sup>**
- **2 $$\leq$$ L $$\leq$$ 52** - Total length of the path
- **1 $$\leq$$ C $$\leq$$ 10<sup>7</sup>** - Total cost of the path
  &nbsp;  
   
#### **Limits**
- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
D10 H9
61 74 78 62 34 83 85 66 21 1 2 6 35
56 46 99 22 95 82 58 84 25 53 43 10 38
33 57 87 80 75 37 88 77 7 11 4 3 72
100 39 23 101 67 41 42 44 8 49 9 12 85
```

### Sample Output 0

```
4 67
D10 S10 H10 H9 
```
