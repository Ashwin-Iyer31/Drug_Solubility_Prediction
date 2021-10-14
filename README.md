# Drug_Solubility_Prediction
Predict Solubility by applying OLS, Ridge and Decision Tree to predict the solubility of molecules.<br>
Drug Solubility is an important Physical Chemical Property during drug design<br>

Process:<br>
1. Importing delaney's solubility dataset.<br>
2. Using rdkit to unpack SMILES to rdkit object<br>
3. Calculating Molecular Descriptors from rdkit Object, forming the X matrix<br>
4. Solubility from the dataset forms the Y vector.<br>
5. Splitting Training and Test set.<br>
6. Applying OLS and Decision Tree.<br>
7. Applying ridge, also finding best alpha manually and also using CV (Cross Validation).<br>
8. Visualizing and predicting.<br>

The notebook contains detailed information regarding every step taken.
