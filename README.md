README

Stride Prediction for Exoskeleton Control

Jennifer Dawkins and Brian Do

MIT 18.337 Final Project, Fall 2018


Folders
- CSV data is the input data used in the models.
- Misc folder has old or unused notebooks
- UnprocessedData folder has raw data files
- Saved Vars And Models folder has varibles/models saved for the presentation

Notebooks
- basicConvNet performs a CNN over the data as described in the presentation
- basicLSTM_julia_wBestBC performs an LSTM over the most correlated feature (of 6) from a PCA of the input data
- basicLSTM_Julia_wPCA-Custom performs an LSTM over the first principle component of the data
- seq2seqLSTM performs sequence to sequence prediction as described in the presentation
- simple_models has processing of data to obtain maxima and clusters, and also performs regression to predict PF force
- hs_pf_visualization is in Python and used to produce KDE plots of HS and PF force

Presentation Notebook
- Presentation Notebook performs demos for the presentation. It uses data and variables in SavedVarsAndModels.

Presentation: available at https://docs.google.com/presentation/d/1yPo7DWC7wkqk6tZIedINC4eAI0z7oDcDgMW3wrxiFlM/edit?usp=sharing

How to run code:
- Julia 1.0.1
- All packages used are listed at the beginning of each notebook
- Each notebook can be run on its own
