# FakeNewsDetection

AI-Driven Fake News Detection via Paraphrasing and Text Similarity Analysis.

## Overview

The **FakeNewsDetection** project leverages advanced AI models to evaluate whether user-provided text resembles real news headlines. By combining real-time news fetching, text preprocessing, AI-powered paraphrasing, and semantic similarity analysis, this tool helps identify potential fake news.

## Features

- **Real-Time News Fetching:** Retrieves the latest news headlines from NewsAPI based on a specified keyword.
- **Text Preprocessing:** Cleans and standardizes text to ensure accurate comparison.
- **AI-Powered Paraphrasing:** Uses the `facebook/opt-350m` model to generate paraphrased versions of user input.
- **Similarity Analysis:** Measures similarity between paraphrased user input and news headlines using the `all-MiniLM-L6-v2` model from Sentence Transformers.
- **Fake News Detection:** Determines if user input is similar to any fetched news headlines based on a similarity threshold.

## Installation

Ensure you have Python 3.7+ installed. Install the required Python libraries using the following commands:

```bash
pip install requests
pip install transformers
pip install sentence-transformers
