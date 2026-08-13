---
title: "Exam-stress"
year: 2025
category: finals
round: "Final Round — Day 1"
sortkey: "3-finals-1-02"
index: 2
max_score: 100
difficulty: "Hard"
contest_name: "National Olympiad in Informatics 2025 day 1"
contest_slug: "noi-2025-day-1"
contest_url: "https://www.hackerrank.com/contests/noi-2025-day-1"
problem_slug: "exam-stress-2"
problem_url: "https://www.hackerrank.com/contests/noi-2025-day-1/challenges/exam-stress-2"
---

Many students dream of becoming champions of the National Academic League. For some, this dream is the very reason they enrolled at the prestigious Academia Maxima. And today, that dream is about to be tested in the toughest challenge yet — the Gauntlet of Exams.

There are $$N$$ students preparing for this final test. Each student has:

$$a_i$$ — their answering speed, indicating how many marks they can eliminate from an exam per minute.

$$b_i$$ — their mental stamina, representing how many stress points they can endure in total.

There are $$M$$ exams waiting, each with:

$$c_j$$ — the stress per minute the exam inflicts on a student.

$$d_j$$ — the total marks of the exam.

Each student enters the exam hall and faces the exams one by one in the given order. If the student finishes one, they immediately begin the next, without any break or stamina recovery.

Exam Mechanics:
Each exam is a timed test. A student and the exam “attack” each other simultaneously:

The student reduces the exam’s remaining marks by $$a_i$$ per minute.

The exam drains the student’s stamina by $$c_j$$ per minute.

This continues until either:

The exam's remaining marks drop to zero or less → the exam is completed.

The student’s stamina drops to zero or less → the student drops out.

If both reach zero in the same minute, the exam is counted as completed, but the student does not proceed further.

Your job is to help Academia Maxima’s automated grading system by computing, for each student, how many exams they will complete before their stamina is fully consumed.

## Input Format

- The first line contains two integers $$N$$ and $$M$$ — the number of students and exams respectively. 
- The next $$N$$ lines contain two integers $$a_i$$ and $$b_i$$ — the student’s answering speed and initial stamina. 
- The next $$M$$ lines each contain two integers $$c_j$$ and $$d_j$$ — the exam’s stress rate and number of marks.

## Output Format

Print $$N$$ lines. On the $$i^{th}$$ line, output a single integer - the number of exams the $$i^{th}$$ student will complete before running out of stamina.

## Constraints

- $$1 ≤ N, M ≤ 100,000$$  
- $$1 ≤ aᵢ, bᵢ ≤ 10⁹$$  
- $$1 ≤ cⱼ, dⱼ ≤ 100,000$$

Subtask: $$1 ≤ N, M ≤ 1000$$ (25 points)

### Sample Input 0

```
5 3
1 2
2 2
10 10
100 10
1 100
2 2
7 2
3 20
```

### Sample Output 0

```
0
1
2
3
3
```
