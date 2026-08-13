---
title: "Number Passing"
year: 2020
category: qualifier
round: "Selection Test"
sortkey: "1-qualifier-04"
index: 4
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - Screening Test 2020"
contest_slug: "noi-2020-selection-test"
contest_url: "https://www.hackerrank.com/contests/noi-2020-selection-test"
problem_slug: "number-passing"
problem_url: "https://www.hackerrank.com/contests/noi-2020-selection-test/challenges/number-passing"
---

Kasun & Damith has developed a new communication medium to send messages between each other. But, so far they could only build a system that can transfer a list of messages between each other. Unfortunately, due to network conditions, one number might not get sent. But they think that they should be able to figure out the missing number, by adding a couple of extra numbers to the list before sending it. 

Kasun and Damith are asking your help to implement this system to their messaging system. 

This is an interactive problem. You have to complete the ```encode_message``` & ```decode_message``` functions given in the editor. The function ```encode_message``` will receive a list of N numbers and you have to return a list of numbers with extra numbers from that function. The function ```decode_message``` will receive a list of numbers returned from the ```encode_message``` message function. But sometimes it will have a missing number. You have to return the correct list of numbers returned from the ```encode_message``` function. 

The score for each test case is calculated based on the number of extra numbers you added to the list, using the following formula, 

$ score = Min(\frac{N -\ no.\ of\ extra\ numbers + 1}{N}, 1) \times 100\%$

## Input Format

***You should not read from the standard input, or else your solution will be considered as invalid.***  
The ```encode_message``` function will receive a single argument, 

1. ***A[N]*** ( ***int[ ]*** ) - list of N numbers  
  
The ```decode_message``` function will receive a single argument, 

1. ***A[ ]*** ( ***int[ ]*** ) - list of numbers

## Output Format

***You should not write anything to the standard output, or else your solution will be considered as invalid.***  

The ```encode_message``` function should return a list of numbers. 

The ```decode_message``` function should return the original set of numbers returned from the ```encode_message``` function.  
   
#### **Data Types**
- **C/C++**
	- ***int*** - ```int```
    - ***int[ ]*** - ```vector<int>```
- **Java**
	- ***int*** - ```int```
    - ***int[ ]*** - ```List<Integer>```
   
#### **Notes**
- You can learn more about functions through the following links ([C/C++](https://www.tutorialspoint.com/cplusplus/cpp_functions.htm) / [Java](https://www.tutorialspoint.com/java/java_methods.htm))
- Contestants who use **C** language should select **C++** as the language.

## Constraints

- **1 $$\leq$$ N $$\leq$$ 10<sup>6</sup>**  
- **1 $$\leq$$ A<sub>i</sub> $$\leq$$ 10<sup>8</sup>**  
- Editing the source code above or below the mentioned points will mark the submission as a wrong answer
   
#### **Limits**
- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
2
3 2
1 3 5
4 0
9 8 7 11
```

### Sample Output 0

```
2
4 4
1 3 5 7 
1 5 7 3 
5 5
9 8 7 11 13 
9 8 7 11 13 
```
