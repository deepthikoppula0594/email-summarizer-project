# Email Summarizer Project

## Overview
This project is a priority-based email summarization system developed using Natural Language Processing (NLP) techniques.  
It allows users to upload an email dataset, specify priority keywords, and automatically ranks emails based on relevance using the TF-IDF algorithm.  
The top emails are summarized using the TextRank method, and the summaries can be converted to speech in multiple languages.

---

## Tech Stack
- Python  
- Pandas  
- Scikit-learn (TF-IDF Vectorizer)  
- NLTK / Sumy (TextRank Summarizer)  
- gTTS (Google Text-to-Speech)  
- Googletrans (Language Translation)

---

## Features
- Upload CSV file containing email data.  
- Rank emails based on user-input keywords.  
- Summarize top-priority emails.  
- Convert summaries to speech in multiple languages.  
- Download generated audio files.

---

## How to Use
1. Open the notebook in Google Colab.  
2. Upload your email dataset (must include “Subject” and “Content” columns).  
3. Enter your priority keywords when prompted.  
4. View the ranked and summarized emails.  
5. Choose language for speech output and download if required.

---

For a detailed explanation, full code, and demo results, refer to the Colab notebook included in this repository.
