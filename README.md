NLP Text Summarizer - SpaCy
An interactive Streamlit app for text summarization powered by SpaCy. Users can input text, adjust summary length, and generate concise summaries by identifying the most relevant sentences using word frequency analysis.

Features
Tokenization: Breaks input text into words and sentences.
Word Frequency Analysis: Scores sentences based on the frequency of important words.
Adjustable Summary Length: Allows users to select the percentage of text to retain in the summary.
Custom Background: Personalize the app with a custom background image.
How It Works
Input Text: Enter text into the input box.
Adjust Length: Use the slider to set the desired summary length.
Generate Summary: The app:
Tokenizes the text.
Calculates word frequencies.
Scores sentences based on relevance.
Outputs a concise summary.
Installation
Follow these steps to set up the app locally:

Clone the repository:

bash
Copy code
git clone https://github.com/tanishqbololu/NLP-Text-Summarizer-spaCy.git  
Navigate to the project directory:

bash
Copy code
cd NLP-Text-Summarizer-Spacy  
Install dependencies:

bash
Copy code
pip install streamlit spacy nltk  
Download the SpaCy model:

bash
Copy code
python -m spacy download en_core_web_md  
Run the app:

bash
Copy code
streamlit run app.py  
Dependencies
Streamlit: For building the interactive web app.
SpaCy: For text processing and NLP tasks.
NLTK: For handling stopwords and other NLP utilities.
Base64: (Part of Python Standard Library) For encoding background images.
Usage
Enter text: Paste or type text into the input box.
Adjust summary length: Use the slider to control the percentage of the text to summarize.
View results: The summary is displayed below the input box.
Author
Mandeep Kaur
Connect on LinkedIn 🚀


