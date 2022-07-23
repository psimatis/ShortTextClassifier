# ShortTextClassifier
A short text classifier using NLP and Machine Learning

This Jupyter Notebook trains a neural network (PyTorch) and uses a bit of NLP (SciPy) to classify a collection of short texts (e.g., tweets, news headlines).

**Input**: 
1. Training data in tabular form (e.g., Excel file) with two columns: Text, Class
2. The list of classes the user wants (e.g., economy, lifestyle, war).
3. Optional: Separate test dataset without tags.

**Output**: A Pandas DataFrame with the texts and their classes.

**Note**: Count Vectorizer achieves greater accuracy than TF-IDF.
