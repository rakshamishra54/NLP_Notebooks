# NLP_Notebooks
# NLP Notebooks

A collection of Jupyter/Colab notebooks where I practice Natural Language Processing, from basic text cleaning to word embeddings. Each notebook covers one topic and is numbered in the order I learned it.

## Notebooks

| # | Notebook | What it covers |
|---|----------|----------------|
| 01 | [Text Preprocessing](notebooks/01_text_preprocessing.ipynb) | Lowercasing, removing HTML tags and emails, punctuation removal, tokenization, stopword removal, stemming (Porter Stemmer) |
| 02 | [POS Tagging](notebooks/02_pos_tagging.ipynb) | Part-of-speech tagging with NLTK / spaCy |
| 03 | [Word2Vec](notebooks/03_word2vec.ipynb) | Training and using word embeddings with Gensim |

More notebooks will be added as I go (text classification, TF-IDF, etc.).

## Dataset

The preprocessing notebook uses the **IMDb Dataset of 50K Movie Reviews** (25,000 positive and 25,000 negative reviews).

- Download it from Kaggle: search for "IMDB Dataset of 50K Movie Reviews"
- The CSV is not included in this repo because of its size (~65 MB). Download it and update the `path` variable in the notebook to point to your copy.

## Tech Stack

- Python 3
- pandas, NumPy
- NLTK
- spaCy
- Gensim
- Google Colab

## How to Run

1. Open any notebook in [Google Colab](https://colab.research.google.com) (download the `.ipynb` file and upload it).
2. Download the dataset (see above) and upload it to Colab or mount your Google Drive.
3. Run the cells from top to bottom.

To run locally instead:

```bash
git clone https://github.com/rakshamishra54/NLP_Notebooks.git
cd NLP_Notebooks
pip install pandas numpy nltk spacy gensim jupyter
jupyter notebook
```

## Repository Structure

```
NLP_Notebooks/
├── README.md
└── notebooks/
    ├── 01_text_preprocessing.ipynb
    ├── 02_pos_tagging.ipynb
    └── 03_word2vec.ipynb
```

## Author

**Raksha Mishra**
GitHub: [@rakshamishra54](https://github.com/rakshamishra54)
