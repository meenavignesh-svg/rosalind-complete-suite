# INI3 - Strings and Lists

**Completed:** 2026-06-01

## Rosalind Problem Context

Given a string `s` of length at most 200 letters and four integers `a`, `b`, `c`, and `d`, return the slice from indices `a` through `b` and the slice from indices `c` through `d`, inclusively, with a space between the two returned substrings.

Because Python slices exclude the stop index, the correct inclusive implementation uses `s[a:b+1]` and `s[c:d+1]`.

## Problem Summary

Extract two inclusive substrings from the given string and print them on one line separated by a space.

## Input and Output Expectations

| Item | Expectation |
| --- | --- |
| Input | One string `s` plus four integers `a`, `b`, `c`, and `d`. |
| Output | Two inclusive slices of `s`, separated by one space. |
| Sample Input | `a = 43`, `b = 47`, `c = 167`, `d = 174` for the published submission context. |
| Sample Output | `Sorex korschun` |

## Published Answers

| Solution | Document | Live Page | Approach Summary |
| --- | --- | --- | --- |
| Answer 1 | [answer-1.md](answer-1.md) | [index.html](./) | Uses inclusive Python slicing with `b + 1` and `d + 1`, then formats the two substrings into one output line. |

## Solution Comparison

| Solution | Core Idea | Time Complexity | Space Complexity | Notes |
| --- | --- | --- | --- | --- |
| Answer 1 | Slice `s[a:b+1]` and `s[c:d+1]`, then print both pieces together. | O(k) | O(k) | `k` is the total number of returned characters copied into the substrings. |

## Engineering Notes

This task is mainly about Python indexing semantics. The only easy mistake is forgetting that slice stop positions are exclusive, which would drop the characters at `b` and `d`.

## Notes Source

No NotebookLM or handwritten notes were committed for this problem in the repository at the time of this automation run.