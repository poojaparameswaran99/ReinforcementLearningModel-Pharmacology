Here are some files that need to be uploaded to the google drive environment for the notebook to work.

pre_trained_RNN.pkl is a 10000 epoch trained generator trained on the large chembl dataset from ReLeaSE (also provided here in ReLeaSE data files).

tox21_final is the final result of some assumptions we made about tox21, we assumed if a molecule has no value for an assay then it is toxic in that assay and we added an all column that says it is toxic if toxic in any assay