---
title: "Bags O' Money"
year: 2022
category: monthly
round: "March 2022"
sortkey: "2-monthly-03-02"
index: 2
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - March 2022"
contest_slug: "noi-2022-mar"
contest_url: "https://www.hackerrank.com/contests/noi-2022-mar"
problem_slug: "bags-o-money"
problem_url: "https://www.hackerrank.com/contests/noi-2022-mar/challenges/bags-o-money"
---

Big Bank stores their money in bags, each containing a **distinct** amount of money. A gang of thieves are planning to rob the bank. The loot has to be **distributed evenly** between them to not risk the thieves snitching on each other. In that sense, they will not perform the heist if the money they loot cannot be divided evenly. The thieves can only carry **exactly two bags** with them so that there is minimal risk involved in the heist, and atleast two to make the heist worthwhile. 

The Bank Manager receives word of this. He plans to transport bags of money to a different branch so that the thieves cannot pull their plan off. Take the transportation cost of one bag to be one unit. What is the **maximum number of bags** he can keep in the bank so that the number of transportation units are minimal and the thieves will **not attempt** the heist?

## Input Format

- The first line contains two space separated integers, ***n*** denoting the number of money bags in the bank and ***T*** denoting the number of thieves in the gang.
- The second line contains space separated integers, each denoting amount of money in the ***i<sup>th</sup>*** bag ***M[i]***.

## Output Format

- Print the integer denoting the  maximum number of money bags that can be kept in the bank.

## Constraints

- 1 $$\leq$$ ***n*** $$\leq$$ 10<sup>5</sup>
- 1 $$\leq$$ ***T*** $$\leq$$ 100
- 1 $$\leq$$ ***M[i]*** $$\leq$$ 10<sup>9</sup>
- Amounts of money in bags are distinct.

### Sample Input 0

```
5 5
2 7 12 17 22
```

### Sample Output 0

```
5
```
