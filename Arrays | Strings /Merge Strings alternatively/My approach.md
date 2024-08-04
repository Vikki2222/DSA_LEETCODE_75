# Problem definition 
**Difficulty:** `Easy`

You are given two strings word1 and word2. Merge the strings by adding letters in alternating order, starting with word1. If a string is longer than the other, append the additional letters onto the end of the merged string.

Return the merged string.

 

**Example:**
```
Input: word1 = "abc", word2 = "pqr"
Output: "apbqcr"
Explanation: The merged string will be merged as so:
word1:  a   b   c
word2:    p   q   r
merged: a p b q c r
```

**Initial Approach**

The initial approach that comes to mind when looking at the problem is to concatenate the two strings alternately and append the result to a 'StringBuilder' iteratively until the length of the largest String.

**Advice**

It's an easy problem so keep it that way don't complicate things

