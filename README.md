# Project: LangLens

## Overview
**LangLens** is a collection of Jupyter notebooks focusing on various natural language processing (NLP) tasks. The project includes tools for document summarization, language classification, syntax tree construction, and geographic text analysis using Wikipedia data. The primary goal of this project is to provide modular and reusable code for diverse NLP challenges.

---

## Notebooks Included

### 1. `context_window_summarizer.ipynb`
This notebook provides a framework for summarizing long documents by:
- Measuring document length in tokens.
- Computing target summary lengths based on a specified ratio.
- Slicing documents into manageable chunks for summarization.

### 2. `english_vs_nonenglish_classifier.ipynb`
A Naïve Bayes classifier that distinguishes between English and non-English texts:
- Uses the Universal Declaration of Human Rights (UDHR) corpus from NLTK.
- Implements preprocessing, feature extraction, and model training.
- Achieves classification using a bag-of-words approach.
- Provides performance metrics such as accuracy and confusion matrix.

### 3. `language_syntax_tree_builder.ipynb`
This notebook builds syntax trees for English, French, and German sentences:
- Uses Context-Free Grammar (CFG) with the NLTK library.
- Demonstrates parsing of sample sentences in each language.
- Visualizes syntax trees for better linguistic understanding.
- Supports visual rendering of parse trees in the notebook.

### 4. `wikipedia_geo_text_analysis.ipynb`
Classifies Wikipedia text as geographic or non-geographic using:
- Preprocessing techniques like tokenization, stop word removal, stemming, and lemmatization.
- Advanced data collection from Wikipedia using search queries and category-based expansion.
- A Naïve Bayes classifier with feature extraction and model evaluation.
- Includes methods for both search-based and category-based dataset expansion.

---

## Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook
- Required Python libraries:
```bash
pip install nltk wikipedia requests
```

### Usage
1. Clone the repository:
```bash
git clone https://github.com/TavakoliMajid/LangLens.git
cd LangLens
```

2. Launch Jupyter Notebook:
```bash
jupyter notebook
```

3. Open and run any of the provided notebooks.

---

## Roadmap
- [ ] Add more languages to the syntax tree builder.
- [ ] Improve text classification models with advanced ML techniques.
- [ ] Integrate deep learning models for document summarization.
- [ ] Develop a web interface for real-time text analysis.

---

## Contributing
Contributions are welcome! Please fork this repository, create a feature branch, and submit a pull request.

---

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

