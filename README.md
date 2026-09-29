# 🏷️ Named Entity Recognition (NER) with spaCy

This repository demonstrates how to perform **Named Entity Recognition (NER)** using the `spaCy` library in Python. The script extracts real-world entities (such as people, organizations, and locations) from unstructured text and organizes them into a structured Pandas DataFrame.

## 🚀 Core Features

1. **Entity Extraction (`spaCy`):** 
   - Loads the English language model (`en_core_web_sm`) to parse and analyze text.
   - Automatically detects and categorizes entities (e.g., Person, Organization, Location, GPE).
2. **Detailed Attributes:** 
   - Extracts entity text, start/end character indices, entity labels, and lemmatized forms (`ent.lemma_`).
3. **Structured Data Conversion:** 
   - Aggregates the extracted entities into a clean, tabular format using `Pandas DataFrame`.

## 🛠️ Tech Stack
- `Python`
- `spaCy` (Industrial-strength Natural Language Processing)
- `Pandas` (Data manipulation and structuring)

## 💻 How to Run

1. Install the required libraries and download the spaCy English model:
   ```bash
   pip install spacy pandas
   python -m spacy download en_core_web_sm
