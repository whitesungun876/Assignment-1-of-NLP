# ELTeC Corpora NLP Assignment

This repository contains an NLP project where I work with the ELTeC corpora in English, Spanish, and an additional language of my choice. The corpora have been downloaded from Zenodo (links below), processed, and analyzed using various Natural Language Processing techniques.

## Project Steps:
1. **Corpus Download & Preparation:**
   - Downloaded the ELTeC corpora in English, Spanish, and a third language from Zenodo:
     - [English corpus](https://zenodo.org/records/4662490)
     - [Spanish corpus](https://zenodo.org/records/4662603)
     - Other languages can be selected from the [Related works](https://zenodo.org/records/4662444) section.
   - Read the corpora and exported raw text versions (saved as `en.txt`, `sp.txt`, and `xx.txt` for the third language).

2. **Tokenization & Text Processing:**
   - Developed a custom tokenizer for the three languages using regular expressions (regex).
   - Printed the first 100 tokens for each language.
   - Tokenized the English corpus using NLTK, saving the first 2000 tokens in `EN_mytok_red.txt` and `EN_NLTK_tok.txt`.
   - Compared the output of the two tokenization methods and analyzed the differences.

3. **Text Normalization:**
   - Stemming of the English corpus using the NLTK Porter Stemmer.
   - Lemmatized the English corpus using the NLTK WordNetLemmatizer.
   - Analyzed the differences between the stems and lemmas of the first 50 tokens.

4. **Frequency & Distribution Analysis:**
   - Generated frequency distributions and Zipf’s law distributions for the three corpora.
   - Provided an explanation and interpretation of the results.

5. **Language Guessing Exercise:**
   - Attempted to guess how "and" is expressed in the third language (without using a translation service or dictionary) and explained the reasoning.

6. **Advanced Processing (English corpus):**
   - Sentence tokenized the English corpus using NLTK.
   - Removed stopwords from the English corpus.
   - Printed the first 10 sentences.
   - Saved the pre-processed corpus in `EN_preproc.txt`.
   - Used the Universal PoS-tagger to count the number of substantives (nouns) in the tokenized English text.

## Files:
- `en.txt` - Raw text from the English corpus
- `sp.txt` - Raw text from the Spanish corpus
- `xx.txt` - Raw text from the third language corpus
- `EN_mytok_red.txt` - First 2000 tokens using custom regex tokenizer
- `EN_NLTK_tok.txt` - First 2000 tokens using NLTK tokenizer
- `EN_preproc.txt` - Pre-processed English corpus (stop words removed)

## Insights:
- Frequency and Zipf distributions provided insight into the text patterns across languages.
- The comparison of tokenization methods highlighted differences in handling punctuation and word boundaries.

