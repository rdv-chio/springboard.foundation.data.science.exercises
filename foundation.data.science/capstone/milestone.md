---
title: "Springboard Foundations of Data Science"
author: "Rocio Dominguez Vidana, PhD"
date: "August 20, 2016"
output: html_document
---

# Capstone Proposal

## 1: What is the problem you want to solve?

Identify a gene expression signature with an ROC over 75%.

## 2: Who is your client and why do they care about this problem? In other words, what will your client DO or DECIDE based on your analysis that they wouldn’t have otherwise?

The client company has extensive experience developing prognosis tests with “gene expression signatures”. Using a combination of publically available data curated with further validation. They have developed a product which can be used to predict aggressivity of another neoplasic disease. Products like these could be considered successful if they are eventually treated as “standard of care”, and thus, reimbursed by insurance companies.

They have decided to focus on developing a product for sarcomas, a rare type of cancer in humans that arises from transformed cells of mesenchymal origin (bone, cartilage, fat, muscle, vascular, hematopoietic tissues, etc). Within sarcomas there is extreme genetic variability, 30% of them have distinct traceable features that can be considered the cause of those particular tumors. However, for the other 70% percent, there is really no traceable genetic modification.

## 3: What data are you going to use for this? How will you acquire this data?

The data is publically available in the following links

RNASeq TCGA-SARC dataset from [GDC Data Portal](https://gdc-portal.nci.nih.gov/) data (in log2(normalized_count+1) units).

This will be called TCGA dataset

[Expression data from Complex genetics sarcomas (cohort 1 and 2)](http://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE21050)  The data was measured in Affymetrix Human Genome U133 Plus 2.0 Array

This will be called CINSARC dataset

## 4: In brief, outline your approach to solving this problem (knowing that this might change later).

1: Normalize data (since it is on two different platforms)

2: Develop modelling approaches based on random forest, neural networks, etc

3: Cross-validate analysis

4: Determine ROC for models or merged models

## 5: What are your deliverables? Typically, this would include code, along with a paper and/or a slide deck.

Code and presentation
