# Automated Seed Counting: Classical Morphology vs. Machine Learning

## Abstract
This project presents a comprehensive study on the automated counting of seeds in digital images, addressing challenges such as uneven illumination, high object density, and varying texture. The study implements and evaluates three distinct workflows:
1. **Classical Segmentation:** Morphological transformations (Top-Hat, Difference of Gaussians) and Watershed segmentation.
2. **Texture-Based Analysis:** Local Binary Patterns (LBP) for separating clustered objects.
3. **Machine Learning:** Random Forest regression to estimate counts based on global image statistics.

## Project Structure
* `main_analysis.ipynb`: The complete Python code for all three workflows, including visualization and metric evaluation.
* `Project_Report.pdf`: Detailed documentation of the mathematical theory, algorithm design, and result analysis.

## Key Results
* **Robustness:** The classical workflow demonstrated high resilience to varying lighting conditions due to the decoupling of illumination correction from detection.
* **Accuracy:** Quantitative analysis (Precision-Recall curves) confirmed that the Machine Learning approach effectively reduced error margins in high-density clusters.

## Installation & Usage
To reproduce the analysis:

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
