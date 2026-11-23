# FAQ Chatbot using TF-IDF and Cosine Similarity

## Overview

This project is a simple FAQ-based chatbot that uses Natural Language Processing (NLP) techniques to match user queries with relevant questions from a predefined FAQ database.

Instead of relying on exact keyword matching, the chatbot converts text into numerical representations using **TF-IDF** and calculates similarity using **Cosine Similarity** to identify the most relevant responses.

## Features

- Text-based question answering
- TF-IDF vectorization
- Cosine similarity for query matching
- Ranking of the most relevant FAQs
- Returns the top 3 relevant matches
- Feedback-based improvement mechanism
- Fallback response for queries with no sufficiently relevant match
- FAQ database containing approximately 200 questions

## Technologies Used

- Python
- Natural Language Processing (NLP)
- Scikit-learn
- TF-IDF Vectorizer
- Cosine Similarity
- Google Colab

## How It Works

1. The chatbot stores questions and answers in an FAQ database.
2. FAQ questions are converted into numerical vectors using TF-IDF.
3. A user's query is vectorized using the same method.
4. Cosine similarity is calculated between the query and FAQ vectors.
5. FAQs are ranked based on similarity scores.
6. The chatbot returns the most relevant results.
7. If no sufficiently relevant answer is found, the chatbot provides a fallback response.

## Project Structure

```text
FAQ-Chatbot/
│
├── FAQ_Chatbot.ipynb
├── README.md
└── requirements.txt
```

## Installation

Install the required libraries:

```bash
pip install scikit-learn
```

## Usage

Run the notebook in Google Colab or a local Jupyter Notebook environment.

Enter a question and the chatbot will search the FAQ database and return the most relevant answers.

## Learning Objectives

This project demonstrates the application of:

- Natural Language Processing
- Text preprocessing and vectorization
- Information retrieval
- Similarity-based ranking
- Basic conversational systems
- Feedback mechanisms in chatbot systems

## Future Improvements

- Integration with a web-based interface
- Larger and more diverse FAQ datasets
- Improved text preprocessing
- Advanced NLP models
- Persistent feedback storage
- User-friendly chatbot interface

## Author

Developed as part of a Natural Language Processing and Responsive AI project.
