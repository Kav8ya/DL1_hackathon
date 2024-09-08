Blog Generation with Deep Learning
This project is a part of the Blog generation project using fine-tuned Language models. It demonstrates how to scrape data from WikiHow, preprocess it, and fine-tune a Longformer Encoder Decoder (LED) model to generate headings for paragraphs.

Overview
Language models are essential in Natural Language Processing (NLP) tasks like text generation, summarization, and translation. In this project, we fine-tune a pre-trained language model to generate blog subheadings given a paragraph using web-scraped data from WikiHow. The model is trained to understand the structure and generate coherent headings based on paragraphs.

Project Structure
Section 1: Web Scraping and Dataset Creation
Section 2: Data Preprocessing and Fine-tuning a Language Model
Section 3: Optional Enhancements (Summarization and Tag Generation)

Features
Scrapes blog articles from WikiHow using BeautifulSoup.
Fine-tunes the LED model on a custom dataset to generate headings.
Preprocessing to clean and format the dataset before model training.
Supports further enhancements for summarization and tag generation.

Installation
Requirements
Python 3.x
Kaggle Account (for scraping data and running initial experiments)
Google Colab (for model fine-tuning using GPU)

Python Dependencies
pip install -r requirements.txt

requests: For making HTTP requests to web pages.
BeautifulSoup (bs4): For parsing HTML and extracting content.
transformers: Hugging Face library for loading and fine-tuning models.
pandas: For handling and cleaning datasets.
matplotlib: For visualizing data.

Web Scraping with BeautifulSoup
The first step of the project involves scraping articles from WikiHow. We use BeautifulSoup to extract paragraphs and subheadings from random articles. These articles are structured in HTML, making it easy to extract data by targeting specific tags.

Data Preprocessing
Once the data is scraped, it is processed and cleaned using pandas. We also handle duplicates and outliers, ensuring the dataset is suitable for fine-tuning the language model.

Fine-Tuning the LED Model
We fine-tune the Longformer Encoder Decoder (LED) model to generate subheadings for paragraphs. The model uses the transformers library from Hugging Face.

Future Enhancements
In Section 3, additional tasks include:

Summarizing paragraphs into concise sentences.
Generating relevant tags for each paragraph.

Conclusion
This project demonstrates the power of fine-tuning language models for specific tasks, such as blog generation. Through web scraping, data preprocessing, and fine-tuning, we successfully create a model capable of generating accurate subheadings for blog paragraphs.



