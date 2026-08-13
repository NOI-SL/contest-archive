---
title: "Study Groups for IOI"
year: 2020
category: monthly
round: "May 2020"
sortkey: "2-monthly-05-04"
index: 4
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka - May 2020"
contest_slug: "noi-2020-may"
contest_url: "https://www.hackerrank.com/contests/noi-2020-may"
problem_slug: "study-groups-for-ioi"
problem_url: "https://www.hackerrank.com/contests/noi-2020-may/challenges/study-groups-for-ioi"
---

Students attending IOI practices at UCSC are standing on a tile grid (everyone is in the center of the tile. No two students are in the same tile.). Two trainers (P and Q) are looking at the students from the bottom right and left points of the tiled grid. The trainers know the registration number of every student.

The registration $$(M/XX/YYYYY)$$ number consists of 3 parts. First letter $$M$$ denotes the medium ($$E$$ for English, $$S$$ for sinhala etc). The next two numbers ($$XX$$) denotes the age. The next numbers ($$YYYYY$$) denotes the index.

The trainer P observe every student ($$S^P_i$$) by 2 parameters. $$R^P_i$$ is the registration number of the student and $$\theta^P_i$$ is the angle.

The trainer Q observe every student ($$S^Q_j$$) by 2 parameters. $$R^Q_j$$ is the registration number of the student and $$\theta^Q_j$$ is the angle.

The students are adviced to train in groups. A "study group" is a group of 3 students consisting of a leader and two other memebers. The leader always stays at equal distances from the other two memebrs. Students make groups only within the same age and same medium.

The IOI selection commitee believes that students should learn to collaborate with multiple people and has imposed a rule saying "no two study groups can be the same". But it is allowed to have the same 3 students in the group if the group leader is different.

From the observations of the two trainers, what is the maximum number of "study groups" in the tiled grid?

## Input Format

The first line contains two integers $$N$$ denoting the number of students and $$D$$ the length of a side in the square grid.
The next $$N$$ lines contains $$R^P_i$$ and $$\theta^P_i$$ each denoting how trainer P sees the students.
The next $$N$$ lines contains $$R^Q_j$$ and $$\theta^Q_j$$ each denoting how trainer Q sees the students.

The deciman numbers can have up to 7 decimal places.

## Output Format

A single line containing a single integer denoting the maximum number of possible "study groups" in the room.

## Constraints

$$0< N <7500$$

$0 < D <1000 $

$$0 < \theta^P < \frac{\pi}{2}$$

$$\frac{-\pi}{2} < \theta^Q < 0$$

### Sample Input 0

```
4 5
E/14/000002 0.50709
E/14/000003 0.620249
E/14/000001 0.78539
E/14/000004 0.95054
E/14/000001 -1.165904
E/14/000002 -0.50709
E/14/000003 -0.620249
E/14/000004 -0.54042
```

### Sample Output 0

```
2
```
