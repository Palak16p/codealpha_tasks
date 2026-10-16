🧩 Emotion Recognition from Speech Using CNN

1. Project Overview:
-> This project aims to recognize human emotions from speech audio using Machine Learning and Deep Learning techniques.

2. Dataset:
-> Dataset: RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)
-> Audio files: 1,440 speech recordings
-> Emotions: Neutral, Calm, Happy, Sad, Angry, Fearful, Disgust, and Surprised.

3. Technologies Used:
-> Python
-> NumPy 
-> Librosa
-> Matplotlib
-> Scikit-lear
-> TensorFlow / Keras
-> Jupyter Notebook

4. Methodology:
-> Load speech recordings from the RAVDESS dataset.
-> Extract emotion labels from audio filenames.
-> Extract MFCC (Mel-Frequency Cepstral Coefficients) features from audio.
-> Standardize feature shapes using padding.
-> Split the dataset into training and testing sets.
-> Standardize features using training-set statistics.
-> Train a Convolutional Neural Network (CNN).
-> Evaluate model performance on test data.

5. Model Evaluation:
-> The model is evaluated using:
-> Accuracy
-> Classification Report
-> Precision, Recall, and F1-Score
-> Confusion Matrix
-> The results are available in the Jupyter Notebook.

6. How to Run:
-> Clone or download this repository.
-> Create and activate a Python virtual environment.
-> Install the required libraries.
-> Download and extract the RAVDESS speech dataset.
-> Update the dataset path in the notebook.
-> Open emotion_recognition.ipynb in Jupyter Notebook or VS Code.
-> Run all cells.

7. Limitations:
-> The model's performance depends on the dataset and training process.
-> Evaluation uses a small held-out portion of the dataset.
-> The current random split may include recordings from the same actors in both training and testing sets, so performance on  completely unseen speakers has not been established.

8. Author:
-> Machine Learning Internship Project — Task 2

