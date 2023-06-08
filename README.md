# Text Summarisation Using NLTK

This project leverages the power of Natural Language Toolkit (NLTK) to summarize the content fetched from a given URL or user-input text. It provides users with a succinct summary, helping them understand the crux of the content quickly and efficiently.

## Overview

In the era of information overload, it's often time-consuming to sift through lengthy texts to understand their essence. This tool is a response to that problem. It can either take a URL of a website or user-provided text and return a concise summary. Users can customize the length of the summary to suit their needs, specifying the number of lines they wish to see.

## Features

* Fetches and processes text from a user-provided URL
* Accepts and processes directly inputted user text
* Summarizes the fetched or inputted text using NLTK
* Allows users to specify the number of lines in the summary

## Tools and Libraries Used

* Python 3.x
* NLTK - for natural language processing tasks
* BeautifulSoup - for web scraping tasks (if used)

## Installation & Usage

Instructions on how to install and run your code. For example:

```sh
git clone https://github.com/kashyapHebbar/text_summarization.git
```

## How It Works

The program first extracts the text from the provided URL or takes the inputted user text. It then tokenizes the text into sentences and words, calculates the frequency of each word, and assigns a score to each sentence based on the words it contains. It then selects the highest-scoring sentences to form the summary, adhering to the user's specified length.

## Future Plans

We plan to continuously refine the summarization algorithm and introduce features like keyword extraction and named entity recognition for more context-aware summaries.

## Acknowledgements

This project is built upon the powerful Natural Language Processing capabilities provided by the NLTK library.


