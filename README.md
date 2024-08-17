# DILI_Bayesian_Model
This repository contains example code for Bayesian Neural Networks (BNN) and other ML approaches utilizing publicly available AstraZeneca's in-vitro assay data for predicting Drug Induced Liver Injury (DILI) risk.

## Objectives :writing_hand:
* Step 1: AZ's in vitro assay data used for the development of the Bayesian Hapatic Safety model was downloaded.
* Step 2: The BNN model was re-developed and the performance of the BNN model was compared with the other Machine learning-based methods.
* Step 3: Important descriptors were selected based on DILI classification abilities
* Step 4: A refined model using original features + top 20 descriptors was generated which shows improved performances.
* Step 5: A similar approach was used utilizing internal in vitro hepatic safety data + descriptors
* Step 6: The model was finally incorporated into the DILI de-risking strategy. It provides DILI prediction probability as well as the relative contribution of each assay. 

## Requirements :crossed_fingers:
> [!TIP]
> Start working with Google Colab or Jupyter Notebook! 
> * First, install the following packages using pip3 or pip:
`numpy`
`pandas`
`sklearn`
`pymc3`
`theano.tensor`
`pickle`
`scipy`
`matplotlib`
`PIL`
`pyplot`
`rdkit`
`seaborn`
`scikit-learn`



