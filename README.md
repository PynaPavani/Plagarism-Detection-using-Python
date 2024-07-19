# Plagiarism Detection Using Python

## Overview

This repository contains a Python implementation of a plagiarism detection system using cosine similarity. The system is designed to identify similarities between text documents and detect potential cases of plagiarism.

## Features

- **Cosine Similarity**: Calculates the similarity between text documents based on their vector representations.
- **Wordcloud Visualization**: Generates word clouds for visual representation of the text data.

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/PynaPavani/plagiarism-detection-python.git
    cd plagiarism-detection-python
    ```

2. **Install the required dependencies:**

    It's recommended to use a virtual environment. You can install the necessary packages using pip:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Prepare your text documents:**

    Place the text files you want to analyze in the `documents/` directory.

2. **Run the plagiarism detection script:**

    ```bash
    plag.ipynb
    ```

    This will analyze the documents in the `data/` directory, calculate the cosine similarity between them, and generate a word cloud for each document.

3. **View results:**

    - **Cosine Similarity Results**: The similarity scores between documents will be displayed in the terminal.
    - **Wordcloud Visualizations**: Word clouds will be saved in the `wordclouds/` directory.

## Example

An example of running the script and the resulting outputs:

```bash
plag.ipynb
```

*Output:*

- Similarity score between `doc1.txt` and `doc2.txt`: `0.85`
- Word clouds generated and saved in `wordclouds/` directory.

## Dependencies

- `numpy`
- `scikit-learn`
- `matplotlib`
- `wordcloud`

