# Smart Product Advisor – ML, DL, and LLM for Amazon Reviews

A complete product recommendation and Q&A system built on 500,000+ Amazon reviews. The project compares 4 machine learning models, 4 deep learning architectures, semantic search, and a Groq LLM to summarize reviews, extract pros and cons, and answer user questions.

## What it does

- Preprocesses raw Amazon reviews (cleaning, lemmatization, negation handling)
- Trains 4 ML classifiers: Logistic Regression, SVM, Random Forest, XGBoost
- Trains 4 DL models: LSTM, GRU, CNN, BiLSTM
- Uses Sentence Transformers for semantic similarity retrieval
- Uses Groq (Llama 3.3 70B) for:
  - Summarizing reviews
  - Extracting pros and cons
  - Answering product-specific questions
- Provides a Gradio interface for interaction

## Technologies

- Python
- Scikit-learn (ML models)
- TensorFlow / Keras (DL models)
- Sentence Transformers (embeddings)
- Groq API (LLaMA 3.3)
- Gradio (UI)

## How to Run

1. Clone the repository
2. Install requirements: pip install -r requirements.txt
3. Set your Groq API key as an environment variable
4. Run the notebook in Google Colab or Jupyter
5. Upload the Reviews.csv dataset (Amazon product reviews)

