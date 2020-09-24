# EP-ENSVM
# 1. Description
EP-ENSVM is a computational approach for isoform function prediction by leveraging the information of gene function prediction models with domain adaptation (DA). IsoResolve treats gene- level and isoform-level features as source and target domain, respectively. It employs DA to project the two domains to a latent variable (LV) space in such a way that the LVs projected from the gene and isoform domain features are of approximately the same distribution, enabling that the gene domain information can be leveraged for predicting isoform functions.

# 2. Input data
data_h.pkl 

# 3. Implementation
IsoResove is implemented in Python. It is tested on both MacOS and Linux operating system. They are freely available for non-commercial use.

# 4. Usage
You can train the model with a very simple way by the command blow:
python train_main.py --type h --threshold 0.5
