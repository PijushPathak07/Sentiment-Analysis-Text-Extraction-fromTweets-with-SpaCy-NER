# Sentiment Analysis Text Extraction from Tweets with spaCy NER

## Project Overview
This project investigates sentiment analysis on Twitter data using spaCy, a flexible Natural Language Processing (NLP) framework. Our goal is to create algorithms that can recognize and extract text segments from Tweets that convey sentiment. This entails using tagged Twitter data to train two spaCy Named Entity Recognition (NER) models: one for positive sentiment and one for negative sentiment. The trained models are then used to predict user emotions and extract pertinent sentences from new Tweets.

## Authors
- Pijush Pathak
- Linson Thomas Verghese
- Dr. G. Divya

## Institution
- Department of Data Science and Business Systems, SRM Institute of Science and Technology, Chennai, India

## Abstract
This project uses spaCy’s Named Entity Recognition (NER) to locate and extract sentiment-containing text fragments from tweets, aiming to go beyond traditional sentiment classification techniques. By identifying sentiment-infused text fragments, we can better comprehend the emotions surrounding particular issues or phrases, gaining insights into the opinions and motivations of Twitter users.

## Libraries and Algorithms
- **spaCy**: An open-source NLP library providing tools for tokenization, part-of-speech tagging, dependency parsing, and named entity recognition (NER).
- **NER (Named Entity Recognition)**: An NLP task focused on identifying and categorizing named entities within text data.

## Research Procedure
1. **Dataset Acquisition**: Acquired from Kaggle, containing text data with corresponding sentiment labels (positive, negative, or neutral).
2. **Preprocessing of Data**: Cleaning the dataset by removing null values, symbols, and irrelevant characters.
3. **Preparation of Models**: Constructing separate models for detecting positive, negative, and neutral sentiments using spaCy NER.
4. **Training the Models**: Training the models to recognize patterns related to positive and negative sentiment expressions.
5. **Identifying Sentiments**: Using trained models to predict sentiment and extract related text snippets from new data.

## Results and Discussion
The sentiment analysis models demonstrated impressive performance across various evaluation metrics, providing valuable insights into their effectiveness in discerning sentiment from text data. The models exhibited a substantial overlap between predicted and actual text spans for sentiment classification, as indicated by a Jaccard score of 0.61365.

## Conclusion
Using NLP and ML approaches, this work explores named entity recognition (NER) and sentiment analysis. The research highlights the effectiveness of NLP and ML in practical situations like social media monitoring and customer feedback analysis, offering future paths for enhancing model performance and tackling issues like noisy data and domain-specific variations.

## Publication
https://ijsret.com/wp-content/uploads/2024/05/IJSRET_V10_issue3_130.pdf

## How to Use
1. **Clone the repository**: `git clone https://github.com/your-username/your-repo-name.git`
2. **Install the required libraries**: `pip install -r requirements.txt`
3. **Run the preprocessing script**: `python preprocess.py`
4. **Train the models**: `python train_models.py`
5. **Predict sentiment on new data**: `python predict_sentiment.py`

## Contact
For any inquiries or feedback, please contact [pijushpathak@gmail.com](mailto:pijushpathak94@gmail.com).
