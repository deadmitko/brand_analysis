# Twitter Data Analysis and Visualization

This project provides a comprehensive analysis of Twitter data, focusing on brand engagement, sentiment analysis, and topic modeling. It leverages Python libraries such as pandas, numpy, plotly, nltk, scikit-learn, and gensim to process data, extract insights, and create interactive visualizations.

## Project Structure

- **README.md:** This file, providing an overview of the project.
- **[Notebook].ipynb:** A Jupyter Notebook with the main analysis code.
- **cleaned_twitter_data.csv:** A sample of the csv file.

## Overview of Analysis

The analysis pipeline consists of the following steps:

1.  **Data Loading and Preprocessing:**
    *   Loads data from a CSV file containing Twitter data.
    *   Converts 'created_at_tweet' column to datetime.
    *   Cleans text by removing mentions, URLs, hashtags, and converting to lowercase.
    *   Tokenizes the cleaned text.
2.  **Data Exploration:**
    *   Visualizes follower counts, post counts, and like counts for different brands.
    *   Generates word clouds for hashtags and common words used in tweets.
3.  **Sentiment Analysis:**
    *   Calculates polarity and subjectivity scores for each tweet using TextBlob.
    *   Categorizes sentiment as positive, negative, or neutral.
    *   Visualizes sentiment distribution over time and sentiment categories.
4.  **Engagement Analysis:**
    *   Calculates total engagement based on retweets, favorites, replies, and quotes.
    *   Computes engagement rate for each tweet.
    *   Visualizes relationship between engagement and sentiment.
5.  **Temporal Analysis:**
    *   Extracts date, hour, and day of the week information.
    *   Analyzes and visualizes the number of tweets and engagement rate over time, by hour, and by day.
6.  **Topic Modeling:**
    *   Performs topic modeling using Latent Dirichlet Allocation (LDA) to uncover themes within the data.
    *   Visualizes the top words for each topic.
7.  **Semantic Analysis:**
    *   Applies Word2Vec to generate word embeddings.
    *   Computes similarities between words.
    *   Creates a heatmap and network graph of word similarities and a bar chart for the most similar words.
8. **Brand Comparison Visualization:**
    * Plots a visualization comparing different brands based on sentiment, engagement, polarity, subjectivity, and number of tweets.

## Libraries Used

-   **pandas:** Data manipulation and analysis.
-   **numpy:** Numerical computing.
-   **plotly:** Interactive plotting.
-   **nltk:** Natural language processing tasks (tokenization, stop words).
-   **textblob:** Sentiment analysis.
-   **scikit-learn:** Machine learning tasks (TF-IDF, LDA).
-   **gensim:** Word2Vec model for semantic analysis.
-   **wordcloud:** Word cloud visualization.
-   **matplotlib:** Basic plot generation.
-   **seaborn:** Statistical data visualization.
-   **string:** String manipulation.
-   **re:** Regular expressions.
-   **collections.Counter:** Counting elements.

## Getting Started

1.  **Clone the Repository:**

    ```bash
    git clone [repository_url]
    cd [repository_name]
    ```
2.  **Install Dependencies:**

    ```bash
    pip install pandas numpy plotly nltk textblob scikit-learn gensim wordcloud matplotlib seaborn
    ```
3.  **Download Required NLTK Data:**
    Run the notebook with the line `nltk.download(['punkt', 'stopwords', 'wordnet', 'averaged_perceptron_tagger'])` to download data required by NLTK library.

4.  **Run the Notebook:**
    * Open the Jupyter Notebook and execute the cells.
    ```bash
        jupyter notebook [notebook_name].ipynb
    ```
5.  **Explore the Visualizations:**
    * Interact with the Plotly visualizations generated.
    * Observe the insights drawn from the analyses.

## Note

*   Ensure that the `cleaned_twitter_data.csv` file is placed in the same directory as the notebook.

*   This project provides a starting point and can be extended further with additional features, analyses, and data sources.
*   The project leverages the power of python's library to create interactive and in-depth analysis of twitter data.
content_copy
download
Use code with caution.
Markdown