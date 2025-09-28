# 🍳 NLP Preprocessing Cookbook

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python) ![NLTK](https://img.shields.io/badge/NLTK-3B84A1?style=for-the-badge&logo=nltk) ![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn)

Welcome to the NLP Preprocessing Cookbook! This repository is a collection of essential techniques for cleaning and preparing text data for Machine Learning models. Think of it as a practical guide with code examples for the most common preprocessing steps in any NLP project.

This entire project is demonstrated within a Jupyter Notebook, making it easy to follow along and experiment with each technique.

---

### ✨ Concepts Covered

This notebook is a step-by-step guide through the foundational techniques of NLP data preparation:

1.  **Tokenization (Sentence and Word)**:
    -   The first and most crucial step. I've shown how to break down a large block of text into its basic units—sentences and individual words—using the NLTK library.

2.  **Stemming and Lemmatization**:
    -   To reduce words to their root forms, I've explored two popular techniques:
        -   **Stemming**: A faster, rule-based approach to chop off word endings.
        -   **Lemmatization**: A more advanced, dictionary-based approach that considers the context to find the true root word (lemma).

3.  **Stopwords Removal**:
    -   I've demonstrated how to remove common words (like "is", "the", "a") that add little semantic value, which helps the model focus on the more important keywords.

4.  **Text Cleaning with RegEx**:
    -   Real-world text is messy! I've used Regular Expressions (RegEx) to clean the text by removing punctuation, numbers, and other unwanted characters.

5.  **Text Vectorization (Bag-of-Words)**:
    -   Finally, to make the text understandable for a machine learning model, I've converted the cleaned words into numerical vectors using Scikit-learn's `CountVectorizer`. This technique, also known as Bag-of-Words, is a fundamental method for feature extraction in NLP.

---

### 🛠️ Libraries Used

-   **NLTK (Natural Language Toolkit)**: For tokenization, stemming, lemmatization, and stopwords.
-   **Scikit-learn**: For text vectorization with `CountVectorizer`.
-   **Jupyter Notebook**: For interactive development and demonstration.

---

### ⚙️ Setup and Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/jsonusuman351/nlp-preprocessing-cookbook.git](https://github.com/jsonusuman351/nlp-preprocessing-cookbook.git)
    cd nlp-preprocessing-cookbook
    ```

2.  **Create and activate a virtual environment:**
    ```bash
    # It is recommended to use Python 3.10 or higher
    python -m venv venv
    .\venv\Scripts\activate
    ```

3.  **Install the required packages:**
    ```bash
    pip install notebook nltk scikit-learn
    ```

4.  **One-Time NLTK Downloads:**
    The first time you run this, you'll need to download some necessary models from NLTK. Open a Python interpreter from your activated environment and run:
    ```python
    import nltk
    nltk.download('punkt')
    nltk.download('stopwords')
    nltk.download('wordnet')
    exit()
    ```

---

### 🚀 How to Use This Project

The entire workflow is contained within a single Jupyter Notebook.

1.  **Launch Jupyter:**
    Make sure your virtual environment is active, then run:
    ```bash
    jupyter notebook
    ```
2.  **Open the Notebook:**
    In the Jupyter interface, click on `NLTK-CountVectorizer.ipynb`.
3.  **Run the Cells:**
    You can run each cell sequentially to see how each preprocessing technique transforms the text step-by-step.

---

### 🔬 A Tour of the Cookbook

I've organized this entire project into a single notebook to make it easy to follow my experiments with different NLP preprocessing techniques.

<details>
<summary>Click to view the code layout</summary>

```
nlp-preprocessing-cookbook/
│
└── NLTK-CountVectorizer.ipynb    # The complete end-to-end workflow is in this single notebook
```
</details>

---

---
