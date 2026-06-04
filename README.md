# Geometric Diamond Pattern Printer

This is a Python script designed to practice algorithmic thinking, precise space management, and loop controls. It uses two sequential `for` loops to print a perfectly symmetrical diamond shape using stars (`*`).

## How it works:
1. It initializes a `space` variable to manage the dynamic indentation before the stars.
2. The first `for` loop counts upwards with a step of 2 (`range(1, 20, 2)`) to build the top half of the shape (the upward triangle).
3. In each iteration of the first loop, the number of spaces decreases as the number of stars increases.
4. The second `for` loop counts downwards (`range(17, 0, -2)`) to build the bottom half of the shape (the downward triangle).
5. In each iteration of the second loop, the spaces increase as the stars decrease, creating a seamless diamond pattern.

## What I practiced in this project:
- **Algorithmic Logic:** Designing a precise geometric pattern by combining text alignment and numbers.
- **Advanced Loop Parameters:** Utilizing both positive and negative steps in Python `range()`.
- **Dynamic Variable Tracking:** Modifying the `space` counter step-by-step to control the alignment perfectly.
