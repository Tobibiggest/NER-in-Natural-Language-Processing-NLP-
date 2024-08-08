## Simple Named Entity Recognition (NER) with NLP Techniques

This project implements a basic Named Entity Recognition (NER) system using various Natural Language Processing (NLP) techniques. It identifies and classifies named entities like people, organizations, locations, dates, etc., within a text.

### Steps Involved

The project follows these key steps for NER:

1. **Segmentation:** Splitting the text into meaningful units like sentences. (Optional, depending on the data format)
2. **Tokenization:** Breaking sentences down into individual words (tokens).
3. **Stop-word Removal:** Removing commonly used words that don't contribute much to meaning (e.g., "the", "a", "is").
4. **Lemmatization (vs. Stemming):** Converting words to their base form (lemma) while preserving their morphological information. This is compared with stemming to showcase the advantages of lemmatization.
5. **Part-of-Speech (POS) Tagging:** Assigning a grammatical tag (e.g., noun, verb) to each token.
6. **Named Entity Recognition:** Identifying and classifying named entities based on predefined rules or machine learning models.

### Key Takeaway

**Lemmatization vs. Stemming:**

Both lemmatization and stemming aim to reduce a word to its base form. However, As seen in this project, lemmatization takes context into account, ensuring the resulting word is an actual word (lemma) in the language. Stemming, on the other hand, simply removes suffixes without considering the context, which can sometimes create non-existent words. This project demonstrates the benefit of using lemmatization for better accuracy in NER tasks.


### Getting Started

1. **Clone the Repository:**

```
git clone https://github.com/<tobibiggest>/simple-ner.git
```

2. **Install Dependencies:**

The project uses libraries like NLTK for NLP processing. Install them using:

```
pip install -r requirements.txt
```

3. **Run the Script:**

Execute the main script (`main.py`) to perform NER on a sample text or provide your own text as input.
