# Article-Summarizer

This repository contains code for an article summarizer based on the T5 transformer model. The model is trained on a dataset of articles and their summaries and can generate a summary for any given article. The dataset is provided in the Dataset folder of the repository. 

# Requirements
To use the code in this repository, you'll need to have Python 3 installed, along with the following packages:

* transformers

* datasets

* sentecepiece

* scikit-learn

You can install these pacakges by running:

` pip install transformers `

` pip install datasets `

` pip install sentencepiece `

` pip install scikit-learn `

# Training the Model

To train the model and run the Summarizer.py script , use Google Colab and use GPU hardware accelerator from Runtime options as the code for model uses GPU provided by google colab and may not run on local PC if it doesns't have CUDA compatible GPU. This will train the model on the dataset provided in the Dataset folder and save the trained model to a file called model.pth. You can modify the training parameters in the script to suit your needs




