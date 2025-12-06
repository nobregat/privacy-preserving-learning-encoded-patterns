# Learning from Encoded Patterns: A Recurrence Plot Approach for Privacy-Preserving Record Linkage

This repository contains the source code and experimental resources for the paper **"Learning from Encoded Patterns: A Recurrence Plot Approach for Privacy-Preserving Record Linkage"**.

## Abstract

Privacy-Preserving Record Linkage (PPRL) enables the integration of records referring to the same entities across multiple datasets without disclosing sensitive information. Traditional PPRL techniques often rely on predefined similarity metrics that may not capture complex data relationships (e.g., non-linear relationships), limiting linkage quality.

This work presents a **Cross Recurrence Plot (CRP)-based representation** of Bloom Filter pairs to train machine learning and deep learning classifiers capable of distinguishing matching and non-matching records directly from encoded bit patterns. The proposed workflow simplifies the PPRL process by replacing similarity thresholding with an ML-based decision model while maintaining privacy guarantees. Experimental results using real-world datasets demonstrate that the proposed approach outperforms traditional threshold-based methods in terms of linkage quality.

## Reference

If you use this code or data in your research, please cite our paper:

**DOI:** [10.1145/3748522.377992](https://doi.org/10.1145/3748522.377992)

> T. Nóbrega, D. Mestre, T. B. Araújo, D. Cassimiro, C. E. S. Pires, and K. Stefanidis. 2026. Learning from Encoded Patterns: A Recurrence Plot Approach for Privacy-Preserving Record Linkage. In *SAC '26: Symposium on Applied Computing, March 23–27, 2026, Thessaloniki, Greece*. ACM, New York, NY, USA.

## Repositories

The implementation of the proposed approach and related tools can be found in the following repositories:

  * **PPDM Core:** [https://github.com/thiagonobrega/ppdm](https://github.com/thiagonobrega/ppdm)
  * **Neural Networks for PPRL:** [https://github.com/thiagonobrega/nn\_pprl](https://github.com/thiagonobrega/nn_pprl)

## Notebooks & Experimental Data

The Jupyter notebooks and datasets used for the experiments and evaluation (including `eval_v1` and `eval_v2`) are available at the link below:

  * [**Access Experimental Notebooks (Google Drive)**](https://drive.google.com/drive/folders/1kxUWLRcwV_mTvD3Xy7mCv8LjYpNv0_on?usp=sharing)

## Authors

  * **Thiago Nóbrega** (Federal University of Campina Grande)
  * **Demetrio Mestre** (Federal University of Campina Grande)
  * **Tiago Brasileiro Araújo** (Federal Institute of Paraíba)
  * **Dimas Cassimiro** (Federal University of Agreste de Pernambuco)
  * **Carlos Eduardo S. Pires** (Federal University of Campina Grande)
  * **Kostas Stefanidis** (Tampere University)
