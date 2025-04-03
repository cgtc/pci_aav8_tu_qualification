# AAV8 TU Assay Qualification

IMPORTANT NOTE: I (Joe) created this repo to do AAV8 assay qualification in Dragos' absence. But did not realise he had already created an empty repo for this purpose (aav8_tu_qualification). I used the AAV9 qmd as a template off of which I made the report, and then looked in some other repos to see how Dragos presented the accuracy measurements. This has been sent to Wilson and Sharon now.

## Data

The data is provided as an `xlsx` file in the `data/` folder.

## Analysis

The analysis is available in the `aav8_tu_qualification.qmd` file.

### Parameters assessed

- Specificity: 50-200% recovery of spiked sample, -ve ctrl < LoD
- Accuracy (relative to TU dev runs): 50-200% (**FIO**)
- Precision (CV):
  - Repeatability <= 40%
  - Intermediate Precision <= 50%
- Linearity (R^2): >= 0.9
- LOQ/LLOD

## Report

The report can be generated from the `qmd` file and rendered as `html`.

### Requirements

- R (>= 4.2.0)
- quarto (>= 0.4.0)
