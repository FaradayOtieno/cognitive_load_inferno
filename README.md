## Cognitive Load Analysis of *Dante's Inferno*

This project uses **Natural Language Processing (NLP)** and **text complexity metrics** to quantify cognitive load in the literary text *Dante's Inferno*.

The analysis is performed canto by canto, and results are saved for further visualization or reporting.

## Features

- Canto-by-canto breakdown
- Text complexity metrics:
  - Flesch Reading Ease
  - Flesch-Kincaid Grade Level
  - SMOG Index
  - Difficult Words Count
  - Average Sentence Length
  - Lexical Diversity
- Sentiment analysis (TextBlob):
  - Polarity
  - Subjectivity
- Emotion frequency (mini NRC lexicon):
  - Fear, Joy, Anger, Sadness, Disgust, Surprise, Trust, Anticipation
- Word cloud visualization

---

## How to Run

From your terminal:

cd cognitive_load_inferno
pip install -r requirements.txt
python scripts/analyze_complexity.py
