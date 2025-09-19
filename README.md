# PCA and Clustering for Genomic Data Analysis
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/release/python-390/)

**Author:** Mohammad Shahnewaz Morshed  
**Date:** 23 March 2024  

---

## Problem Statement
Modern genomic experiments generate massive datasets with thousands to millions of features, such as DNA variants (SNPs), k-mers, or gene expression levels. Analyzing this data directly is difficult because many features are highly correlated, measured on different scales, and embedded in a very high-dimensional space. These properties make it challenging to detect meaningful biological signals, and standard statistical methods can often become unstable or misleading when applied to such data.

## Objective
The goal of this project is to show how Principal Component Analysis (PCA) can reduce the complexity of genomic data and how k-means clustering can group samples with similar genetic profiles. PCA transforms the data into a smaller set of uncorrelated variables that capture the main sources of variation, while clustering applied to these new variables helps reveal hidden patterns such as population structure, technical effects, or biologically meaningful groupings. Together, these methods provide a reproducible framework for exploring structure in genomic datasets.

## Methodology
A detailed statistical explanation of the approach, including problem formulation, data preprocessing, PCA decomposition, validation, and clustering, is provided in the methodology document: [Methodology]([./Methodology%20-%20analysis%20of%20genomic%20data.pdf](https://github.com/ShahnewazMorshed/Principal-Component-Analysis/blob/main/Methodology.pdf))

---

## Project Structure

- **Data:** 
  - [Data](https://github.com/ShahnewazMorshed/Principal-Component-Analysis/blob/main/ccrescentus.fa): The genomic sequence used in this project comes from a FASTA file of *Caulobacter crescentus*.

- **Python Notebooks:**
  - [PCA and K-Means Decipher Genome](https://github.com/ShahnewazMorshed/Principal-Component-Analysis/blob/main/PCA%20and%20K-Means%20Decipher%20Genome.ipynb): Principal Component Analysis (PCA), k-means clustering, genomic data.
