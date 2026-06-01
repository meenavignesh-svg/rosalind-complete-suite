# Rosalind Complete Suite

A growing portfolio of Rosalind solutions, beginning with the **Python Village** track. Each completed problem includes the question context first, completion date, one or more verified answer documents, explanation, live GitHub Pages work, and engineering complexity notes.

## Python Village Progress

| Problem | Title | Completed | Status | Answer Documents | Live Page |
| --- | --- | --- | --- | --- | --- |
| INI1 | Installing Python | 2026-05-31 | Complete | [Answer 1](docs/python-village/INI1/answer-1.md) | [Live page](docs/python-village/INI1/) |
| INI2 | Variables and Some Arithmetic | 2026-05-31 | Complete | [Answer 1](docs/python-village/INI2/answer-1.md) | [Live page](docs/python-village/INI2/) |
| INI3 | Strings and Lists | 2026-06-01 | Complete | [Answer 1](docs/python-village/INI3/answer-1.md) | [Live page](docs/python-village/INI3/) |

---

## INI1 - Installing Python

**Completed:** 2026-05-31

### Question

Rosalind's first Python Village task introduces the Python interpreter. The task is to run Python and execute the built-in command:

```python
import this
```

This prints **The Zen of Python**, a short set of guiding principles for writing readable, explicit, and maintainable Python code.

### Answer Documents

| Answer | Document | Summary |
| --- | --- | --- |
| Answer 1 | [docs/python-village/INI1/answer-1.md](docs/python-village/INI1/answer-1.md) | Runs `import this` and records the Zen of Python output. |

### Engineering Performance

| Solution | Time Complexity | Space Complexity | Notes |
| --- | --- | --- | --- |
| Answer 1: `import this` | O(1) | O(1) | Prints a fixed-size built-in text from Python's standard library. |

## INI2 - Variables and Some Arithmetic

**Completed:** 2026-05-31

### Question

Given two positive integers `a` and `b`, compute the sum of their squares:

```text
a^2 + b^2
```

For this submitted answer, `a = 856` and `b = 957`.

### Answer Documents

| Answer | Document | Summary |
| --- | --- | --- |
| Answer 1 | [docs/python-village/INI2/answer-1.md](docs/python-village/INI2/answer-1.md) | Uses Python variables and exponentiation to print `1648585`. |

### Engineering Performance

| Solution | Time Complexity | Space Complexity | Notes |
| --- | --- | --- | --- |
| Answer 1: `a ** 2 + b ** 2` | O(1) | O(1) | Performs a fixed number of arithmetic operations. |

## INI3 - Strings and Lists

**Completed:** 2026-06-01

### Question

Given a string `s` of length at most 200 letters and four integers `a`, `b`, `c`, and `d`, return the inclusive slices `s[a:b]` and `s[c:d]` with a space between them. In Python, that means using `s[a:b+1]` and `s[c:d+1]`.

For this submitted answer, `a = 43`, `b = 47`, `c = 167`, and `d = 174`.

### Answer Documents

| Answer | Document | Summary |
| --- | --- | --- |
| Answer 1 | [docs/python-village/INI3/answer-1.md](docs/python-village/INI3/answer-1.md) | Uses inclusive slicing to print `Sorex korschun`. |

### Engineering Performance

| Solution | Time Complexity | Space Complexity | Notes |
| --- | --- | --- | --- |
| Answer 1: inclusive slicing | O(k) | O(k) | `k` is the total number of returned slice characters. |

## Repository Goal

For each completed Rosalind Python Village problem, this repository will maintain:

| Asset | Purpose |
| --- | --- |
| Root `README.md` | Portfolio table of contents and progress tracker. |
| Per-problem `README.md` | Question context, completion date, answer links, solution comparison, and complexity summary. |
| `answer-1.md`, `answer-2.md`, etc. | Standalone document for each individual answer. |
| `index.html` | Live GitHub Pages interface for the problem. |
| Solution script | Verified source code or submitted answer. |

Multiple answers for the same problem will be preserved as separate solution documents and compared clearly.
