# NetworkTargetID

**Data/**
Contains all input data required for feature construction and model training. This includes:
  - Curated ccRCC disease-associated gene signatures
  - CRISPR knockout gene dependency scores from the DepMap database
  - The human protein-protein interaction network from the STRING database (confidence score ≥400)

**Feature_space_generation/**
Includes scripts for computing the full set of 139 machine learning features for each gene, capturing: 
  - Genetic dependency metrics across 16 ccRCC cell lines
  - Node centrality within the STRING PPI network
  - Neighborhood structure and proximity to disease-associated and drug target signatures

**ML_training_testing/**
Contains scripts for training and evaluating machine learning models.
  - Addresses class imbalance by generating multiple balanced training and test sets through repeated random sampling of the negative class
