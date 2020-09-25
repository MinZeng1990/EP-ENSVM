# EP-ENSVM
# Description
EP-ENSVM is a computational approach for essential protein prediction by using only sequence information. 

# Requirements
tensorflow==1.3.0
numpy==1.11.2
scikit-learn==0.18
scipy==0.18.1 

# Input data
data_h.pkl 

# Implementation
IsoResove is implemented in Python. It is tested on both MacOS and Linux operating system. They are freely available for non-commercial use.

# Usage
You can train the model with a very simple way by the command blow:
python train_main.py --type h --threshold 0.5
