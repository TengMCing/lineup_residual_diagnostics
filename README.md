
<!-- README.md is generated from README.Rmd. Please edit that file -->

# A Plot is Worth a Thousand Tests: Assessing Residual Diagnostics with the Lineup Protocol

This repo contains the materials to fully reproduce the paper titled “A
Plot is Worth a Thousand Tests: Assessing Residual Diagnostics with the
Lineup Protocol” by Weihao Li, Dianne Cook, Emi Tanaka, and Susan
VanderPlas.

## Citation

Please cite the paper as:

Li et al. (2023) A Plot is Worth a Thousand Tests: Assessing Residual
Diagnostics with the Lineup Protocol . arXiv preprint. URL:
<http://arxiv.org/abs/2308.05964>

## Reproducibility

The main paper is written using R Markdown and contained in “paper.Rmd”.
To render this, you need to install all relevant packages. Two custom
packages are:

``` r
# OOP supports needed by `visage`
remotes::install_github("TengMCing/bandicoot")
# 
# Visual inference models and p-value calculation
remotes::install_url("https://github.com/TengMCing/visage/raw/master/built/visage_0.1.0.tar.gz")
```
