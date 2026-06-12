# INI2 - Variables and Some Arithmetic

## Rosalind Problem Context

This Rosalind Python Village problem introduces variables and arithmetic expressions. Given two positive integers `a` and `b`, compute:

```text
a^2 + b^2
```

For the currently published submission in this repository, the dataset values are:

```text
a = 856
b = 957
```

## Completion Date

**Completed:** 2026-05-31

## Problem Summary

Store the two integers, square each one, add the results, and print the final value.

## Input and Output Expectations

| Item | Expectation |
| --- | --- |
| Input | Two positive integers `a` and `b`. |
| Output | A single integer equal to `a^2 + b^2`. |
| Sample Input | `856 957` for the published submission context. |
| Sample Output | `1648585` |

## Published Answers

| Solution | Document | Live Page | Approach Summary |
| --- | --- | --- | --- |
| Answer 1 | [answer-1.md](answer-1.md) | [index.html](./) | Uses Python variables and the exponent operator `**` to square both values before summing them. |

## Solution Comparison

| Solution | Core Idea | Time Complexity | Space Complexity | Notes |
| --- | --- | --- | --- | --- |
| Answer 1 | Compute `(a ** 2) + (b ** 2)` directly. | O(1) | O(1) | Only a fixed number of arithmetic operations are required. |

## Engineering Notes

This solution is the straightforward constant-time implementation for the given arithmetic task. It is clear, idiomatic Python and matches the intended beginner-level learning objective.

## Notes Source

No NotebookLM or handwritten notes were committed for this problem in the repository at the time of this automation run.
