# README

# Acute Myeloid Leukemia Heatmap Analysis

[![License](https://img.shields.io/github/license/alsf/refinebio)](LICENSE)

This repository contains an R Markdown analysis pipeline for creating heatmaps from Acute Myeloid Leukemia (AML) RNA sequencing data. The analysis focuses on identifying gene expression patterns across different AML samples and treatments.

## Overview
```  Yesssss!

This analysis utilizes RNA sequencing data from 19 AML model mice samples 
, originally published in Shih et al., 2017 
. The dataset has been processed and quantile normalized through refine.bio, enabling direct analysis of gene expression patterns.

## Key Features

* Analysis of 19 AML model mice samples
* Gene variance-based filtering
* Hierarchical clustering visualization
* Treatment condition annotations
* Reproducible workflow with R Markdown

## Dependencies

Required R packages:



## Data Structure

The analysis requires two main files:



Both files are downloaded from refine.bio and stored in the 
 directory.

## Analysis Workflow

The pipeline consists of several key steps:



## Output Files

The analysis generates:



## Usage Instructions

1. Clone the repository
2. Install required dependencies using the provided installation script
3. Download the dataset from refine.bio
4. Run the R Markdown document to generate all outputs

## Citation

This analysis adapts methods from the refine.bio-examples notebook 
 and utilizes data from Shih et al., 2017 
. When using this analysis pipeline, please cite both the original publication and this adaptation.
