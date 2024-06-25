# Suzuki_Yield_Prediction
This is a non-exhaustive list of methods for creating machine learning algorithms for yield prediction.

## Datat_set : Suzuki 
This dataset originates from a recent publication by a Pfizer team. Utilizing flow chemistry, they conducted a high-throughput reaction screening of the Suzuki–Miyaura C–C coupling reaction. This screening involved 11 reactants, 12 ligands, 8 bases, and 4 solvents, resulting in a total of 5760 reactions. The predictive target in this dataset is the reaction yield. (D. Perera, J. W. Tucker, S. Brahmbhatt, C. J. Helal, A. Chong, W. Farrell, P. Richardson and N. W. Sach, Science, 2018, 359, 429–434.)

## First method : DRFP  
CHEMSITRY_ML_XGBOOST_Fingerprintonly(DRFP)SMILE.ipynb --> Description : This a jupyter notebook file, using to test this method.  

Suzuki_DRPF_main.ipynb --> Description : Main Python script, used to launch the script from a high computing environment.

Note : As a beginner, there may be numerous opportunities for improvement in this notebook. I was largely inspired by the work of Alexander A. Ksenofontov and co (10.1016/j.jocs.2023.102173),Jean-Louis Reymond and co (10.1039/d1dd00006c) and the André OLIVEIRA's notebook (Predicting molecule properties based on its SMILES), thanks to them.

## Second method : Rdkit Descriptor 
CHEMSITRY_ML_XGBOOST_RDKIT_SMILE.ipynb --> Description : This a jupyter notebook file, using to test this method.  

Suzuki_rdkit_main.ipynb --> Description : Main Python script, used to launch the script from a high computing environment.

Note : As a beginner, there may be numerous opportunities for improvement in this notebook. I was largely inspired by the work of Alexander A. Ksenofontov and co (10.1016/j.jocs.2023.102173) and the André OLIVEIRA's notebook (Predicting molecule properties based on its SMILES), thanks to them. 

## Third method : RXNBERT Fingerprints Descriptor 
Generate RXNBERT fingerprints from reaction SMILES.ipynb --> Description : This a jupyter notebook file, using to product RXNBERT fingerprint 
CHEMSITRY_ML_XGBOOST_Fingerprintonly(RXNBERT)SMILE.ipynb --> Description : This a jupyter notebook file, using to test RXNBERT fingerprint   

Suzuki_RXNBERT_main.ipynb --> Description : Main Python script, used to launch the script from a high computing environment.

finger.csv --> Description : DataFrame containing RXNBERT fingerprint 

