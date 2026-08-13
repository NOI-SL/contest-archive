---
title: "No Electricity Hour"
year: 2022
category: monthly
round: "February 2022"
sortkey: "2-monthly-02-01"
index: 1
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - February 2022"
contest_slug: "noi-2022-feb"
contest_url: "https://www.hackerrank.com/contests/noi-2022-feb"
problem_slug: "no-electricity-hour"
problem_url: "https://www.hackerrank.com/contests/noi-2022-feb/challenges/no-electricity-hour"
---

There's a distant island named Ãkkåy Island, that uses a different timing convention. Unlike ours, this island has ***D*** days per month and ***H*** hours per day. The island is divided into ***S*** number of sections. This island is having a hard time finding fuel for electricty generation. So, to overcome this, they have decided to stop providing power for various sections of the island to control the fuel usage for power generation. So, the smart people in this island have come up with a plan, to stop power for different sections in different intervals. So, every section would loose power for one hour, after different number of hours(***Y<sub>s</sub>***). Due to this, there are some hours, where the whole island looses power. And the people on this island have begun to call this hour as "No Electricity Hour".  

Given a time of a no electricy hour(***T<sub>1</sub>***), you are supposed to find whether a given time(***T<sub>2</sub>***) is a no electricity hour. If it's not a no electricity hour, find ***X***, the number of hours to the closest no electricity hour.

## Input Format

First line contains **3** integers, ***D***, ***H*** & ***S*** describing the number of days per month, number of hours per day and number of sections in the island respectively.  
Next line contains ***S*** integers, ***Y<sub>1</sub>***, ***Y<sub>2</sub>***, ..., ***X<sub>n</sub>***, describing the number of hours between a power cut for each section.  
Next line contains **3** integers, ***m<sub>1</sub>***, ***d<sub>1</sub>***, ***h<sub>1</sub>***. The month, date and hour of ***T<sub>1</sub>*** respectively.  
Last line contains **3** integers, ***m<sub>2</sub>***, ***d<sub>2</sub>***, ***h<sub>2</sub>***. The month, date and hour of ***T<sub>2</sub>*** respectively.

## Output Format

If ***T<sub>2</sub>*** is a Full Moon Day, print “***NO ELECTRICITY HOUR***”.  
If not, print a single positive integer ***X***, the number of hours to the closest no electricity hour.

## Constraints

If the number of hours between ***T<sub>1</sub>*** & ***T<sub>2</sub>*** is ***D***,  
  
- **1 $$\leq$$ D, H $$\leq$$ 10<sup>4</sup>**
- **1 $$\leq$$ S $$\leq$$ 10<sup>2</sup>**
- **1 $$\leq$$ Y<sub>s</sub> $$\leq$$ D * 3**
- **1 $$\leq$$ D $$\leq$$ 10<sup>8</sup>**
- **1 $$\leq$$ m<sub>1</sub>, m<sub>2</sub> $$\leq$$ 10<sup>8</sup>**
- **1 $$\leq$$ d<sub>1</sub>, d<sub>2</sub> $$\leq$$ D**
- **1 $$\leq$$ h<sub>1</sub>, h<sub>2</sub> $$\leq$$ H**
  &nbsp;  
   
#### **Limits**
- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
30 24 1
26
2 24 8
2 25 10
```

### Sample Output 0

```
NO ELECTRICITY HOUR
```

### Sample Input 1

```
20 12 2
3 2
2 1 1
2 1 12
```

### Sample Output 1

```
1
```
