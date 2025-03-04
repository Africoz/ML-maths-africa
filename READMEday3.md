# Day 3 - Solving Systems of Linear Equations (Detective Work in Data)

## Real Life Detective Example: Stolen Necklace Case

| Time | Suspect A | Suspect B | Suspect C | Suspect D | Evidence (Where Necklace Was Seen) |
|---|---|---|---|---|---|
| Morning | 1 | 0 | 0 | 0 | 1 (Necklace at A's house) |
| Afternoon | 0 | 1 | 0 | 0 | 0 (Necklace not seen) |
| Evening | 0 | 0 | 1 | 0 | 1 (Necklace at C's shop) |
| Night | 0 | 0 | 0 | 1 | 1 (Necklace at D's home) |

This forms a **matrix equation:**

\[
Ax = b
\]
Where:
- A = Who was where at what time (Truth Matrix)
- x = Real involvement (Unknown we want to solve)
- b = Evidence (Actual sightings)

---

## Why This Matters in ML

| Area | Use Case |
|---|---|
| Regression | Fit equations to data |
| Physics-Informed ML | Solve scientific models as systems |
| Portfolio Optimization | Balancing investments with equations |
| Traffic Flow | Predict city traffic using road data |

---

## Quick Example - Sales Price Puzzle

You know combined price of:
- Apple + Mango = $30
- Mango + Banana = $40
- Apple + Banana = $35

Solve for individual prices — this is exactly solving linear equations!

---

# **Matrix Form**
\[
\begin{bmatrix}
1 & 1 & 0 \\
0 & 1 & 1 \\
1 & 0 & 1
\end{bmatrix}
\begin{bmatrix}
x_{apple} \\
x_{mango} \\
x_{banana}
\end{bmatrix}
=
\begin{bmatrix}
30 \\
40 \\
35
\end{bmatrix}
\]
This can be solved directly using matrix techniques.

---

## Core Techniques You’ll See Today

| Technique | Why Important |
|---|---|
| Gaussian Elimination | Hand-calculation method |
| Matrix Inversion | Direct matrix solver |
| `np.linalg.solve` | Cleanest numpy method |
| Checking Consistency | Does the system even have solutions? |

---

## Code in `day3-systems.ipynb`

- Fully tested on Google Colab.
- Both **detective case** and **fruit price puzzle** included.
- Easy to modify for student practice.

---

## ML Takeaway

Solving equations is the **backbone of regression**, curve fitting, and many ML models.  
Master it now — future ML will feel like fun puzzles.

---

Next: Day 4 - Vector Spaces (Creating Your Own Coordinate Language for Data)

---
