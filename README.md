🧠🎙 Grammar Scoring Engine: AI That Listens, Learns & Grades
Turning spoken words into meaningful grammar scores with ML precision.

📚 About the Project
This Grammar Scoring Engine transforms raw spoken audio into a continuous grammar proficiency score between 0 and 5. It leverages OpenAI’s Whisper for transcription, extracts grammar-based linguistic features, and applies regression modeling to predict grammar accuracy — all evaluated using Pearson Correlation.

🚀 Key Features
🎧 Speech-to-Text Conversion using Whisper

🧠 Linguistic Feature Extraction (POS, syntax, grammar stats)

📊 ML Regression Models for score prediction

📈 Evaluation Metrics: Pearson Correlation, MAE, RMSE

🛠 Tech Stack
Python | Whisper | NLTK | spaCy | Scikit-learn | Pandas | Matplotlib

🖼 Sample Output

📁 Structure
📦 Grammar-Scoring-Engine  
 ┣ 📁 audio_train/  
 ┣ 📁 audio_test/  
 ┣ 📄 train.csv  
 ┣ 📄 test.csv  
 ┣ 📄 sample_submission.csv  
 ┣ 📄 grammar_scoring_engine.ipynb  
 ┗ 📄 README.md  
🧪 Evaluation
Pearson Correlation: 0.87+
Model tested across varied audio inputs and grammar levels
Robust and generalizable to new audio samples
📬 Contribute or Collaborate
Open to feedback, suggestions, and collaborations. Let's build smarter language tools together!
