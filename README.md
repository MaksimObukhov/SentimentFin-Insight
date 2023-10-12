# SentimentFin Analyzer

SentimentFin Analyzer is a versatile project designed for sentiment analysis on financial news data, focusing on the labeled dataset provided by The Financial Phrasebank at the Hugging Face webpage. The dataset comprises 3453 sentences from English language financial news, categorized by sentiment.

## Key Features

1. **Sentiment Classification:**
   - Create a powerful sentiment classifier to analyze and categorize financial news sentences based on their sentiment.

2. **Additional Tasks:**
   - Choose from one of the following tasks to complement sentiment analysis:
      - Clustering: Perform clustering with visualization and description of important clusters.
      - Topic Modelling: Extract and visualize important topics within the financial news data.
      - Similarity Analysis: Investigate mutual similarity among items (reviews) with graph visualization.

3. **Collocation Analysis:**
   - Conduct collocation analysis on "highly ranked words" using metrics like TF-IDF, providing valuable insights into significant terms.

## How to Use

1. **Clone the Repository:**
   - Clone this repository to your local machine.

```bash
git clone https://github.com/yourusername/sentimentfin-analyzer.git
cd sentimentfin-analyzer
```

2. **Open and Run the Jupyter Notebook:**
   - Open the Jupyter Notebook provided in the repository.

```bash
jupyter notebook SentimentFin_Analysis.ipynb
```

3. **Execute Each Cell:**
   - Execute each cell in the notebook sequentially to perform the following tasks:
      - Sentiment Classification
      - Additional Tasks (Clustering, Topic Modelling, Similarity Analysis)
      - Collocation Analysis

4. **Follow the Instructions:**
   - Follow the instructions within the notebook for each task to train models, analyze data, and visualize results.

## Dependencies

- Python 3.x
- Libraries: nltk, scikit-learn, matplotlib, pandas, gensim
