# Search Engine On Amazon Product Dataset Project

## Code Explanation

### Libraries
- Import necessary libraries: pandas, numpy, nltk, SnowballStemmer, TfidfVectorizer, cosine_similarity, and streamlit.

### Dataset
- Load "amazon_product_dataset.csv" using pandas.
- Drop the 'id' column.

### Tokenization and Stemming
- Define a tokenizer and stemmer.
- Create a function to tokenize and stem text.

### Stemmed Tokens
- Apply tokenization and stemming to 'Title' and 'Description' columns.
- Save stemmed tokens in 'stemmed_tokens' column.

### TF-IDF Vectorizer and Cosine Similarity
- Define TF-IDF vectorizer.
- Create a function to calculate cosine similarity.

### Search Function
- Define a function to search products based on query similarity.
- Return top 10 relevant results.

## Streamlit App
- Create a Streamlit app titled "Amazon Product Search".
- Provide a text input for the product name.
- Implement a "Search" button to execute the search function.
- Display top 10 relevant products.

## Report

### Project Description
- Build a search engine for Amazon products using natural language processing.

### Dataset
- Utilize the "Amazon Product Dataset" from Kaggle.

### Implementation
- Load dataset, preprocess text, calculate similarity, and create a user-friendly interface.

### Conclusion
- Develop a functional search engine for Amazon products using NLP techniques.