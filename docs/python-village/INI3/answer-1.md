# INI3 - Strings and Lists: Answer 1

**Completed:** 2026-06-01

## Question

Given a string `s` of length at most 200 letters and four integers `a`, `b`, `c`, and `d`, return the slice of the string from indices `a` through `b` and `c` through `d`, inclusively, with a space between the two slices.

In Python, the stop index of a slice is exclusive, so inclusive ranges must use `b + 1` and `d + 1`.

## Dataset

```python
s = "4Dt0IdYSzQOk1yltD8FfbCfGHaFZEOIecHXwIrTYriISorexHiyPRcdrFLWwN7Bi0fVK0aqgylLGO52ZU67ivxzIvuvcUVxe2ATqKeHskwfx1MTLtfQWIZZj3ugC8CiQRejz6ne05iwcfj9C3p0gK6U4bX0kwFWJySngI1tkorschunVy8fXf43Vs."
a, b, c, d = 43, 47, 167, 174
```

## Answer 1

```python
s = "4Dt0IdYSzQOk1yltD8FfbCfGHaFZEOIecHXwIrTYriISorexHiyPRcdrFLWwN7Bi0fVK0aqgylLGO52ZU67ivxzIvuvcUVxe2ATqKeHskwfx1MTLtfQWIZZj3ugC8CiQRejz6ne05iwcfj9C3p0gK6U4bX0kwFWJySngI1tkorschunVy8fXf43Vs."
a, b, c, d = 43, 47, 167, 174
print(f"{s[a:b+1]} {s[c:d+1]}")
```

## Output

```text
Sorex korschun
```

## Explanation

The first slice is `s[a:b+1]`, which means `s[43:48]`. This includes index `47`, giving:

```text
Sorex
```

The second slice is `s[c:d+1]`, which means `s[167:175]`. This includes index `174`, giving:

```text
korschun
```

The formatted string prints the two extracted words with a single space between them.

## Complexity Analysis

| Metric | Complexity | Reason |
| --- | --- | --- |
| Time Complexity | O(k) | Python creates two sliced strings whose combined length is `k = (b - a + 1) + (d - c + 1)`. |
| Space Complexity | O(k) | The two extracted substrings and final output string require space proportional to the returned characters. |

## Edge Cases

The important edge case is the inclusive endpoint. Python slices normally exclude the stop index, so using `s[a:b]` and `s[c:d]` would miss the characters at positions `b` and `d`.
