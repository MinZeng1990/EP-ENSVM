# EP-ENSVM
# Description
EP-ENSVM is a computational approach for essential protein prediction by using only sequence information. 

# Requirements
numpy==1.18.1

scikit-learn==0.23.1

imblearn==0.7.0

# Usage
In this GitHub project, we give a demo to show how EP-ENSVM works. 

In Raw data folder, we provide the raw protein sequences and their labels.

In Processed features folder, we provide the processed protein sequence features obtained by Pseudo Amino Acid Composition (PseAAC) tool. 

In predicted results by 8 centrality methods folder, we provide the results of 8 centrality methods. 

data_h.pkl and data_y.pkl are used to store the sampled positive and negative samples of human and yeast, respectively.

In our demo, we provide a python file (train_main.py) to train and evaluate the ensemble classifier. 

You can train the model with a very simple way by the command blow:

`python train_main.py --type h --threshold 0.5`


If you want to tune some hyper-parameters, you can change some values of hyper-parameters in train_main.py. 

The other details can see the paper and the codes.
 
# Contact
If any questions, please do not hesitate to contact me at:

Min Zeng   zengmin@csu.edu.cn  

Min Li     limin@mail.csu.edu.cn

