# DrugGenius
The main packages used are RDKit (version 2023.09.6) and scikit-learn (version 1.5.0). 

# Structure of repository

- Data folder: Contains csv files of SMILES of tested and untested molecules, with and without added descriptors
- Main.ipynb: Contains importing libraries, opening files, scaling and PCA, data boxplots, train_test_split, GridSearchCV, accuracy, confusion Matrices, scores, prediction untested molecules
- data_analysis.ipynb: Contains EDA
- retrieve_data.ipynb: Script to generate file with final chosen descriptors
- Add_descriptors.ipynb: Script to compute descriptors and fingerprints from SMILES


