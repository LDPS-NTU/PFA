# Protein Function Annotation

## Motivation: 
Homology-based transfer is frequently used to predict protein functions of unannotated sequences through similarity analysis between the target and previously annotated sequences. The most direct and accessible homology-based transfer approach is sequence alignment. However, its accuracy varies with keywords. To assess the reliability of alignment-based prediction, we applied a 10-fold cross-validation test in SWISS-Prot database. We compared Matthews correlation coefficient (MCC), sensitivity, and precision, and examined different parameter settings used in the alignment-based methods, with BLASTp and PSI-BLAST.

## Results: 
The prediction performance of the methods differed with the categories of keywords annotated. The keyword categories in SWISS-Prot can be classified into four levels according to their performances. The keywords in the first two levels can be confidently used for prediction, whereas those in the other two levels are less reliable.
The predictions made with the two algorithms, BLASTp and PSI-BLAST, were close. Therefore, BLASTp is recommended for protein function prediction owing to its lower computational complexity.
