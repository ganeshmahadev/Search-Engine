# Search Engine Project

Welcome to the **Search Engine Project**! This project uses advanced Natural Language Processing (NLP) and machine learning techniques to create a search engine capable of indexing and retrieving text documents, offering an intuitive search experience based on user queries.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Technologies Used](#technologies-used)
- [License](#license)

## Overview

This search engine leverages libraries like `langchain`, `sentence_transformers`, and `chromadb` to process and rank documents. It performs preprocessing, query understanding, and indexing, making it efficient for both small and large datasets. It also integrates various NLP tools for optimal search accuracy and relevancy.

## Features

- **Document Indexing**: Quickly indexes text data for fast retrieval.
- **Query Processing**: Efficient query interpretation to ensure relevant search results.
- **Ranking Mechanism**: Ranks search results based on relevance and contextual matching.
- **NLP Preprocessing**: Uses NLP methods for tokenization, stemming, and removing stopwords.
- **Integration with External APIs**: Fetches and processes data from various sources, like Wikipedia and YouTube transcripts.

## Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/ganeshmahadev/Search-Engine.git
    ```
2. **Navigate to the Project Directory**:
    ```bash
    cd Search-Engine
    ```
3. **Set Up a Virtual Environment (Optional)**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # For Mac/Linux
    venv\Scripts\activate     # For Windows
    ```
4. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Run the Application**:
    ```bash
    python app.py
    ```
2. **Using the Search Engine**:
   - Enter a keyword or phrase as a query, and the search engine will retrieve and display relevant documents.

## File Structure

```plaintext
Search-Engine/
├── app.py                    # Main application script
├── requirements.txt          # List of dependencies
├── tools_agents.ipynb        # Jupyter notebook with additional tools and agents
└── data/                     # Directory to store document data
