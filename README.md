# NN-GeneExpression
Neural network-based prediction of the drug response using gene expression groups.

This jupyter notebook demonstrates the implementation of ANN algorithm to predict response of cancer cells to specific drug treatment.

## Novelty
- Multiple sources for gene expression (RNA-Seq) and drug response (WST8)
    - CCLE
    - GDSC
    - TCGA (GDC data portal)
    - Lab-generated (Mainz)
- TMM-normalized gene expression counts in cancer cells are grouped into low and high expression by comparing to the average TMM-normlaized gene expression counts in cancer patients (data from TCGA)
- Logistic regression with regularization for gene selection
- ANN as a final prediction model

## To do
- Training the model to the specific cancer of interest
- Integrating gene mutations