# Experimental-Analysis-of-Speech-Emotion-and-Gender-Recognition

The file below has not been updated yet because it is awaiting publication, after which others can use the code and further develop it.
The file below is a research work related to Speech Emotion Recognition, consisting of the following:

### 1. Preprocessed Data

- **clean_data_only_emotion.ipynb**: A notebook file that shows the steps of cleaning audio data from all four datasets, RAVDESS, CREMA-D, SAVEE, and TESS, for predicting only emotions. The data is arranged in a table format with metadata (emotion, sex_type, name_file) ready to be used in the model-building process.

- **clean_data_gender_emotion.ipynb**: A notebook file that outlines the steps for cleaning audio data from both datasets, RAVDESS and CREMA-D, to predict emotions and gender as a single label for use in model training scenarios where emotions and gender are predicted simultaneously. For use with RAVDESS and CREMA-D datasets only

---

### 2. Model Training and Evaluation Files

- **ML_DL_only_emotion.ipynb**: It consists of 17 training models (Machine Learning and Deep Learning) for emotion-specific prediction, comparing the accuracy values ​​to identify the best model in each dataset.

- **ML_DL_gender_emotion.ipynb**: It consists of 17 training models for emotion and gender prediction, showing the results of each model along with the accuracy values for each emotion and gender class.

- **EL_only_emotion.ipynb**: Convolutional Neural Network training combined with Ensemble Learning for emotion-specific prediction, separating the evaluation of Soft Voting and Hard Voting, and analyzing the accuracy of each emotion in detail

- **EL_gender_emotion.ipynb**: CNN training combined with Ensemble Learning for emotion and gender prediction together By using Voting to judge the results and measure the performance of the model in every class in detail

---

### 3. Image files and tables for analysis

- **diagram.png**: Diagram showing the architecture of the Convolutional Neural Network model used in the research, with an overview of how to combine it with Ensemble Learning techniques via Soft Voting and Hard Voting.

- **table1.png**: Comparative table of the accuracy of 19 models in classifying emotions from sounds for RAVDESS dataset.

- **table2.png**: Comparative table of the accuracy of 19 models in classifying emotions from sounds for CREMA-D dataset.

- **table3.png**: Comparative table of the accuracy of 19 models in classifying emotions from sounds for SAVEE dataset.

- **table4.png**: Comparative table of the accuracy of 19 models in classifying emotions from sounds for TESS dataset.

- **table5.png**: Comparative table of the accuracy of 19 models in classifying emotions with gender from the RAVDESS and CREMA-D datasets, showing the results separated by emotion and gender in detail

- **table6.png**: A comparative table of the accuracy between the models developed in this research and previous research to show the prominence and technical development of the proposed CNN + Ensemble Learning model