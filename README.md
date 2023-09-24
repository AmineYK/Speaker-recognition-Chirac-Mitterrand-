# Speaker-recognition-Chirac-Mitterrand-

This NLP project aims to apply natural language processing techniques to recognize speakers (Chirac or Mitterrand) by processing their speeches. The text data undergoes various transformations and feature extraction methods before being used to train machine learning models, with a focus on evaluating their performance using appropriate metrics.. 
The main steps involved are: 
- Text Parametric Transformation (Pre-processing) Text to lowercase or not Punctuation removal Transformation of all uppercase words into specific markers Digit removal or retention Keeping only a portion of the text ,  Stemming ...
- Vocabulary Extraction (BoW - Bag of Words) Variations of BoW TF-IDF Vocabulary size reduction (min_df, max_df, max_features) Binary BoW Bi-grams, tri-grams
- Machine Learning Models Evaluation Metrics Accuracy ROC Curve, AUC, F1-score Class imbalance handling: Upsampling Undersampling Cost function modification.
