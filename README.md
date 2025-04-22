# POOE-Lite: Effector Prediction and Promoter Motif Analysis in Oomycetes

![Oomycete](https://img.shields.io/badge/Oomycete-Pipeline-blue)
![Notebook](https://img.shields.io/badge/Platform-Kaggle/Colab-orange)
![License](https://img.shields.io/badge/License-MIT-green)

This repository contains the `pooe-lite.ipynb` notebook—a simplified, user-friendly implementation of the [POOE](https://github.com/zzdlabzm/POOE) tool for effector prediction, designed to run efficiently on Kaggle notebooks or Google Colab. This version facilitates quick analysis of secreted and non-secreted effector genes and their associated promoter motifs across oomycete pathogens.

---

## Overview

Effector proteins are key players in the virulence strategies of oomycetes, enabling suppression of host immunity. This notebook:

- Identifies effector proteins using filters from the original POOE model.
- Applicable on oomycete proteomes


---

## Repository Contents

| File | Description |
|------|-------------|
| `pooe-lite.ipynb` | Notebook for streamlined effector prediction and promoter motif discovery |
| `README.md` | Project documentation and instructions |

---

##  How to Use

Run the notebook on:
- [Kaggle Notebooks](https://www.kaggle.com/)
- [Google Colab](https://colab.research.google.com)

### Required Tools & Packages
- Python ≥ 3.7
- Biopython, Pandas, NumPy
- bio_embeddings (optional)
- Jupyter or IPython environment

---

## Features

- Efficient **effector classification** using `POOE` logic for both secreted and non-secreted genes.
- Results obtained are best suited for downstram Promoter **motif discovery** using MEME Suite and **motif matching** against JASPAR & ELM databases.
- Functional comparison of **cis-regulatory architectures** across effector classes.
- Ideal for **multi-species comparative analysis** in oomycetes.

---

## Biological Context

This tool is designed for studying transcriptional regulation of effectors in:
- *Phytophthora infestans*
- *Phytophthora sojae*
- *Plasmopara halstedii*
- *Pythium ultimum*
- *Hyaloperonospora arabidopsidis*

Promoter-level differences in motif content between secreted and non-secreted effectors offer insight into the **modular regulatory networks** underpinning infection strategies.

---

## Citation & Credits

### Original POOE Tool

> This notebook builds upon the excellent work of Zzd Lab and their published tool, **POOE: Prediction of Oomycete Effectors**, available at  
> [https://github.com/zzdlabzm/POOE](https://github.com/zzdlabzm/POOE)  
> Please cite the original POOE tool if you use this notebook in your research.

### Acknowledgments

This repository is part of the PhD research conducted by Sakshi Bharti at the Senckenberg Biodiversity and Climate Research Center, affiliated with Goethe University, Frankfurt. The work was carried out under the supervision of Prof. Dr. Marco Thines, with the aim of developing reproducible and scalable pipelines for effector prediction and promoter motif analysis in oomycetes.

Special thanks to:
- The developers of the original [POOE tool](https://github.com/zzdlabzm/POOE), which this notebook builds upon.
- OpenAI, for providing AI assistance in drafting the workflow structure and standardizing documentation formats.
  
---

## License

Distributed under the MIT License. See `LICENSE` for details.

---

 **Contact:** sakshi.bharti@senckenberg.de  or sakshi.bhartiobioinfo@gmail.com ORCID: https://orcid.org/0000-0001-5356-7666
**Keywords:** Oomycetes, Effector Proteins, Promoter Motifs, POOE, Plant Pathogens, Transcriptional Regulation, Nextflow Pipelines

