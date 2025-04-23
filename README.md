# Analyzing-ISIS-Twitter-Networks

## 📌Project Overview

This project analyzes a dataset of tweets to uncover insights into user engagement, trending topics, and sentiment patterns using data analytics and natural language processing (NLP). The analysis includes data cleaning, exploratory data analysis (EDA), frequency analysis, and visualization of key metrics such as follower counts, tweet frequencies, and dominant conversation themes. The project is implemented in a Jupyter Notebook, leveraging Python libraries for robust data processing and visualization.

## Key Objectives

User Engagement Analysis: Examine user activity through metrics like follower counts and tweet frequencies.

Topic Modeling: Identify trending topics and keywords driving conversations using NLP techniques.

Sentiment Insights: Analyze sentiment trends in tweets to understand emotional undertones.

Data Quality Assessment: Address missing values and duplicates to ensure reliable insights.

## 🚀Key Findings

User Engagement: Users averaged ~3,975 followers and ~4,761 tweets, with outliers reaching up to 34,692 followers and 33,091 tweets, indicating a highly active subset.

Trending Topics: A bar chart of the top 10 subjects highlighted key conversation drivers, supported by NLP-derived keyword clusters.

Sentiment Trends: NLP analysis revealed sentiment patterns, showing correlations between emotions and specific topics.

Data Gaps: Missing data in 2,682 user descriptions and 5,978 locations suggests incomplete profiles, impacting targeted analysis.

## 🔧 Tech Stack

Data Processing: Pandas for data cleaning and preprocessing

Visualization: Matplotlib, Seaborn for charts; WordCloud for keyword visualization

NLP: WordCloud for frequency analysis, with potential use of NLTK or spaCy for sentiment and keyword extraction

Environment: Jupyter Notebook for interactive analysis

## 📁Project Structure
```
├── data/
│   └── tweets.csv              # Raw tweet dataset
├── notebooks/
│   └── ISIS.ipynb             # Main Jupyter Notebook with analysis
├── README.md                  # Project documentation
└── requirements.txt           # Python dependencies
```

## 🛠️Installation

1.Clone the repository:
```
git clone https://github.com/your-username/social-media-tweet-analysis.git
cd social-media-tweet-analysis
```

2.Create a virtual environment and activate it:
```
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3.Install dependencies:
```
pip install -r requirements.txt
```
4.Launch Jupyter Notebook:
```
jupyter notebook
```
Open notebooks/ISIS.ipynb to explore the analysis.

## Usage

Data Cleaning: The notebook removes duplicates and handles missing values in the tweets.csv dataset.

EDA: Summary statistics and visualizations (e.g., follower distribution, tweet frequency) are generated.

NLP Analysis: WordCloud and frequency analysis identify key topics; sentiment analysis (if extended) provides emotional insights.

Visualizations: A bar chart displays the top 10 subjects, with additional plots for engagement metrics.

## Requirements

See requirements.txt for a full list of dependencies. Key libraries include:
```
pandas
matplotlib
seaborn
wordcloud
jupyter
```
Optional NLP libraries (if used): nltk, spacy

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

Inspired by social media analytics research and open-source data science communities.

Thanks to the developers of Pandas, Matplotlib, Seaborn, and WordCloud for their powerful tools.
