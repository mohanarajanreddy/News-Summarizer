# News Summarizer

This project implements a news summarization tool using both extractive and abstractive summarization techniques. It processes news articles from the CNN/Daily Mail dataset and generates concise summaries.

## Prerequisites
Before running this project, you need to download the CNN Stories dataset. You can find instructions for downloading the dataset.[here]https://huggingface.co/datasets/ccdv/cnn_dailymail/blob/main/cnn_stories.tgz


## Installation

1. Clone this repository:
   ```
   git clone https://github.com/mohanarajanreddy/mreddy.git
   cd mreddy
   ```

2. Install the required Python packages:
   ```
   pip install spacy scikit-learn transformers rouge_score
   ```

3. Download the spaCy English model:
   ```
   python -m spacy download en_core_web_sm
   ```

## Usage

The main script is `newssummarizer.py`. It contains several functions for loading, processing, and summarizing news articles.

To use the summarizer:

1. Ensure your CNN Stories dataset is in the correct directory.
2. Update the `filename` variable in the script to point to your desired news story file.
3. Run the script:
   ```
   python newssummarizer.py
   ```

## Features

- Load and preprocess news articles from the CNN Stories dataset
- Implement extractive summarization using TF-IDF
- Implement abstractive summarization using the BART model
- Evaluate summaries using ROUGE scores

## File Structure

- `newssummarizer.py`: Main script containing all functions and logic
- `README.md`: This file

## Dependencies

- spaCy
- scikit-learn
- transformers
- rouge_score

Project Link: (((https://github.com/mohanarajanreddy/mreddy)))
