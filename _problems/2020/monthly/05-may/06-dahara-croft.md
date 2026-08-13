---
title: "Dahara Croft"
year: 2020
category: monthly
round: "May 2020"
sortkey: "2-monthly-05-06"
index: 6
max_score: 100
difficulty: "Easy"
contest_name: "National Olympiad in Informatics Sri Lanka - May 2020"
contest_slug: "noi-2020-may"
contest_url: "https://www.hackerrank.com/contests/noi-2020-may"
problem_slug: "dahara-croft"
problem_url: "https://www.hackerrank.com/contests/noi-2020-may/challenges/dahara-croft"
---

Dahara is playing a video game where in each level, she has to unlock a door to collect the treasure and reach the next level.  
  
Each door has a digital lock which can be unlocked by entering a password (PIN) with ***N*** number of digits. When Dahara enters a password into the lock, one of the following can happen.

1. The display of the lock will show number ***0***, and the door will open  
2. The display of the lock will show number ***1***, indicating the password is greater than the entered value  
3. The display of the lock will show number ***-1***, indicating the password is less than the entered value  
4. The display of the lock will show number ***-2***, indicating that the maximum number of consecutive attempts has reached  
  
Dahara has only ***X*** number of attempts to guess and enter the password. If she doesn’t enter the correct password within ***X*** number of attempts, she loses the game and has to start from the beginning. In addition, if Dahara figures out the password without using all the attempts, the game offers bonus points.  
  
Being the genius she is, she decided to write a computer program to find the password with the minimum number of attempts. And she’s asking your help to complete the program.  
  
This is an interactive problem. You have to complete the ```solve``` function given in the editor. You can call the function ```attempt``` with the password you want to try. It will return an integer, that can be one of the following 4 values,

- ***0*** - Password correct. You shouldn’t do anything after this.
- ***1*** - Correct Password is greater than the password you attempted.
- ***-1*** - Correct password is lesser than the password you attempted.
- ***-2*** - You either attempted a password that is of wrong length or you exceeded the maximum number of attempts. You shouldn’t do anything after this.
  
The score for each test case is calculated based on the number of attempts you used, using the following formula, 

$ score = \frac{X -\ no.\ of\ attempts}{X - log_2(10^N - 1)} \times 100\%$

## Input Format

**You should not read from the standard input, or else your solution will be considered as invalid.**  
The solve function will receive 2 arguments,  

1. ***N*** (***int***) - number of digits in the password
2. ***X*** (***int64***) - maximum number of attempts

## Output Format

**You should not write anything to the standard output, or else your solution will be considered as invalid.**  
The attempt function will accept a single argument, 

1. ***password*** (***string***) - the password you are attempting

This function will return an ***int*** denoting the result as explained above.  
   
#### **Data Types**
- **C/C++**
	- ***int*** - ```int```
    - ***int64*** - ```long long```
    - ***string*** - ```string```
- **Java**
	- ***int*** - ```int```
    - ***int64*** - ```long```
    - ***string*** - ```String```
   
#### **Notes**
- You can learn more about functions through the following links ([C/C++](https://www.tutorialspoint.com/cplusplus/cpp_functions.htm) / [Java](https://www.tutorialspoint.com/java/java_methods.htm))
- Contestants who use **C** language should select **C++** as the language.

## Constraints

- **1 $$\leq$$ N $$\leq$$ 16**  
- **1 $$\leq$$ X $$\leq$$ 10<sup>16</sup>**  
- Editing the source code above or below the mentioned points will mark the submission as a wrong answer
   
#### **Limits**
- **Time Limit**: 4s
- **Memory Limit**: 512MB

### Sample Input 0

```
1 10
4
```

### Sample Output 0

```
1 1 0
```

### Sample Input 1

```
2 60
11
```

### Sample Output 1

```
1 1 0
```
