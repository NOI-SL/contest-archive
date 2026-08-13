---
title: "Segment Processor"
year: 2020
category: monthly
round: "March 2020"
sortkey: "2-monthly-03-04"
index: 4
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - March 2020"
contest_slug: "noi-2020-mar"
contest_url: "https://www.hackerrank.com/contests/noi-2020-mar"
problem_slug: "segment-processor"
problem_url: "https://www.hackerrank.com/contests/noi-2020-mar/challenges/segment-processor"
---

Dilshan is working with a new supercomputer that can run the same program multiple times simultaneously (at the same time). Dilshan has ***N*** lists of numbers, and wants to calculate the sum of each number list, using the supercomputer.  
  
He wrote two programs to get this done. **mainProgram** calls **getSumOfSet** program ***N*** times (simultaneously).
  
**mainProgram** accepts **3** parameters.  

- ***S*** - the length of a single list
- ***startingPositions*** - a list containing the starting positions of the N lists
- ***input*** - a list containing all the numbers  
  &nbsp;
  
**getSumOfSet** program accepts **3** parameters.  

- ***S*** - number of elements to be added from input 
- ***startingPosition*** - index of the first number in the sequence
- ***Input*** - the list containing all the numbers
  &nbsp;
  
```java
mainProgram ( int S, int startingPositions [ ],  int input [ ] ) {
	for each startingPosition in startingPositions:
		call getSumOfSet( S, startingPosition, input )
}
```

```java
getSumOfSet ( int S, int startingPosition, int input[  ] ) {
	BigInt ans = 0;
	for(int i = 0; i < S; i++) {
		ans += input[ startingPosition + i];
	}
	print ans;
}
```

Notice that ***S*** is the same for all calls to the **getSumOfSet** program. Hence he needs your help to prepare the input parameters to be sent to **mainProgram**.
  
You are allowed to modify the original ***N*** lists of numbers in order to meet the input criteria of **mainProgram**.

## Input Format

First line contains a single integer ***N*** ,  the number of lists.  
Next line contains ***N*** integers, with ***i<sup> th</sup>*** of them being ***C<sub>i</sub>*** .  
***N*** lines follow, with the ***i<sup> th</sup>*** line having ***C<sub>i</sub>*** space separated integers and the ***j<sup> th</sup>*** of them being ***V<sub>i , j</sub>*** .

## Output Format

First line should contain a single integer, ***S***, the length of a number set.  
Next line should contain ***N*** integers, the starting positions for each number set(***startingPositions***).  
Third line should contain a list of integers (***N x S*** maximum length), the newly prepared list of numbers (***input***).   
  
*Note: the sequence is indexed from 0.*

## Constraints

- **1 $$\leq$$ N $$\leq$$ 10<sup>5</sup>**
- **1 $$\leq$$ C<sub>i</sub> $$\leq$$ 10<sup>3</sup>**
- **-10<sup>8</sup> $$\leq$$ V<sub>i, j</sub> $$\leq$$ 10<sup>8</sup>**
  &nbsp;  
   
#### **Limits**
- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
3
3 3 3
3 2 1
4 5 6
9 8 7
```

### Sample Output 0

```
3
0 3 6 
3 2 1 4 5 6 9 8 7 
```

### Sample Input 1

```
3
5 2 3
4 3 2 1 0
5 6
9 8 7
```

### Sample Output 1

```
5
0 5 10 
4 3 2 1 0 5 6 -5 3 2 9 8 7 -8 8 
```

### Sample Input 2

```
1
5 1000 100 900
10 10
20 10
30 10
40 10
50 10
```

### Sample Output 2

```
4 800
```
