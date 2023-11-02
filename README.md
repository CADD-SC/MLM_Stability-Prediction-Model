# MLM-Stability-Prediction-Model
Machine Learning-based prediction model for Mouse Liver Microsomal (MLM) stability prediction.

**Introduction:**

Welcome to our repository, here we provide machine learning model to efficiently predict the Mouse Liver Microsomal (MLM) stability of target drug compounds in early stage of drug discovery process. 

**Dependencies:**

  - python=3.7
  - rdkit
  - chembl_webresource_client
  - seaborn
  - scikit-learn
  - pickle5
  - jupyter
  - molvs
  - python-graphviz
  - pydotplus


**Execution:**

Use Jupyter notebook to execute the code, download all the input files and MLM_stability.pkl from the tab “Tag”.

Prepare your input file containing SMILES in .csv format and name the column as “SMILES”.

Make sure the paths of model, MLM_stability.pkl file and input files before executing the code file named as MLM_stability_Prediction_model.ipynb.

**Output:**

Our model generates output in binary value (1 or 0), where 1 indicates compound to be stable, while 0 indicates unstable.

**Note:**

To access and download the prediction model file in .pkl format and input feature file, please refer to the tab "Tag --> v2.3.4".

**Authors:**

Maninder Singh, Bilal Shaker, Jin Hee Lee, Sunghwan Choi, Sanghee Yoon, Shaherin Basith, Minghua Cui, Sunil Ahn, Haerim Han, Min SunYeom* and Sun Choi*
