---
title: "Knight Rider"
year: 2021
category: finals
round: "Final Round — Day 2"
sortkey: "3-finals-2-03"
index: 3
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka 2021 - Day 2"
contest_slug: "noi-2021-day-2"
contest_url: "https://www.hackerrank.com/contests/noi-2021-day-2"
problem_slug: "knight-rider"
problem_url: "https://www.hackerrank.com/contests/noi-2021-day-2/challenges/knight-rider"
---

There’s a chess board. There is a white king, a white knight, some black pawns and some trees. The king has to eliminate all the pawns. The pawns are initially not on the board. The pawns fall on the board one by one in order. The first pawn falls on the board at the beginning, and as soon as the king eliminates that pawn the next one falls. Pawns don’t move after falling on the board.  
  
Trees never change their positions. The king can jump to any of the adjacent 8 squares, and it takes him a minute to jump. The king can remain in the same square (for any number of full minutes) without jumping. The knight can jump any of the 8 squares as shown in the diagram below. Knight also takes 1 minute to jump.  
  
Any two pieces can share the same square. But they can never be on a square with a tree or go beyond the borders of the board.  
  
**Possible movements for King**  
![image]({{ "/assets/problems/b6c10ba3-1622859484-9cd14aa4da-01king01.png" | relative_url }})  
&nbsp;  
&nbsp;    
**Possible movements for Knight**  
![image]({{ "/assets/problems/0bb50de1-1622859506-2bbba2d84b-02knight02.png" | relative_url }})  

At the start of each minute the king can instantly eliminate a pawn (if he’s sharing a square with a pawn) or instantly get on or off the knight (if he’s sharing a square with the knight), before moving. King can control the knight when he is on the knight. That is he, together with the knight, can jump to any of the 8 squares shown in the diagram above, or decide to stay on the same square. King cannot move to adjacent squares when he is on the knight. King can eliminate a pawn while he’s on a knight.

Knight has no intelligence. When the knight is on its own (at the beginning or after the king gets off the knight), it will move in the same direction it last moved for every minute until it cannot move in that direction (due to the chess board border or a tree). Then it will rotate its direction clockwise. (i.e. from 1 to 2, 5 to 6 or 8 to 1 - see above diagram) and try. At the very beginning the knight will start in direction 1. It is guaranteed that the knight will always be able to move in at least one direction.

You are given the size of the chess board, the position of the knight, and the king. You are also given the locations of the trees, and the order and the locations the pawns will fall into. You want to find the minimum time it will take the king to eliminate all the pawns.

## Input Format

- First line contains **R**, **C**; the number of rows and columns of the chess board.
- Next line contains **K<sub>R</sub>**, **K<sub>C</sub>**; the row and column of the king.
- Next line contains **N<sub>R</sub>**, **N<sub>C</sub>**; the row and column of the knight.
- Next line contains **T**; the number of trees
- Following **T** lines each contain **T<sub>Ri</sub>**, **T<sub>Ci</sub>**; the row and column of the trees.
- Next line contains **P**; the number of pawns
- Following **P** lines each contain **P<sub>Ri</sub>**, **P<sub>Ci</sub>**; the row and column of the pawns.
- All pawns and trees will have different locations.
- The rows are numbered from top to bottom starting from **1** and the columns are numbered from **left to right** starting from **1**.

## Output Format

Output a single integer, the minimum number of minutes it takes the king to eliminate all pawns. All pawns are guaranteed to be reachable by the king.

## Constraints

- **8 $$\leq$$ R $$\leq$$ 16**  
- **8 $$\leq$$ C $$\leq$$ 16**  
- **0 $$\leq$$ T $$\leq$$ 16**  
- **1 $$\leq$$ P $$\leq$$ 16**  

#### **Subtasks**  

1. **For 30% of the test cases**  
	- **P = 1** 
    - **R = 8** 
    - **C = 8**  
2. **For the next 20% of the test cases**  
    - **R = 8** 
    - **C = 8**   
3. **For the remaining test cases**  
	- No additional constraints. 
    
#### **Limits**  

- **Time Limit**: 2s
- **Memory Limit**: 256MB

### Sample Input 0

```
8 8
3 2
5 2
0
1
2 4
```

### Sample Output 0

```
2
```
