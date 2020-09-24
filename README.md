# EP-ENSVM
# 1. Description
EP-ENSVM is a computational approach for isoform function prediction by leveraging the information of gene function prediction models with domain adaptation (DA). IsoResolve treats gene- level and isoform-level features as source and target domain, respectively. It employs DA to project the two domains to a latent variable (LV) space in such a way that the LVs projected from the gene and isoform domain features are of approximately the same distribution, enabling that the gene domain information can be leveraged for predicting isoform functions.

# 2. Input data
Both gene- and isoform-level data are required as input for IsoResolve. The demo input data are provided in the folder 'data'. The subfolder 'goterm_cv' includes data for evulating the performance of IsoResolve with cross validation (CV). The subfolder 'goterm_traintest' includes training data for building models and test data for evaluating the performance of IsoResolve.

# 3. Implementation
IsoResove is implemented in Python. It is tested on both MacOS and Linux operating system. They are freely available for non-commercial use.

# 4. Usage
We provide two demo scripts to show how to run IsoResolve.

4.1. To test IsoResolve by cross validation, run the following command from command line:

python run_isoresolve_cv.py
This command will excecute cross validation on the provided data.
