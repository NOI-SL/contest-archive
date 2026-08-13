---
title: "Overclocking the GPUs"
year: 2021
category: finals
round: "Final Round — Day 1"
sortkey: "3-finals-1-04"
index: 4
max_score: 0
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka 2021 - Day 1"
contest_slug: "noi-2021-day-1"
contest_url: "https://www.hackerrank.com/contests/noi-2021-day-1"
problem_slug: "overclocking-the-gpus"
problem_url: "https://www.hackerrank.com/contests/noi-2021-day-1/challenges/overclocking-the-gpus"
---

You are in charge of setting up a GPU cluster to train some ML models. Before beginning the hardware development, you want to overclock the GPUs to get maximal output.  
  
To test out the maximal output, you’re given ***N*** identical GPUs.  
You have access to an **overclock** function that goes from ***0*** to ***M***  

You can run an experiment by using a GPU with **overclock(x)** to see if the GPU works at **overclock(x)**, or it gets destroyed rendering it unusable in future experiments. If the GPU survives an experiment you can use it on subsequent experiments.  

Using these ***N*** GPUs you want to find the maximum value you can safely use in the overclocking function without destroying the GPU.  
  
You also want to do this by executing the least number of experiments.  

Given,
- ***N*** - number of GPUs
- ***M*** - maximum value for the overclock function

Find the minimum number of experiments you need to perform to find the maximum safe value for the overclock function.

## Input Format

Two space seperated integers, ***N*** and ***M*** respectively

## Output Format

A single integer indicating the answer

## Constraints

- **1 $$\leq$$ N $$\leq$$ 10<sup>5</sup>**  
- **1 $$\leq$$ M $$\leq$$ 10<sup>9</sup>**  
  
#### **Subtasks**  

1. **(30 points)**  
	- **1 $$\leq$$ N $$\leq$$ 1000**  
	- **1 $$\leq$$ M $$\leq$$ 2000**  
2. **(30 points)**  
	- **1 $$\leq$$ N $$\leq$$ 10<sup>3</sup>**  
	- **1 $$\leq$$ M $$\leq$$ 10<sup>4</sup>**  
3. **(40 points)**  
	- No additional constraints.  
   
#### **Limits**  

- **Time Limit**: 1s
- **Memory Limit**: 256MB

### Sample Input 0

```
1 2
```

### Sample Output 0

```
2
```

### Sample Input 1

```
3 4
```

### Sample Output 1

```
3
```
