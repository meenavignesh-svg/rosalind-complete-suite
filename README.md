# Rosalind Complete Suite

A polished GitHub Pages portfolio for Rosalind solutions, starting with the **Python Village** track. Each completed problem is documented with the question context first, then a problem brief, one or more standalone answer documents, and a live HTML page.

## Python Village Progress

| Metric | Value |
| --- | --- |
| Completed problems | 3 of 6 |
| Standalone answer documents | 3 |
| Problem brief READMEs | 3 |
| Latest published codes | `INI1`, `INI2`, `INI3` |

| Problem | Title | Completed | Status | Problem README | Answer Documents | Live Page |
| --- | --- | --- | --- | --- | --- | --- |
| INI1 | Installing Python | 2026-05-31 | Complete | [README](docs/python-village/INI1/README.md) | [Answer 1](docs/python-village/INI1/answer-1.md) | [Live page](docs/python-village/INI1/) |
| INI2 | Variables and Some Arithmetic | 2026-05-31 | Complete | [README](docs/python-village/INI2/README.md) | [Answer 1](docs/python-village/INI2/answer-1.md) | [Live page](docs/python-village/INI2/) |
| INI3 | Strings and Lists | 2026-06-01 | Complete | [README](docs/python-village/INI3/README.md) | [Answer 1](docs/python-village/INI3/answer-1.md) | [Live page](docs/python-village/INI3/) |

---

## INI1 - Installing Python

**Completed:** 2026-05-31

### Rosalind Problem Context

Rosalind's first Python Village task asks you to run Python and execute:

```python
import this
```

This prints **The Zen of Python**, a fixed text that introduces Python's core design values.

### Input and Output Expectations

| Item | Expectation |
| --- | --- |
| Input | No external dataset is required. |
| Output | The Zen of Python text block. |
| Sample Input | Not applicable. |
| Sample Output | The standard `import this` output beginning with `The Zen of Python, by Tim Peters`. |

### Published Assets

| Asset | Link | Purpose |
| --- | --- | --- |
| Problem README | [docs/python-village/INI1/README.md](docs/python-village/INI1/README.md) | Problem context, answer links, and performance summary. |
| Answer 1 | [docs/python-village/INI1/answer-1.md](docs/python-village/INI1/answer-1.md) | Standalone answer document with explanation and edge cases. |
| Live page | [docs/python-village/INI1/](docs/python-village/INI1/) | GitHub Pages presentation of the problem and answer. |

### Solution Comparison

| Solution | Approach | Time Complexity | Space Complexity | Notes |
| --- | --- | --- | --- | --- |
| Answer 1 | Import Python's built-in `this` module and record its fixed output. | O(1) | O(1) | No variable-sized input is processed. |

## INI2 - Variables and Some Arithmetic

**Completed:** 2026-05-31

### Rosalind Problem Context

Given two positive integers `a` and `b`, compute the sum of their squares:

```text
a^2 + b^2
```

For the currently published submission, the dataset values are `a = 856` and `b = 957`.

### Input and Output Expectations

| Item | Expectation |
| --- | --- |
| Input | Two positive integers `a` and `b`. |
| Output | A single integer equal to `a^2 + b^2`. |
| Sample Input | `856 957` |
| Sample Output | `1648585` |

### Published Assets

| Asset | Link | Purpose |
| --- | --- | --- |
| Problem README | [docs/python-village/INI2/README.md](docs/python-village/INI2/README.md) | Problem context, answer links, and performance summary. |
| Answer 1 | [docs/python-village/INI2/answer-1.md](docs/python-village/INI2/answer-1.md) | Standalone answer document with code and explanation. |
| Live page | [docs/python-village/INI2/](docs/python-village/INI2/) | GitHub Pages presentation of the problem and answer. |

### Solution Comparison

| Solution | Approach | Time Complexity | Space Complexity | Notes |
| --- | --- | --- | --- | --- |
| Answer 1 | Compute `(a ** 2) + (b ** 2)` directly in Python. | O(1) | O(1) | Uses a fixed number of arithmetic operations. |

## INI3 - Strings and Lists

**Completed:** 2026-06-01

### Rosalind Problem Context

Given a string `s` of length at most 200 letters and four integers `a`, `b`, `c`, and `d`, return the inclusive slices `s[a:b]` and `s[c:d]` with a space between them. In Python, the correct inclusive implementation is `s[a:b+1]` and `s[c:d+1]`.

For the currently published submission, `a = 43`, `b = 47`, `c = 167`, and `d = 174`.

### Input and Output Expectations

| Item | Expectation |
| --- | --- |
| Input | One string `s` and four integers `a`, `b`, `c`, and `d`. |
| Output | Two inclusive string slices separated by one space. |
| Sample Input | `a = 43`, `b = 47`, `c = 167`, `d = 174` |
| Sample Output | `Sorex korschun` |

### Published Assets

| Asset | Link | Purpose |
| --- | --- | --- |
| Problem README | [docs/python-village/INI3/README.md](docs/python-village/INI3/README.md) | Problem context, answer links, and performance summary. |
| Answer 1 | [docs/python-village/INI3/answer-1.md](docs/python-village/INI3/answer-1.md) | Standalone answer document with code, explanation, and edge cases. |
| Live page | [docs/python-village/INI3/](docs/python-village/INI3/) | GitHub Pages presentation of the problem and answer. |

### Solution Comparison

| Solution | Approach | Time Complexity | Space Complexity | Notes |
| --- | --- | --- | --- | --- |
| Answer 1 | Use `s[a:b+1]` and `s[c:d+1]` to preserve inclusive endpoints. | O(k) | O(k) | `k` is the total number of returned characters. |

## Repository Publishing Standard

For each completed Rosalind Python Village problem, this repository maintains:

| Asset | Purpose |
| --- | --- |
| Root `README.md` | Portfolio table of contents and progress tracker. |
| Per-problem `README.md` | Question context, answer links, solution comparison, and complexity summary. |
| `answer-1.md`, `answer-2.md`, etc. | Standalone document for each individual answer. |
| `index.html` | Live GitHub Pages interface for the problem. |
| Verified answer content | The exact submitted code or output being documented. |

Multiple answers for the same problem will be preserved as separate solution documents and compared clearly.