# SocioSentiment

SocioSentiment – Multilingual Sentiment & Emotion Analysis
SocioSentiment is a multilingual sentiment and emotion analysis system designed to analyze public opinions on social issues such as climate change, healthcare, education, and politics. The system processes text input in English and Hindi, detects sentiment polarity, identifies underlying emotions, and provides confidence scores and explainable results through keyword highlighting. 

Live App
Try the app here: https://sociosentiment-dnnuo4yyrqc3z4ptxtthnd.streamlit.app/

The project is deployed as an interactive Streamlit web application, allowing users to analyze text in real time.

Project Overview
In today's digital world, large volumes of opinions are shared through social media, blogs, and online forums. Understanding these opinions is essential for:
Policymakers to understand public reaction
NGOs to measure campaign effectiveness
Researchers to analyze social trends
Organizations to monitor public perception 
However, many existing sentiment analysis tools:
Work only in English
Perform only binary classification (Positive/Negative)
Do not detect emotions
Lack transparency in predictions 
SocioSentiment addresses these limitations by providing a multilingual, multi-level, and explainable sentiment analysis system.

Features
Multilingual Text Analysis
Supports English and Hindi text inputs.
Sentiment Classification
Classifies text into:
Positive
Negative
Neutral

Emotion Detection
Identifies emotions such as:
Happy
Sad
Angry
Fear
Surprise

Confidence Score
Displays probability values that indicate how confident the model is about its prediction.

Explainable AI
Highlights important keywords that influenced the prediction.

Interactive Web Interface
Built with Streamlit to provide real-time sentiment analysis through a simple user interface.

System Architecture
The system follows an NLP pipeline:
 Input Layer
User enters text through Streamlit interface.
 Text Preprocessing
Remove URLs and special characters
Lowercasing
Tokenization
Stopword removal
Lemmatization
 Feature Extraction
TF-IDF
Word Embeddings
Contextual embeddings (BERT-based concepts)
 Model Layer
Sentiment Classification
Emotion Detection
 Confidence Scoring
Calculates prediction probabilities.
 Explainability Layer
Highlights keywords influencing prediction.
 Output Visualization
Sentiment result
Emotion result
Confidence score

Technologies Used
Programming Language
Python
Machine Learning / NLP Libraries
NumPy
Pandas
Scikit-learn
NLTK
Visualization
Matplotlib
Web Framework
Streamlit
Development Tools
Jupyter Notebook / VS Code

Installation
Clone the repository:
git clone https://github.com/yourusername/SocioSentiment.git
cd SocioSentiment
Install required libraries:
pip install -r requirements.txt
Run the Streamlit app:
streamlit run app.py

Example Usage
Open the Streamlit app in your browser.
Enter a sentence such as:
The government has done a great job improving healthcare.
The system will display:
Sentiment: Positive
Emotion: Happy
Confidence Score
Highlighted keywords

Applications
SocioSentiment can be used for:
Public opinion analysis
Social media monitoring
Policy feedback analysis
NGO campaign evaluation
Market and customer sentiment analysis
Academic research

Limitations
Currently supports only English and Hindi
Struggles with sarcasm and irony
Accuracy depends on dataset quality
Mixed-language sentences may reduce accuracy 

Future Improvements
Add more regional languages (Marathi, Tamil, Bengali, Malayalam)
Integrate real-time social media APIs
Implement advanced transformer models (mBERT / XLM-R)
Detect sarcasm and irony
Build a dashboard for sentiment trends and analytics 

Contributors
Ishika Belel
Raina Mitra
Gauri Nair
Sahas Shinde 

Acknowledgement
We would like to thank Lokesh Chakranarayan for his guidance and support throughout the development of this project. 
