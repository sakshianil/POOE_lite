# POOE-Lite: Effector Prediction and Promoter Motif Analysis in Oomycetes

![Oomycete](https://img.shields.io/badge/Oomycete-Pipeline-blue) ![Notebook](https://img.shields.io/badge/Platform-Kaggle/Colab-orange) ![License](https://img.shields.io/badge/License-MIT-green)

This repository hosts the `pooe-lite.ipynb` notebook—a lightweight, interpretable pipeline built to identify effector proteins across oomycete genomes and analyze the cis-regulatory motifs in their upstream promoter regions. It simplifies the integration of effector predictions with motif discovery and known transcription factor binding site (TFBS) mapping.

## Overview

Effector proteins secreted by oomycete pathogens manipulate host defenses and facilitate infection. This notebook:
- Predicts effector proteins using lightweight bioinformatics filters.
- Differentiates putative effectors vs. non-effectors.
- Analyzes 1000 bp upstream promoter regions.

## Contents

| File | Description |
|------|-------------|
| `pooe-lite.ipynb` | Main notebook for effector prediction and promoter motif analysis |
| `README.md` | Project overview and usage instructions |

## How to Use

You can run this notebook:
- On [Kaggle](https://www.kaggle.com) with GPU support
- On [Google Colab](https://colab.research.google.com/) (ensure `meme-suite` or `bio_embeddings` dependencies are installed)

### Dependencies
- Python ≥ 3.7
- Biopython
- Pandas, NumPy, Matplotlib
- `bio_embeddings` (optional for future embedding support)
- Jupyter or IPython environment

## Features
- Classification into **secreted** and **non-secreted** proteins using `POOE` logic on results obtained from SignalP and DeepTM.
- Downstream-ready outputs for integration with R/Nextflow pipelines.
- Functional comparison of **cis-regulatory architectures** across effector classes.
- Ideal for **multi-species comparative analysis** in oomycetes.

## Biological Application
This notebook is used for studying transcriptional regulation of effectors in:
- *Phytophthora infestans*
- *Phytophthora sojae*
- *Plasmopara halstedii*
- *Pythium ultimum*
- *Hyaloperonospora arabidopsidis*

Promoter-level differences in motif content between secreted and non-secreted effectors offer insight into the **modular regulatory networks** underpinning infection strategies.


## Citation & Credits

### Original POOE Tool

> This notebook builds upon the excellent work of Zzd Lab and their published tool, **POOE: Prediction of Oomycete Effectors**, available at  
> [https://github.com/zzdlabzm/POOE](https://github.com/zzdlabzm/POOE)  
> Please cite the original POOE tool if you use this notebook (https://github.com/sakshianil/POOE_lite) in your research.

### 🙏 Acknowledgments

> We acknowledge **OpenAI's ChatGPT** for assisting in structuring this notebook and for helping adapt our analysis tools (MEME Suite, TOMTOM, FIMO, etc.) into a **Nextflow-compatible pipeline** to support scalable and reproducible research workflows.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for details.

---

**Contact:** sakshi.bharti@senckenberg.de or sakshi.bhartibioinfo@gmail.com  
**Keywords:** Oomycetes, Effector Proteins, Promoter Motifs, Plant Pathogens, Transcriptional Regulation, Nextflow Pipelines

