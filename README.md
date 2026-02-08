# hopfion-validation
Computational validation of Hopf fibration topology via dense fiber extraction and linking analysis.
Reproducible pipeline for sampling, visualizing, and quantifying topological linking (Lk ≈ ±1) across large ensembles of Hopf fibers derived from electromagnetic hopfion field structures. Includes numerical Gauss linking computation, closure verification, and interactive 3D visualizations.

## Notebook Structure

This notebook contains two self-contained experiments:

### 1. Linked Fiber Pair (Validation)
Demonstrates extraction of two Hopf fibers corresponding to distinct points on S².
- Closed centerlines
- Gauss linking number Lk ≈ −1
- Numerical error < 10⁻⁵

This establishes correctness of the extraction and quantification pipeline.

### 2. Dense Fiber Ensemble (Extension)
Extracts and visualizes 373 fibers from the same Hopf map.
- Preserves global fibration structure
- Demonstrates scalability of the method
- Confirms consistency of local topology across fibers

## What this repository is (and is not)

This work does not propose a new Hopf map, hopfion solution, or analytical construction.
Instead, it provides a reproducible numerical pipeline for extracting, visualizing,
and validating the topological linking structure implied by existing hopfion fields.
