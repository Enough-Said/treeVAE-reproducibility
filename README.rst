========================================
treeVAE-Reproducibility - Forked for HTIN5005 Assignment 1
========================================

This is a fork of the original reproducability repo by Khalil Ouardini, which 
was made to reproduce the results of the "Reconstructing unobserved cellular 
states from  paired single-cell lineage tracing and transcriptomics data" paper. 

In this fork, I made a few minor changes to the requirements file and a typo in 
the Metastasis notebook. I also changed this readme file. 


Original Repo
======

https://github.com/khalilouardini/treeVAE-reproducibility


Guide (My Use Case Only)
======

I decided to reproduce the Metastasis data analysis, which utilises real cell 
lineage tracing data. I used ``uv``, so the example commands will reflect that, but 
all the steps can be replicated using ``pip`` and ``python``/``python3``. My steps were:

1. Create a python environment and enter it (``uv venv`` and ``source .venv/bin/activate``)

2. Install dependencies (``uv pip install -r requirements.txt``)

3. Open the notebook ``scvi/external/notebooks/Metastasis.ipynb`` and follow the instructions / run all the cells


Original Paper
======

Link: https://doi.org/10.1101/2021.05.28.446021 

Reference: Ouardini, K., Lopez, R., Jones, M. G., Prillo, S., Zhang, R., Jordan, M. I., & Yosef, N. (2021,
May 30). Reconstructing unobserved cellular states from paired single-cell lineage tracing
and transcriptomics data. https://doi.org/10.1101/2021.05.28.446021
