# MethodeMonteCarlo
This script estimates the value of π using the Monte Carlo method

  **Problem statement:**  
- Consider a circle of radius 1 inscribed in a square of side 2.  
- By randomly generating points inside the square, we can estimate π.  
- If `N` points are randomly chosen and `n` points fall inside the circle, then:

\[
π ≈ 4 × \frac{n}{N}
\]

## Method
1. Randomly choose coordinates `x` and `y` between -1 and 1 using `random.uniform()`.
2. Compute the distance from the point to the center of the circle.
3. If the distance ≤ 1 (the radius), increment the counter `n`.
4. Repeat for `N` iterations.
5. Estimate π using the formula: `π ≈ 4 * n / N`.

## Usage
```bash
python monte_carlo_pi.py
