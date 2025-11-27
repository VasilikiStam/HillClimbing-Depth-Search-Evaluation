# Hill-Climbing and Depth Search – Experimental Evaluation

## Overview
This repository contains the results of **AI Assignment 2**, where  
**Hill-Climbing** and **Depth-First Search** were tested on randomly generated logical satisfaction problems for different values of **M**.

Each value of **M** corresponds to a separate set of experiments stored in a **ZIP file**.

For each M:
- 10 runs of **Hill-Climbing**
- 10 runs of **Depth Search**
- Output files showing whether a solution was found
- Execution times for each run

---

## Repository Structure

Each ZIP contains the results for one M value:


Inside each ZIP you will find files such as:
solution_hill_1_run1.txt
solution_hill_1_run2.txt
...
solution_hill_2_run1.txt
solution_hill_2_run2.txt
...
solution_depth_1.txt
solution_depth_2.txt
...
solution_depth_10.txt


These files contain the detailed outputs of each algorithm run.

---

## Included Analysis

The repository also contains (if uploaded):

- **results.xlsx**  
  A complete analysis including:
  - Success percentage per M
  - Execution time (per run + averages)
  - Comparison Hill-Climbing vs Depth
  - Performance curves and plots

- **report.pdf** *(optional)*  
  A written summary of the experimental findings.

---

## Summary of Findings

- **Hill-Climbing** performs very well for small M/N ratios, but its success rate drops when the problem becomes harder.
- **Depth Search** maintains higher stability but requires significantly more computation time.
- The hardest region appears around **M/N > 600**, where success rates for both algorithms decrease dramatically.

---

## How to Use the Files

1. Download any ZIP folder (e.g., `M=1000.zip`)
2. Extract the contents locally
3. Inspect the `.txt` files to see:
   - Whether a solution was found
   - The steps taken by each algorithm
   - Execution time for each run

---

## Author
**Vasiliki Stamatogianni**  
AI Assignment 2 – Experimental Study  
Department of Applied Informatics

