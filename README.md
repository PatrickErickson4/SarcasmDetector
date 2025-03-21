# SarcasmDetection
This is a collaborative effort with Parth Gosar, Derek Guidorizzi, Sahil Pardasani.
The following packages need to be installed, to run the code: pandas, nltk, numpy, tensorflow, optuna, scikit-learn, gensim. This is the same repository under @squiddycodes, but duplicated due to the logistics of class enrollments.

You can run "pip install -r requirements.txt" to install them all in one command.

Make sure you have all files in the same folder, to be able to run the model.

You will need to download GloVe's "glove.6B.100d.txt" file before running the code. You can find this file at [https://www.kaggle.com/datasets/rtatman/glove-global-vectors-for-word-representation]

To run the code, you will need to run "main.py"

We used optuna to find our best parameters, but if you want to train the model yourself and find your own parameters, edit the model.py file, changing the cnn filters in the objective function.

final_model.h5 is our highest model evaluation achieved, around 92% accuracy. To use this model, uncomment the associated code in main.py. Understand that this model may be overfitted.
