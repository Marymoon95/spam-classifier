# Message Classification
Classifying SMS messages as *spam* or *ham* using multiple supervised learning algorithms.

The following machine learning algorithms are used for classification:
- Random Forest
- Support Vector Classification (SVC)
- Naive Bayes Classifier
- Long short-term memory (LSTM)


## Data

The data was retrieved from the link https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection and was saved in the original format and with the original names in a directory that is then used in the code.

The dataset contains 5572 text messages which are labelled as *ham* or *spam*. The messages are not cleaned, and the dataset is not balanced because it contains 4825 *ham* messages and 747 *spam* messages.

## Execution
The project has a jupyter notebook spam-classifier.ipynb which is used for the implementation of this project. 

## Requirements: 
- Python3
- Jupyter Notebook
- WordNet lexical database
- Python libraries listed in the notebook
