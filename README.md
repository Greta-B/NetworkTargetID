# NetworkTargetID

**Data/**
Contains all input data required for feature construction and model training. This includes:
  - Curated ccRCC disease-associated gene signatures
  - CRISPR knockout gene dependency scores from the DepMap database
  - The human protein-protein interaction network from the STRING database (confidence score ≥400)

**Feature_space_generation/**
Includes scripts for computing the full set of 139 machine learning features for each gene.

**ML_training_testing/**
Contains scripts for training and evaluating machine learning models.
