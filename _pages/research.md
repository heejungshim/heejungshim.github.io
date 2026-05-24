---
title: "Heejung Shim Lab - Research"
layout: textlay
excerpt: "Heejung Shim Lab -- Research"
sitemap: false
permalink: /research/
---

# Research

Our group develops statistical methods and computational tools for applications to a wide range of biological questions. We emphasize close communication with biologists to ensure our approaches address real biological questions while respecting the properties of the data.

---

## 1. Multi-scale Analyses of Functional Data

High-throughput sequencing technologies produce high-resolution genomic measurements that are best treated as functional data. We develop wavelet-based statistical methods to analyze these measurements.

Our **[WaveQTL](https://github.com/heejungshim/WaveQTL)** software uses wavelets for genetic association analysis of functional phenotypes and identified 50% more dsQTLs than a typical window-based analysis in chromatin accessibility studies.

Our **[multiseq](https://github.com/heejungshim/multiseq)** package models count data directly using Bayesian multi-scale models for Poisson processes. Testing on ATAC-seq samples showed that multiseq detected substantially more differences in chromatin accessibility between conditions compared to competing approaches.

---

## 2. Transcription Factor Binding & Motif Finding

We develop hierarchical multi-scale models for Poisson processes to improve transcription factor binding site inference from DNase-seq data. Our **[msCentipede](http://rajanil.github.io/msCentipede/)** software enhances detection accuracy over existing approaches.

We have also developed methods for motif discovery that integrate ChIP-seq quantitative information, showing superior sensitivity and specificity — especially when the motif of interest has low abundance.

---

## 3. Ribosome Profiling & Coding Sequence Annotation

The **[riboHMM](https://github.com/rajanil/riboHMM)** hidden Markov model leverages ribosome profiling data for precise coding sequence annotation at subcodon resolution, enabling discovery of thousands of novel translated open reading frames.

We also develop tools such as **[NanoSplicer](https://github.com/shimlab/NanoSplicer)** and **[McSplicer](https://github.com/canzarlab/McSplicer)** for accurate identification of splice junctions and estimation of splice site usage from sequencing data.

---

## 4. Single-cell and Spatial Genomics

We develop methods for analyzing single-cell and spatial transcriptomics data. Our tools include:

- **[BLAZE](https://github.com/shimlab/BLAZE)**: identification of cell barcodes from long-read single-cell RNA-seq
- **[sgcocaller](https://gitlab.svi.edu.au/biocellgen-public/sgcocaller) / [comapr](https://github.com/ruqianl/comapr)**: personalised haplotype assembly and crossover map analysis

We are actively developing new methods for spatial transcriptomics, including approaches for identifying molecular niches and spatially variable features.

---

## 5. Genome-wide Association Analysis

Our **[mvBIMBAM](https://github.com/heejungshim/mvBIMBAM)** software enables joint analysis of multiple related phenotypes in genome-wide association studies. We have shown that joint analyses can considerably increase power to detect associations compared with conventional univariate approaches.

---

## 6. Bayesian Co-estimation of Alignment & Tree (BayesCAT)

**[BayesCAT](https://github.com/heejungshim/BayesCAT)** jointly estimates sequence alignment and phylogeny while modeling arbitrary-length overlapping indel events, improving phylogenetic inference in challenging settings.
