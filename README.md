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

## Future Work
- Refining and optimizing machine learning models
- Expanding support to multiple languages
- Implementing real-time processing
- Optimizing scalability and performance
- Incorporating mechanisms for continuous learning and adaptation

## References
1. Derczynski, L., Maynard, D., Rizzo, G., et al. (2014). Analysis of Named Entity Recognition and Linking for Tweets.
2. Sahayak, V., Shete, V., & Patha, A. (2017). Sentiment Analysis on Twitter Data.
3. Giachanou, A., & Crestani, F. (2016). A Survey of Twitter Sentiment Analysis Methods.
4. Aliza Sarlan, Chayanit Nadam, Shuib Basri,”TwitterSentiment Analy- sis”,26 March 2015
5. M S Neethu, R Rajasree,”Sentiment analysis in twitter using machine learning techniques.”,30 January 2014
6. Shelar, H., Kaur, G., Heda, N., Agrawal, P.(2020). Named Entity Recognition Approaches and Their Comparison forCustom NER Model. Science Technology Libraries, 39(3), 324–337.
7. Wankhade, M., Rao, A.C.S. Kulkarni, C. A survey on sentiment analysis methods, applications, and challenges. Artif Intell Rev 55, 5731–5780 (2022). https://doi.org/10.1007/s10462-022-10144-1
8. Doaa Mohey El-Din Mohamed Hussein,A survey on sentiment analysis challenges,Journal of King Saud University Engineering Sciences,Volume 30, Issue 4,2018,Pages 330-338,ISSN 1018-3639, https://doi.org/10.1016/j.jksues.2016.04.002.(https://www
.sciencedirect.com/science/article/pii/S1018363916300071)
9. M.D. Devika, C. Sunitha, Amal Ganesh,Sentiment Analysis: A Comparative Study on Different Approaches,Procedia Computer Science, Volume 87,2016,Pages 44-49,ISSN 1877-0509, https://doi.org/10.1016/j.procs.2016.05.124.(https://www. sciencedirect.com/science/article/pii/S187705091630463X)
10. David Zimbra, Ahmed Abbasi, Daniel Zeng, and Hsinchun Chen. 2018. The State-of-the-Art in Twitter Sentiment Analysis: A Review and Benchmark Evaluation. ACM Trans. Manage. Inf. Syst. 9, 2, Article 5 (June 2018), 29 pages. https://doi.org/10.1145/3185045

## How to Use
1. **Clone the repository**: `git clone https://github.com/your-username/your-repo-name.git`
2. **Install the required libraries**: `pip install -r requirements.txt`
3. **Run the preprocessing script**: `python preprocess.py`
4. **Train the models**: `python train_models.py`
5. **Predict sentiment on new data**: `python predict_sentiment.py`

## Contact
For any inquiries or feedback, please contact [your-pijushpathak@gmail.com](mailto:pijushpathak94@gmail.com).
