# chinese-grammar-helper

A GenAI application to explain Chinese grammatical structures and help point me to relevant pages to understand my Chinese mistakes and uncertainties.

## Setting up API keys

Create an account and an API key here: https://platform.openai.com/api-keys

Then populate it in your `.env` file. An example of what the `.env` file should look like is in `t.env.dist`.


## Setting up vector database

Create new vector database with Astra.

## Fetching data
There are two ways to get data.

### 1. Scraping website data from allsetlearning.
```
zhongwen-llm % python ./src/data/fetch_data.py
```

### 2. Chinese grammar PDF download:
```
curl https://www.kinezika.com/pdf/ModernMandarinChineseGrammar_Textbook.pdf -o data/chinese_grammar_textbook/ModernMandarinChineseGrammar_Textbook.pdf
```
