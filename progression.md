# Progressions

Progressions are sequences of numbers following a particular pattern. The three main types of progressions are Arithmetic Progression (AP), Geometric Progression (GP), and Harmonic Progression (HP).

## 1. Arithmetic Progression (AP)

### Definition
An arithmetic progression is a sequence of numbers in which the difference between consecutive terms is constant. This difference is called the "common difference" (d).

### General Form
\[ a, a + d, a + 2d, a + 3d, \ldots \]

### Formulas
- **n-th Term (Tn)**: 
  \[ T_n = a + (n - 1)d \]
- **Sum of First n Terms (Sn)**: 
  \[ S_n = \frac{n}{2} \left[2a + (n - 1)d\right] \]
  or
  \[ S_n = \frac{n}{2} (a + l) \]
  where \( l \) is the last term of the AP.

### Examples
- **Example 1:** Find the 5th term of the AP: 2, 5, 8, 11, ...
  \[ T_5 = 2 + (5 - 1) \cdot 3 = 2 + 12 = 14 \]

- **Example 2:** Find the sum of the first 10 terms of the AP: 1, 3, 5, 7, ...
  \[ S_{10} = \frac{10}{2} [2 \cdot 1 + (10 - 1) \cdot 2] = 5 [2 + 18] = 100 \]

## 2. Geometric Progression (GP)

### Definition
A geometric progression is a sequence of numbers in which each term after the first is found by multiplying the previous term by a fixed, non-zero number called the "common ratio" (r).

### General Form
\[ a, ar, ar^2, ar^3, \ldots \]

### Formulas
- **n-th Term (Tn)**: 
  \[ T_n = ar^{(n - 1)} \]
- **Sum of First n Terms (Sn)**:
  \[ S_n = \frac{a(1 - r^n)}{1 - r} \]
  if \( r \neq 1 \)
- **Sum to Infinity (S∞)**: 
  \[ S_{\infty} = \frac{a}{1 - r} \]
  if \( |r| < 1 \]

### Examples
- **Example 1:** Find the 4th term of the GP: 3, 6, 12, 24, ...
  \[ T_4 = 3 \cdot 2^{(4 - 1)} = 3 \cdot 8 = 24 \]

- **Example 2:** Find the sum of the first 5 terms of the GP: 1, 2, 4, 8, ...
  \[ S_5 = \frac{1(1 - 2^5)}{1 - 2} = \frac{1 - 32}{-1} = 31 \]

## 3. Harmonic Progression (HP)

### Definition
A harmonic progression is a sequence of numbers derived from the reciprocals of an arithmetic progression.

### General Form
If the sequence \( a, a + d, a + 2d, a + 3d, \ldots \) is an AP, then the sequence \( \frac{1}{a}, \frac{1}{a + d}, \frac{1}{a + 2d}, \ldots \) is an HP.

### Formulas
- **n-th Term (Tn)** of HP: The n-th term of an HP is the reciprocal of the n-th term of the corresponding AP.
  \[ T_n = \frac{1}{a + (n - 1)d} \]

### Examples
- **Example 1:** Find the 3rd term of the HP corresponding to the AP: 2, 4, 6, 8, ...
  \[ \text{AP: } 2, 4, 6, 8, \ldots \]
  \[ \text{HP: } \frac{1}{2}, \frac{1}{4}, \frac{1}{6}, \frac{1}{8}, \ldots \]
  \[ T_3 = \frac{1}{6} \]

  ## Additional Resources

For more examples and practice questions, check out [Concpt](https://www.placementpreparation.io/quantitative-aptitude/arithmetic-progression/questions-and-answers/,
[Practice](https://www.geeksforgeeks.org/progression-aptitude-questions/)
