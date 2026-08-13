---
title: "Frequency Fusion"
year: 2026
category: finals
round: "Final Round — Day 1"
sortkey: "3-finals-1-01"
index: 1
max_score: 100
difficulty: "Medium"
contest_name: "NOI 2026 Day 1"
contest_slug: "noi-2026-day-1"
contest_url: "https://www.hackerrank.com/contests/noi-2026-day-1"
problem_slug: "frequency-fusion"
problem_url: "https://www.hackerrank.com/contests/noi-2026-day-1/challenges/frequency-fusion"
---

Dr. Aria runs a prestigious sound research lab. She has collected **n** frequency generators, each tuned to a distinct frequency (in Hz). The frequencies are given as an array $$f_1, f_2, \ldots, f_n$$ of **distinct** positive integers.

She owns a device called the **Harmonic Resonator**. She can use it to perform the following operation:

- Choose two frequency generators $$f_i$$ and $$f_j$$ ($$i \ne j$$) currently in her lab. The resonator extracts their **Greatest Common Frequency** $$\gcd(f_i, f_j)$$. If that frequency is **not already present** in her collection, a new generator tuned to that frequency is built and added to the lab.

Note that the lab's collection changes after each operation, and future operations can use the newly added generators.

Dr. Aria wants to perform as many resonance operations as possible. Find the **maximum number of times** she can use the Harmonic Resonator.

## Input Format

The first line contains a single integer $$n$$ $$(2 \le n \le 10^6)$$.

The second line contains $$n$$ integers $$f_1, f_2, \ldots, f_n$$ $$(1 \le f_i \le 10^6)$$. All $$f_i$$ are **distinct**.

## Output Format

Print a single integer — the maximum number of times the Harmonic Resonator can be used.

## Constraints

**Time limit:** 2 seconds  
**Memory limit:** 256 megabytes

### Sample Input 0

```
5
4 20 1 25 30
```

### Sample Output 0

```
3
```
