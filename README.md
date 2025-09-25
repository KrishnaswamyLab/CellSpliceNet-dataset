# Dataset of CellSpliceNet: Interpretable Multimodal Modeling of Alternative Splicing Across Neurons in *C. elegans*
Alternative splicing profoundly diversifies the transcriptome and proteome, but decoding its regulatory mechanisms remains a challenge. We introduce CellSpliceNet, an interpretable transformer-based multimodal deep learning framework designed to predict splicing outcomes across the neurons of C. elegans. By integrating four complementary data modalities, namely long-range genomic sequence, local regions of interest (ROIs) in the RNA sequence, secondary structure, and gene expression, CellSpliceNet captures the complex interplay of factors that influence splicing decisions within the cellular context. CellSpliceNet employs modality-specific transformer embeddings, incorporating structural representations guided by mutual information and scattering graph embeddings. To this end, a novel and carefully designed multimodal multi-head attention mechanism preserves the integrity of each modality while facilitating selective cross-modal interactions, notably allowing gene expression data to inform sequence and structural predictions. Attention-based pooling within each modality highlights biologically critical elements, such as canonical intron–exon splice boundaries and accessible single-stranded RNA loop structures within the exon. Quantitative comparisons with current state-of-the-art methods demonstrated CellSpliceNet‘s superior predictive accuracy (Spearman ρ = 0.88) and high accuracy across diverse neuron subtypes.

**Authors:** Arman Afrasiyabi, Jake Kovalic, Chen Liu, Egbert Castro, Alexis Weinreb, Erdem Varol, David M. Miller III,  Marc Hammarlund,  Smita Krishnaswamy 

[**Preprint (bioRxiv)**](https://www.biorxiv.org/content/10.1101/2025.06.22.660966v1) // 
[**Repository**](https://github.com/KrishnaswamyLab/CellSpliceNet)  // 
[**Dataset**](https://github.com/KrishnaswamyLab/CellSpliceNet-dataset)


## Overview

This repository contains the data used to train and evaluate **CellSpliceNet**, our multimodal framework for modeling and interpreting cell-type–specific alternative splicing profiles in the _C. elegans_ nervous system. 

## Download

The v0.1 release of the CellSpliceNet dataset is available here:  
[Release v0.1 (Dataset)](https://github.com/KrishnaswamyLab/CellSpliceNet-dataset/releases/tag/v0.1-dataset)

You can download the entire archive as a ZIP file directly from the release page.

