# Similarity and Diversity Analysis for DYRK1B Ligand Discovery

## Overview

This repository contains a cheminformatics workflow for similarity-based virtual screening targeting DYRK1B.
The objective of this project is to identify compounds structurally related to the known inhibitor **AZ191** using a combination of:

Chemical similarity searching

Drug-likeness filtering

Diversity analysis

## Project Context
This project was developed as part of the challenge of the **9ADD Workshop at Palacký University Olomouc**. 
The challenge focused on applying computational drug discovery methods to identify compounds similar to **AZ191**, a known **DYRK1B** inhibitor.

## Virtual Screening Strategy

### The screening pipeline consists of several stages:

Data preprocessing

Loading the chemical dataset

Cleaning invalid SMILES

Removing duplicates

### Molecular fingerprint generation

Morgan fingerprints (ECFP4)

2048-bit fingerprint vectors

### Similarity searching

Tanimoto similarity calculation against **AZ191**

Ranking molecules by similarity score
Drug-likeness andLipinski's Rule of Five
Filtering compounds with unfavorable properties

### Diversity analysis including:

Butina clustering

Identification of structurally diverse compounds

### Visualization
Similarity distribution plots

Molecular property analysis

Structural visualization of top compounds

## Output

The workflow produces:

Filtered dataset of drug-like compounds

Ranked 100 compounds based on similarity to **AZ191**

Clustered compounds ensuring chemical diversity

Visualization plots for dataset exploration

These results can be used as input for subsequent molecular docking studies.



