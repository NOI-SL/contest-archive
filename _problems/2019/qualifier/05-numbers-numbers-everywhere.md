---
title: "Numbers Numbers Everywhere!"
year: 2019
category: qualifier
round: "Selection Test"
sortkey: "1-qualifier-05"
index: 5
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - Screening Test"
contest_slug: "noi-2019-selection-test"
contest_url: "https://www.hackerrank.com/contests/noi-2019-selection-test"
problem_slug: "numbers-numbers-everywhere"
problem_url: "https://www.hackerrank.com/contests/noi-2019-selection-test/challenges/numbers-numbers-everywhere"
---

Given an integer **N**, output it in **words**.

Rules to print the words:

1. All letters should be printed in **lowercase**
2. Use only the **following words**, each separated by a space to generate the output  
   
|       	|           	|         	|          	|   	|
|-----------|---------------|-----------|-----------|---	|
|  zero 	|    ten    	|  twenty 	|  hundred 	|   	|
|  one  	|   eleven  	|  thirty 	| thousand 	|   	|
|  two  	|   twelve  	|  forty  	|  million 	|   	|
| three 	|  thirteen 	|  fifty  	|  billion 	|   	|
| four  	| fourteen  	| sixty   	|          	|   	|
| five  	| fifteen   	| seventy 	|          	|   	|
| six   	| sixteen   	| eighty  	|          	|   	|
| seven 	| seventeen 	| ninety  	|          	|   	|
| eight 	| eighteen  	|         	|          	|   	|
| nine  	| nineteen  	|         	|          	|   	|
&nbsp;

## Input Format

A single integer **N**.

## Output Format

**N** in **words**.

## Constraints

- **0 $$\leq$$ N $$\leq$$ 10<sup>9</sup>**

### Sample Input 0

```
13
```

### Sample Output 0

```
thirteen
```

### Sample Input 1

```
70
```

### Sample Output 1

```
seventy
```

### Sample Input 2

```
94
```

### Sample Output 2

```
ninety four
```

### Sample Input 3

```
100
```

### Sample Output 3

```
one hundred
```

### Sample Input 4

```
123456789
```

### Sample Output 4

```
one hundred twenty three million four hundred fifty six thousand seven hundred eighty nine
```

### Sample Input 5

```
1000000000
```

### Sample Output 5

```
one billion
```

### Sample Input 6

```
1111
```

### Sample Output 6

```
one thousand one hundred eleven
```
