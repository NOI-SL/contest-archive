---
title: "Love in times of Corona"
year: 2020
category: qualifier
round: "Selection Test"
sortkey: "1-qualifier-02"
index: 2
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - Screening Test 2020"
contest_slug: "noi-2020-selection-test"
contest_url: "https://www.hackerrank.com/contests/noi-2020-selection-test"
problem_slug: "love-in-times-of-corona"
problem_url: "https://www.hackerrank.com/contests/noi-2020-selection-test/challenges/love-in-times-of-corona"
---

Jameel and Asma are a couple. They met in an A/L tuition class. Initially the class was held in a big hall for many students. But once COVID happened, the government came up with two regulations  

1. Larger tuition classes have to be split into smaller classes.
2. Every smaller class should have one hand sanitizer at the entrance.


Students have to stay in a queue in front of the entrance at 7am everyday (minding the 1m distance). There are ***N*** classes and therefore ***N*** hand sanitizers near the entrance. The ***i <sup>th</sup>*** hand sanitizer takes ***S<sub>i</sub>*** seconds to sanitize a person.  
   
Students have to go to the first sanitizer that gets vacant. If a student uses the ***i <sup>th</sup>*** sanitizer, s/he has to go to the ***i <sup>th</sup>*** classroom. Students usually go to the sanitizer with lowest ***i*** if more than one sanitizer is vacant. If Jameel and Asma are on ***J*** and ***A*** positions of the queue, can they go to the same class? Print the answer as ***YES*** or ***NO***.

## Input Format

First line contains a single integer ***T*** denoting the number of test cases.  
Then there are ***T*** of the following form,  
First line has ***N***, an integer denoting the number of hand sanitizers.  
Next line contains two integers ***J*** and ***A*** denoting the locations of Jameel and Asma in the queue.  
The next contains ***N*** integers, ***S<sub>1</sub>, S<sub>2</sub>, S<sub>3</sub> ,...S<sub>N</sub>*** denoting the time a sanitizer takes to sanitize a person's hands.

## Output Format

***T*** lines, one line for each test case containing ***YES*** or ***NO*** according to whether Jameel and Asma can go to the same class.

## Constraints

- ***1 $$\leq$$ T $$\leq$$ 20***
- ***1 $$\leq$$ N<sub>i</sub> $$\leq$$ 5000***
- ***1 $$\leq$$ J, A $$<$$ 10<sup>12</sup>***
- ***0 $$\leq$$ S<sub>i</sub> $$<$$ 100***  
   
#### **Limits**
- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
1
1
10 50
100
```

### Sample Output 0

```
YES
```

### Sample Input 1

```
3
2
3 4
10 5
2
2 6
10 5
3
2 8
10 5 5
```

### Sample Output 1

```
NO
YES
NO
```
