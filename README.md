# Sentiment-Analysis-of-Real-time-Flipkart-Product-Reviews
Real-time sentiment analysis of Flipkart product reviews using Python and NLP. The project scrapes live reviews, cleans and preprocesses text, classifies sentiments as positive, negative, or neutral, and visualizes insights with WordClouds and charts for quick understanding of customer feedback.

## Features
- Scrapes real-time product reviews from Flipkart
- Text preprocessing (removes stopwords, punctuation, lemmatization)
- Sentiment classification: Positive, Negative, Neutral
- Visualizations using WordClouds and matplotlib/seaborn plots
- Easy-to-read summary of customer feedback

## Installation
1. Clone the repository: https://github.com/keerthipriy/Sentiment-Analysis-of-Real-time-Flipkart-Product-Reviews.git
2. Navigate to the project folder: ## cd Sentiment-Analysis-of-Real-time-Flipkart-Product-Reviews
3. Install required Python packages: ## pip install -r requirements.txt
   
## Usage
1. Open the Jupyter Notebook: jupyter notebook
2. Run the notebook cells sequentially:
Scrape product reviews
Preprocess text
Perform sentiment analysis
Visualize results
## NLTK Setup
Run these commands once to download required NLTK data:
import nltk
nltk.download('stopwords')
nltk.download('wordnet')
nltk.download('omw-1.4')

## Example Output
WordClouds showing frequent words in reviews
Bar charts showing counts of positive, negative, and neutral sentiments

## Requirements
All required packages are in requirements.txt:
pandas
numpy
matplotlib
seaborn
wordcloud
nltk
requests
beautifulsoup4

## License
This project is licensed under the MIT License.

## Author
Keerthi Priya
