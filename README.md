# TOPSIS Ranking Program

## Author Details

* **Author:**Nandita
* **Roll No.:** 102303513
* **Course:** Predictive Analytics using Statistics

## Method Used

**TOPSIS (Technique for Order Preference by Similarity to Ideal Solution)**

## Overview

This project implements the **TOPSIS methodology** to evaluate and rank different funds using an input Excel dataset. The program is designed as a **command-line application** and includes validation checks for weights, impacts, and file formats.

TOPSIS is a widely used **Multi-Criteria Decision Making (MCDM)** technique that ranks alternatives based on their distance from the ideal best and ideal worst solutions. Each alternative is assigned a performance score, which is then used to generate rankings.

## Methodology

The program follows these steps:

1. Construct the decision matrix from the input Excel file
2. Normalize the decision matrix using vector normalization
3. Apply user-defined weights to the normalized matrix
4. Determine the ideal best (V⁺) and ideal worst (V⁻) solutions based on impacts
5. Calculate Euclidean distance from ideal best and ideal worst solutions
6. Compute TOPSIS score for each fund
7. Assign rank based on TOPSIS score

## Dataset Information

* Dataset contains **8 funds** and **5 parameters** for ranking
* Input file format: **Excel (.xlsx)**
* First column contains **fund names**
* Remaining columns contain **numeric criteria values**
* Invalid or non-numeric inputs are handled through validation checks

## File Structure

* **Assignment_1_UCS654.ipynb** → Jupyter / Google Colab notebook containing full implementation
* **TOPSIS_code.py** → Python script for TOPSIS calculation
* **data.xlsx** → Sample input dataset
* **result.xlsx** → Output file with TOPSIS scores and rankings
* **README.md** → Project documentation

## Output

The output file contains:

* Original dataset
* TOPSIS score for each fund
* Final rank of each fund

## Validation Checks

The program validates:

* Correct number of weights
* Correct number of impacts
* Numeric values in criteria columns
* Valid Excel input format

## Conclusion

This implementation provides an efficient way to rank alternatives using TOPSIS and can be extended for other multi-criteria decision-making problems.
