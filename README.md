😊 Emotion Recognition from Speech using Machine Learning
📌 Project Overview
This machine learning project focuses on recognizing human emotions from speech using audio feature extraction and supervised learning techniques. By analyzing voice patterns, we aim to classify emotions such as happy, sad, angry, neutral, and more.

Applications include virtual assistants, customer sentiment analysis, and mental health monitoring.

📂 Dataset: Toronto Emotional Speech Set (TESS)
🔍 Overview
The Toronto Emotional Speech Set (TESS) is a well-known dataset for speech-based emotion classification tasks.

Source: University of Toronto (Department of Psychology)

Format: .wav audio files

Speakers: 2 female actors (aged 26 and 64)

Utterances: “Say the word [target]”

Total Files: ~2,800

Languages: Canadian English

🎭 Emotions Included:
Neutral

Happy

Sad

Angry

Fear

Disgust

Surprise

📁 Dataset Structure:
Each emotion has its own folder.

File names indicate the emotion, speaker, and target word.

📥 Download:
TESS Dataset (University of Toronto)

🔧 Feature Engineering
We extracted key acoustic features from the .wav files using the librosa library:

MFCC (Mel-Frequency Cepstral Coefficients)

Chroma Frequencies

Spectral Contrast

Tonnetz

Zero-Crossing Rate

Root Mean Square Energy (RMSE)

These features form the basis of our emotion classification model.

🧠 Machine Learning Models
We trained several classifiers on the labeled audio data:

✅ Logistic Regression

✅ Random Forest

✅ Support Vector Machine (SVM)

✅ K-Nearest Neighbors (KNN)

✅ Multilayer Perceptron (MLP)

🎯 Target:
The model predicts one of the 7 emotional categories based on extracted audio features.

📈 Evaluation Metrics
Accuracy Score

Confusion Matrix

Classification Report (Precision, Recall, F1-score)

🤖 Results & Observations
Random Forest and SVM classifiers showed the highest accuracy.

MFCC features were particularly effective in distinguishing emotions.

Emotions like happy, sad, and neutral were most accurately predicted.

The dataset’s simplicity and clarity make it ideal for baseline modeling and experimentation.

🚀 Future Enhancements
Incorporate data augmentation (pitch shift, noise, time-stretching).

Use deep learning models (e.g., CNNs, LSTMs) for end-to-end audio learning.

Build a real-time emotion recognition app using Streamlit or Flask.

Experiment with multilingual speech or male voices for generalization.
