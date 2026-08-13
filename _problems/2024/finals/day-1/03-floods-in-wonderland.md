---
title: "Floods!"
year: 2024
category: finals
round: "Final Round — Day 1"
sortkey: "3-finals-1-03"
index: 3
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka 2024 - Day 1"
contest_slug: "noi-2024-day-1"
contest_url: "https://www.hackerrank.com/contests/noi-2024-day-1"
problem_slug: "floods-in-wonderland"
problem_url: "https://www.hackerrank.com/contests/noi-2024-day-1/challenges/floods-in-wonderland"
---

Wonderland has a well-known city called the Land of Gems. During the heavy rainy season, this city experiences severe flooding, leading to the displacement of most of its residents. Many residents have moved to safer areas, but those who remained have gathered in small groups on elevated locations to avoid the floodwaters.

The disaster management team plans to relocate all these groups to one of the existing elevated locations to facilitate the distribution of essential supplies like food. Given Wonderland's limited resources, including a scarcity of boats, the team considers first combining smaller groups into larger ones before bringing everyone together at a final location.

**Condition:**
•	People from a maximum of ***$$M$$*** other groups can be relocated to one destination.

**Assumptions:**
•	The time required to transfer people from one location to another is proportional to the number of people being moved and it is one time unit per person.

**Objective:**
•	The disaster management team needs to devise a strategy to minimize the time required to consolidate all groups into a single final group, considering the above assumptions and conditions.

## Input Format

•	The first line contains an integer ***$$N$$***, representing the number of elevated places.

•	The second line contains $$N$$ space-separated integers 
**$$a_1,a_2,…,a_n (1 ≤ a_i ≤ 10^9$$**), denoting the initial number of people at each location.

•	The third line contains an integer **$$Q$$**, indicating the number of queries.

•	The fourth line contains space-separated integers **$$m_1,m_2,…,m_q (1 ≤ m_i ≤ 10^5$$**), representing the values for the queries. Note that **$$m_i$$** values may repeat.

## Output Format

Print **$$Q$$** space-separated integers, each representing the minimum time taken to bring all people to a final destination in time units for the corresponding query, in the order the queries are given.

## Constraints

- $$1 ≤ N ≤ 10^5$$
- $$1 ≤ Q ≤ 10^5$$


**Subtask 1 (5 Marks)**

- $$Q=1 \text{ and } m_1 = N-1$$

**Subtask 2 (10 Marks)**

- $$Q=1 \text{ and } m_1 = 2 \text{ and } a_i =1 \text{ for all } 1≤i≤N-1$$ 

**Subtask 3 (15 Marks)**

- $$Q=1 \text{ and } m_1 =2$$ 

**Subtask 4 (70 Marks)**

No Additional Constraints.

   
#### **Limits**
- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
4
1 1 1 2
3
3 2 1
```

### Sample Output 0

```
3 4 6
```

### Sample Input 1

```
5
1 2 3 4 5
2
2 3
```

### Sample Output 1

```
13 11
```
