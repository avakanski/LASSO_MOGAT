# LASSO–MOGAT: A Multi-omics Graph Attention Framework for Cancer Classification

[![Academia Biology](https://img.shields.io/badge/Academia_Biology-10.20935/AcadBiol7325-blue.svg)](https://doi.org/10.20935/AcadBiol7325)  [![arXiv](https://img.shields.io/badge/arXiv-2408.17384-b31b1b)](https://arxiv.org/abs/2408.17384)

Authors: Fadi Alharbi, Aleksandar Vakanski, Murtada K. Elbashir, Mohanad Mohammed

The application of machine learning (ML) methods to analyze changes in gene expression patterns has recently emerged as a powerful approach in cancer research, enhancing our understanding of the molecular mechanisms underpinning cancer development and progression. Combining gene expression data with other types of omics data has been reported by numerous works to improve cancer classification outcomes. Despite these advances, effectively integrating high-dimensional multi-omics data and capturing the complex relationships across different biological layers remain challenging. This article introduces Least Absolute Shrinkage and Selection Operator–Multi-omics Gated Attention (LASSO–MOGAT), a novel graph-based deep learning framework that integrates messenger RNA, microRNA, and DNA methylation data to classify 31 cancer types. By utilizing differential expression analysis (DEG) with Linear Models for Microarray (LIMMA) and LASSO regression for feature selection and leveraging graph attention networks (GATs) to incorporate protein–protein interaction (PPI) networks, LASSO–MOGAT effectively captures intricate relationships within multi-omics data. Experimental validation using fivefold cross-validation demonstrates the method’s precision, reliability, and capacity to provide comprehensive insights into cancer molecular mechanisms. The computation of attention coefficients for the edges in the graph, facilitated by the proposed graph attention architecture based on PPIs, proved beneficial for identifying synergies in multi-omics data for cancer classification.

## 📁 Repository Organization
The code in the notebook [LASSO_MOGAT.ipynb](LASSO_MOGAT.ipynb) in the repository presents the proposed framework that employs a Graph Attention Network (GAT) with a PPI (protein-protein interaction) network graph structure for cancer classification using multi-omics data integration of mRNA, miRNA, and DNA methylation.

The file [PPI.csv](PPI.csv) contains information about the PPI (protein-protein interaction) network. 

The file containing the multi-omics data (mRNA, miRNA, and DNA methylation) can be downloaded from: [here](https://www.idahofallshighered.org/vakanski/Codes_Data/mRNA_miRNA_Meth_integrated.csv).


## ▶️ Use
The codes are provided as a Jupyter Notebook file. To reproduce the results, run the .ipynb file. 

## 📖 Citation
If you use the codes or the methods in your work, please cite the following <a href="https://www.academia.edu/2837-4010/2/3/10.20935/AcadBiol7325">article</a>:   

    @ARTICLE{Alharbi2024,
    TITLE={LASSO–MOGAT: A multi-omics graph attention framework for cancer classification},
    AUTHOR={Alharbi, Fadi and Vakanski, Aleksandar and Elbashir, Murtada K. and Mohammed, Mohanad},
    JOURNAL = {Acedemia Biology},
    YEAR = {2024},
    VOLUME = {2},
    ISSUE = {3}
    PAGES = {1-13},
    URL = {https://www.academia.edu/2837-4010/2/3/10.20935/AcadBiol7325},
    DOI = {10.20935/AcadBiol7325}
    }

## 🚩 License
<a href="License - MIT.txt">MIT License</a>

## ✉️ Contact or Questions
<a href="https://www.webpages.uidaho.edu/vakanski/">A. Vakanski</a>, e-mail: vakanski at uidaho.edu

