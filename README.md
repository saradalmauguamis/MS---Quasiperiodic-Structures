# MS---Quasiperiodic-Structures

# 1D Patterns

## Overview

This Jupyter Notebook explores the creation and analysis of various 1D patterns derived from 2D quasiperiodic structures. The patterns analyzed include Fibonacci, quadratic (Q2), and cubic (Q7) sequences, as well as periodic and random (Poisson) distributions. The notebook also investigates the number variance of these patterns and their corresponding diffraction patterns.

## Contents

1. **Introduction**
   - Overview of the patterns being studied.

2. **Quasiperiodic Patterns**
   - Definition and generation of quasiperiodic patterns.
   - Implementation of the `Point2D` class to handle 2D points and their projections.

3. **Projection to 1D**
   - Conversion of 2D quasiperiodic patterns to 1D by projecting onto specified direction vectors.
   - Visualization of the projected points.

4. **Periodic Patterns**
   - Generation of periodic 1D points based on the Fibonacci sequence.

5. **Random (Poisson) Patterns**
   - Generation of random 1D points using exponential inter-point distances.

6. **Comparison of Patterns**
   - Visualization of the different 1D patterns on the same plot for comparison.

7. **Number Variance**
   - Calculation and visualization of number variance for each pattern.
   - Analysis of density fluctuations across different radii.

8. **Diffraction Patterns**
   - Calculation and visualization of the diffraction patterns for each 1D pattern.

## Requirements

To run this notebook, you will need the following Python packages:

- `numpy`
- `matplotlib`
- `pandas`

You can install the required packages using pip:

```bash
pip install numpy matplotlib pandas
```

## Usage

1. Clone this repository or download the notebook file.
2. Open the notebook in Jupyter Notebook or any compatible environment.
3. Run the cells sequentially to generate and visualize the patterns.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

- Inspired by the study of quasiperiodic patterns and their applications in various fields.
