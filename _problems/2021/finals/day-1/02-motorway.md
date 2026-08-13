---
title: "Motorway"
year: 2021
category: finals
round: "Final Round — Day 1"
sortkey: "3-finals-1-02"
index: 2
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka 2021 - Day 1"
contest_slug: "noi-2021-day-1"
contest_url: "https://www.hackerrank.com/contests/noi-2021-day-1"
problem_slug: "motorway"
problem_url: "https://www.hackerrank.com/contests/noi-2021-day-1/challenges/motorway"
---

King Unumagudut ruled Aknalirs in 150 BC. One day he woke out of bed discovering motorways. He wanted to build a motorway from the south of the country to the north connecting ***N*** cities, and the motorway consists of **2 one way roads**. The travellers can enter the motorway from each city to travel either north or south. Cities are numbered from ***1*** to ***N*** starting from the southern city to the northern city.  
  
King Unumagudut wanted to be perceived as generous to the citizens and came up with a new way of giving money to  travellers:  

- The king associated an integer for each city in the northboard road (one-way road going from south to north).
- Similarly the king associated an integer for each city in the southbound road (one-way road going from north to south).
- When travellers entered the northbound road from a city they were given an amount of gold coins that equal to the associated value of that entering city of the northbound road.
- But when they exited from a city they had to pay an amount of gold coins that equal to the associated value of the existing city of the northbound road.  
- Similarly when they were travelling the southbound road:  
	- they received gold coins equal to the associated value of the entering city of the southbound road, and  
	- they had to pay back gold coins equal to the associated value of the exiting city of the southbound road.  
- Travellers were not allowed to change the direction (take U-turns) without exiting from a city and then entering back.  
  
Given ***N*** and above values of the cities, you are asked to calculate the number of pairs of cities where traveling from the northern city to the southern city (in the southbound road) is more beneficial than traveling from the southern city to the northern city (in the northbound road).

## Input Format

First line contains a single integer, ***N***  
Next ***N*** lines contain associated values of city ***1*** to ***N***, in that order. Each of those lines will contain ***2*** integers separated by a space  

- The first integer, ***R<sub>1</sub>*** is the associated value of northbound road  
- The second integer, ***R<sub>2</sub>*** is the associated value of the southbound road.

## Output Format

Print a single integer representing the number of city pairs whether travelling in the northbound road is more beneficial than the southbound road.

## Constraints

- **1 $$\leq$$ N $$\leq$$ 10<sup>6</sup>**  
- **0 $$\leq$$ R1, R2 $$\leq$$ 10<sup>9</sup>**  
  
#### **Subtasks**  

1. **(30 points)** - 1 $$\leq$$ N $$\leq$$ 10<sup>4</sup>  
2. **(20 points)** - 1 $$\leq$$ N $$\leq$$ 5 * 10<sup>5</sup> 
3. **(50 points)** - No additional constraints.  
   
#### **Limits**  

- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
4
4 1
3 4
5 2
7 3
```

### Sample Output 0

```
5
```
