# Day 2 - Matrices (The Town's Infrastructure Grid)

## Metaphor: African Town Transport Grid

Imagine our town's **infrastructure map** is stored as a **matrix**.

- Rows = Starting points (Town Hall, School, Market, Hospital)
- Columns = Destinations (same places)
- Matrix entry = Time taken to travel (in minutes)

This **table of travel times** is actually a **matrix**.

---

## Why Matrices Matter in Machine Learning

| Area | How Matrices are Used |
|---|---|
| Images | Images are matrices of pixels (RGB or Grayscale) |
| Neural Networks | Weight matrices control every layer |
| PCA (Dimensionality Reduction) | Data gets factored into matrix forms |
| Data Storage | Features of data can be stored as matrices |
| Transformations | Rotation, Scaling (Augmentations) = Matrix Operations |

---

## Real Life Example 1 - Transport Matrix (Pure Math)

We build a matrix representing travel times:

| From / To | Town Hall | School | Market | Hospital |
|---|---|---|---|---|
| Town Hall | 0 | 15 | 30 | 45 |
| School | 15 | 0 | 20 | 35 |
| Market | 30 | 20 | 0 | 25 |
| Hospital | 45 | 35 | 25 | 0 |

Operations like adding new towns, adjusting costs due to traffic, etc., are basic matrix operations.

---

## Real Life Example 2 - Image Processing (Matrix = Image)

A grayscale image is a matrix where each cell is pixel brightness (0-255).  
We visualize this matrix directly to see the image.

---

## Core Matrix Operations Used Today

| Operation | Explanation |
|---|---|
| Matrix Access | Find travel time from school to market |
| Transpose | Flip rows and columns (reverse direction) |
| Addition | Adding extra time due to road repairs |
| Multiplication | Apply traffic intensity multipliers |

---

## Code in `day2-matrices.ipynb`

- Fully tested on Google Colab.
- Contains both **transport matrix math** and **image matrix demo**.
- Ready for copy-paste into real ML projects.

---

## ML Lesson Takeaway

Matrices are **foundational** to:
- Images
- Neural Networks
- Dimensionality Reduction (PCA/SVD)
- Data Storage in Tabular Datasets

Mastering matrix thinking helps you think like a **data scientist**.

---

## Next: Day 3 - Solving Systems of Linear Equations (Detective Work on Data)

---

## Quick Note
- This file is meant for both students and teachers.
- Students should practice modifying these matrices with their own town names!
