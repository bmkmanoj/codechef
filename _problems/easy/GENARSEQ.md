---
languages_supported:
    - NA
title: GENARSEQ
category: NA
old_version: true
problem_code: GENARSEQ
tags:
    - NA
layout: problem
---
###  All submissions for this problem are available. 

For given two positive integers **a** and **b** let's construct the sequence **x\[1\], x\[2\], ...** by the following rules. For **k=1** we put **x\[1\]=1**. Now let **k >= 2**. Then **x\[k\]** is the least positive integer such that the following two conditions hold

- **x\[k\] > x\[k - 1\]**;
- for all **i, j < k** we have **x\[k\]** is not equal to **a \* x\[i\] - b \* x\[j\]**.


 You need to find the first **n** terms of this sequence. 

**Remark.** Let **a=2** and **b=1**. Then we see that sequence **x\[1\], x\[2\], ...** does not contain any arithmetic progression of length three as its subsequence. This justifies the problem title.

### Input

The first line contains a single integer **T**, the number of test cases. **T** test cases follow. The only line of each test case contains three integers **a, b** and **n**.

### Output

For each test case, output a single line containing the numbers **x\[1\], x\[2\], ..., x\[n\]** generated by the rules given in the problem statement and numbers **a, b**. Separate any two consecutive numbers in a line by a single space.

### Constraints

 **1 <= T <= 50 
 1 <= a, b <= 50 
 1 <= n <= 1000**

### Example

```
<b>Input:</b>
3
2 1 10
1 1 5
4 2 4

<b>Output:</b>
1 2 4 5 10 11 13 14 28 29
1 2 3 4 5
1 3 4 5

```
- - - - - -