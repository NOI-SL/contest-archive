---
title: "King Siripala’s Forts"
year: 2020
category: monthly
round: "February 2020"
sortkey: "2-monthly-02-03"
index: 3
max_score: 100
difficulty: "Hard"
contest_name: "National Olympiad in Informatics Sri Lanka - February 2020"
contest_slug: "noi-2020-feb"
contest_url: "https://www.hackerrank.com/contests/noi-2020-feb"
problem_slug: "king-siripalas-forts"
problem_url: "https://www.hackerrank.com/contests/noi-2020-feb/challenges/king-siripalas-forts"
---

King Siripala the Conqueror loves to build forts on the islands he has conquered. As his chief architect, you are asked to provide him with as many fort designs as possible whenever he conquers an island.

Each island is a rectangle of positive integer dimensions which is divided into 1 x 1 land plots. A design is a rectangle covering a whole number of land plots. The borders of the design must not split any land plots. Two designs are the same if they cover the same set of rectangles, and different otherwise.

For example, an island with dimensions ***3 x 2*** has ***18*** different fort designs:

![image]({{ "/assets/problems/a2cea964-1580026718-4158118756-KingSiripalasForts.png" | relative_url }})

For **each design** you provide, King Siripala pays you **one** gold coin.

As an architect, your dream is to build a palace of your own. You have a number of designs for your dream palace, and you want to find out the smallest possible area of an island King Siripala could conquer that would allow you to build a palace costing ***n*** gold coins.

## Input Format

A single line, containing a single integer ***n***.

## Output Format

A single line, containing an integer ***A***, where ***A*** is the smallest possible area of an island King Siripala could conquer that would net you at least ***n*** gold coins.

## Constraints

- ***1 $$\leq$$ n $$\leq$$ 10<sup>7</sup>***  &nbsp; (***N*** is greater than or equal to ***1*** and less than or equal to ***10<sup>7</sup>***)

### Sample Input 0

```
18
```

### Sample Output 0

```
6
```

### Sample Input 1

```
8
```

### Sample Output 1

```
4
```
