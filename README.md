# DILI_Bayesian_Model
This repository contains example code for Bayesian Neural Networks (BNN) and other ML approaches utilizing publicly available AstraZeneca's in-vitro assay data for predicting Drug Induced Liver Injury (DILI) risk.

## Objectives
* Step 1: AZ's in vitro assay data used for the development of the Bayesian Hapatic Safety model was downloaded.
* Step 2: The BNN model was re-developed and the performance of the BNN model was compared with the other Machine learning-based methods.
* Step 3: Important descriptors (based on Mutual Informative Score) were selected based on DILI classification abilities
* Step 4: A refined model using original features + top 20 descriptors was generated which shows improved performances.
* Step 5: A similar approach was used utilizing internal in vitro hepatic safety data + descriptors
* Step 6: The model was finally incorporated into the DILI de-risking strategy. It provides DILI prediction probability as well as the relative contribution of each assay. 

## Requirements
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

## Steps
> [!NOTE]
> ## The pipeline has been divided into multiple steps
> * **Step1:** Use **<span style="color:blue">BNN_Check.ipynb</span>** This script was used to develop a BNN model using AZ's in vitro assay data.
> * **Step2:** Use **<span style="color:blue">BNN_vs_otherML.ipynb</span>** This script was used to develop other ML models to compare the performance with BNN model 
> * **Step3:** Use **<span style="color:blue">MultiClass_ROC.ipynb and BinaryClass_ROC.ipynb</span>** scripts were used to compute ROC performance for multi-class (No-DILI; Medium-DILI; and Severe-DILI) and binary class (No-DILI vs DILI)
> * **Original internal assay data and plots has not been included here due to confidentially issues.**

## Contact: :raised_back_of_hand:
> [!IMPORTANT]
> For any questions please contact: :point_right: Ashok K. Sharma; ashoks773@gmail.com
