# Rosalind Complete Suite

A growing portfolio of Rosalind solutions, beginning with the **Python Village** track. Each completed problem includes the question context first, followed by one or more verified answer documents, explanation, live GitHub Pages work, and engineering complexity notes.

## Python Village Progress

| Problem | Title | Status | Answer Documents | Live Page |
| --- | --- | --- | --- | --- |
| INI1 | Installing Python | Complete | [Answer 1](docs/python-village/INI1/answer-1.md) | [Live page](docs/python-village/INI1/) |
| INI2 | Variables and Some Arithmetic | Complete | [Answer 1](docs/python-village/INI2/answer-1.md) | [Live page](docs/python-village/INI2/) |

---

## INI1 - Installing Python

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

### Question

Given two positive integers `a` and `b`, compute the sum of their squares:

```text
a^2 + b^2
```

For this answer, `a = 3` and `b = 4`.

### Answer Documents

| Answer | Document | Summary |
| --- | --- | --- |
| Answer 1 | [docs/python-village/INI2/answer-1.md](docs/python-village/INI2/answer-1.md) | Uses Python variables and exponentiation to print `25`. |

### Engineering Performance

| Solution | Time Complexity | Space Complexity | Notes |
| --- | --- | --- | --- |
| Answer 1: `a ** 2 + b ** 2` | O(1) | O(1) | Performs a fixed number of arithmetic operations. |

## Repository Goal

For each completed Rosalind Python Village problem, this repository will maintain:

| Asset | Purpose |
| --- | --- |
| Root `README.md` | Portfolio table of contents and progress tracker. |
| Per-problem `README.md` | Question context, answer links, solution comparison, and complexity summary. |
| `answer-1.md`, `answer-2.md`, etc. | Standalone document for each individual answer. |
| `index.html` | Live GitHub Pages interface for the problem. |
| Solution script | Verified source code or submitted answer. |

Multiple answers for the same problem will be preserved as separate solution documents and compared clearly.
