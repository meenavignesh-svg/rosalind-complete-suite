# INI3 - Strings and Lists

**Completed:** 2026-06-01

## Question

Given a string `s` of length at most 200 letters and four integers `a`, `b`, `c`, and `d`, return the slice of this string from indices `a` through `b` and `c` through `d`, inclusively, with a space between the two slices.

## Answer Documents

| Answer | Document | Summary |
| --- | --- | --- |
| Answer 1 | [answer-1.md](answer-1.md) | Uses inclusive Python slicing with `b + 1` and `d + 1` to print `Sorex korschun`. |

## Engineering Performance

| Solution | Time Complexity | Space Complexity | Notes |
| --- | --- | --- | --- |
| Answer 1: inclusive slicing | O(k) | O(k) | `k` is the total number of returned slice characters. |

## Live Page

[Open the live INI3 portfolio page](index.html)
