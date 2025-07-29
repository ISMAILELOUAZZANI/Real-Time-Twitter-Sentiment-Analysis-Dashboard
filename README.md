# Real-Time Twitter Sentiment Analysis Dashboard

This project streams tweets in real-time, analyzes their sentiment using a machine learning model, and displays the results in a live dashboard.

## Project Structure

- `data/` — data used for model training and references
- `notebooks/` — Jupyter notebooks for model development
- `src/` — streaming, analysis, and dashboard scripts
- `results/` — output examples and screenshots

## How to Run

1. Install dependencies:
    ```
    pip install -r requirements.txt
    ```
2. Set your Twitter API keys as environment variables.
3. Train the sentiment model using the notebook.
4. Start the tweet stream and dashboard:
    ```
    python src/stream_tweets.py
    python src/dashboard.py
    ```

## Model

A logistic regression model classifies tweets as positive, negative, or neutral.

## Results

See `results/sample_output.png` for a dashboard example.