# Data accompanying the manuscript "Lysine-deficient proteome can be regulated through non-canonical ubiquitination and ubiquitin-independent proteasomal degradation"

<img src="readme_pics/lysine_deserts_definition.png" width="900" class="center" />

[![Python 3.9](https://img.shields.io/badge/python-3.9-blue.svg)](https://www.python.org/downloads/release/python-360/)
[![Project Status: Active - The project has reached a stable, usable
state and is being actively
developed.](http://www.repostatus.org/badges/latest/active.svg)](http://www.repostatus.org/#active)
[![License: CC BY 4.0](https://i.creativecommons.org/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

---


# Overview

This repository contains codes and auxiliary data to article "Lysine-deficient proteome can be regulated through non-canonical ubiquitination and ubiquitin-independent proteasomal degradation" by Szulc et al., 2023.

# What is a lysine desert and why is it important?

Lysine desert is a continuous lysine-less region of a protein. Such lysine deserts have been shown to counteract the ubiquitin-dependent turnover of equipped proteins. Understanding the role of such regions in protein functioning and degradation can shed new light on the regulation of the ubiquitin-proteasome system and play role in the development of targeted protein degradation therapies, as VHL, a crucial E3 ligase in proteolysis targeting chimeras (PROTACs) development, has an extensive lysine deserts, which elongated in the course of evolution.

# Installation

Recommended usage of the jupyter notebooks deposited in this repository is in a conda environment.

## Conda environment

1. Install conda

      Please refer to the [conda manual](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html) and install the conda version with Python 3.x according to your operating system.

2. Clone the repository

      `git clone https://github.com/n-szulc/fingernat.git`

3. Create conda environment

      `conda env create -f /environment.yml`

# About the repository

## Architecture

There are four main directories with codes required for performing analyses described in Szulc et al., 2013, namely `Proteomes_analysis`, `OGs_analysis`, `Human_proteome_detailed_analysis`, and `Structral_lysine_deserts_search`.

Each of the abovementioned directories contains two jupyter notebooks: `Download_data.ipynb` and `Pipeline.ipynb`. `Download_data.ipynb` is required to run prior `Pipeline.ipynb` as it allows to download data for the analyses.

All the notebooks are extensively documented with all the analyses' steps described.

## Order of computational analyses

Codes from `Proteomes_analysis` and `OGs_analysis` may be run independently from other analyses.

The order for performing analyses from `Human_proteome_detailed_analysis` and `Structral_lysine_deserts_search` is as follows:
1. `Proteomes_analysis/Download_data.ipynb`
2. `Structral_lysine_deserts_search/Download_data.ipynb`
3. `Human_proteome_detailed_analysis/Download_data`
4. `Human_proteome_detailed_analysis/Pipeline.ipynb`
5. `Structral_lysine_deserts_search/Pipeline.ipynb`

## Supplementary tables

All supplementary tables generated during this study are deposited in subdirectories of appropriate analyses and accompanied by README files with description of their content and each column.

## Experimental data

The `Experimental_data` directory contains raw luminescence and fluorescence measurements from the cycloheximide chase and NanoBRET ubiquitination assays.

# Feedback, issues, and questions

We welcome any feedback, please send an email to Natalia Szulc ![](https://img.shields.io/badge/nszulc-%40iimcb.gov.pl-brightgreen)

# How to cite

If you used codes or datasets from this repository, please cite:

**Lysine-deficient proteome can be regulated through non-canonical ubiquitination and ubiquitin-independent proteasomal degradation**  
Natalia A. Szulc, Małgorzata Piechota, Pankaj Thapa, Wojciech Pokrzywa
bioRxiv
doi:

# License

This repository is licensed under the [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.

# Funding

This research was supported by the National Science Centre, Poland (grant PRELUDIUM number 2021/41/N/NZ1/03473 to N.A.S. and grant SONATA-BIS number 2021/42/E/NZ1/00190 to W.P.).
