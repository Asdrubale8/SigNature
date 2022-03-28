# SigNature
The goal of the following work is to present and analize the impact of different approaches to the task of handwritten signature forgery detection. There will be presented three models related to two kind of approaches: writer dependent (the model classify a user that already trained on) and writer independent (the model doesn’t train on new user’s instances), with advantages and disadvantages of the two approaches, also based on the number of signatures we have already available for new user.

## How to
This is how to use the python notebooks, further descriptions are contained in the notebooks:
  1) Open all the .ipynb in Google Colab
  2) Execute the DataPreparation.ipynb to create the integrated dataset (this dataset is already present in Datasets)
  3) Execute the CNN_identification_verification.ipynb to build the complete CNN system for identification and verification
  4) Execute the Basic_model.ipynb to build the basic model (It's important to execute this step before steps 5 and 6)
  5) Execute the Fine_tuning_model.ipynb to build the fine tuning model
  6) Execute the Tailored_model.ipynb to build the tailored model
  7) Execute the Siamese_model.ipynb to build the Siamese network model
  8) Execute the Graphs.ipynb to create graphs for the comparison of the models
