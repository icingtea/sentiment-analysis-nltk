VADER (Valence Aware Dictionary and sEntiment Reasoner) scores a piece of text on the emotion is carries (that is, positive, negative, and neutral). VADER assigns a score between -1 (most negative) and +1 (most positive).

This notebook runs sentiment analysis using VADER on a dataset of IMDB reviews. This notebook runs sentiment analysis using VADER on a dataset of IMDB reviews. An optimal threshold is evaluated to turn compound sentiment score into a binary result (1 for positive, 0 for negative).

Dataset can be found here: https://www.kaggle.com/datasets/columbine/imdb-dataset-sentiment-analysis-in-csv-format/data

Regarding preprocessing: VADER accounts for punctutation, capitalization in calculating sentiment scores. It also deals with stopwords on its own, so the preprocessing in this notebook only includes basic lemmatization.