# AI-Assisted CRISPR-Cas12a Guide RNA Design for Mycobacterium tuberculosis

## Overview

This project presents a computational pipeline for identifying and optimizing CRISPR-Cas12a guide RNAs targeting the Mycobacterium tuberculosis (MTB) genome. The workflow integrates sequence analysis, off-target screening, machine learning, and biological optimization to prioritize high-quality guide candidates.

## Objectives

- Identify Cas12a PAM sites (TTTN)
- Extract 20-bp candidate guide RNAs
- Perform off-target analysis
- Rank guides using machine learning
- Optimize guides using biological design principles

## Workflow

MTB Genome
→ PAM Detection
→ Guide Extraction
→ Initial Scoring
→ Off-target Analysis
→ Machine Learning Ranking
→ Biological Optimization
→ Final Guide Recommendation

## Methods

- Python
- Biopython
- Pandas
- Scikit-learn
- Matplotlib

## Results

The final pipeline integrates biological and machine learning criteria to generate optimized Cas12a guide RNA recommendations for MTB.

## Future Work

- Genome-wide off-target analysis using Bowtie/Cas-OFFinder
- RNA secondary structure prediction
- Experimental validation

## Project Files

* [View the Python Notebook](Cas12a_MTB_Target_Design_v3.ipynb) - Click here to see the full code and data analysis.


## Author

Oscar

BME | KMITL
