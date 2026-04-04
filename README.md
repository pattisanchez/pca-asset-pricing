# PCA in Asset Pricing

## Overview

This project applies **Principal Component Analysis (PCA)** to equity return panels to uncover latent risk factors and compare them with Fama–French factors.

---

## Data

* Fama–French 3 Factors
* 100 Size–B/M Portfolios
* 49 Industry Portfolios
* International Portfolios

Source: Ken French Data Library

---

## Methodology

* Data cleaning and alignment
* Excess return computation
* PCA (correlation-based)
* Factor interpretation via loadings
* Comparison with Fama–French factors

---

## Results

* PC1 ≈ Market factor
* PC2 and PC3 capture size and value effects
* Strong alignment with Fama–French factors
* Factor structure varies across datasets

---

## Project Structure

```bash
notebook/PCA_Ken_French.ipynb
```

---

## Author

Patricia Sánchez
Business Analytics & International Relations
Wharton Exchange Student

## Acknowledgements
This project builds on concepts introduced in a FNCE 2370 recitation.

While the initial motivation and datasets were inspired by course material, the full implementation, data pipeline, PCA analysis, and interpretation were independently developed and extended.
