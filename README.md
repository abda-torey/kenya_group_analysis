# Kenyans in Ireland WhatsApp Group Analysis

This Jupyter notebook provides an in-depth analysis of the conversations within the "Kenyans in Ireland" WhatsApp group. Through data visualization and natural language processing (NLP), we uncover insights into the group's dynamics, including message trends, emoji usage, and frequently discussed topics.

## Features

- **Emoji Analysis:** Identifies the most commonly used emojis within the group, offering insights into the emotional tone of the conversations.
- **Message Trends:** Tracks the volume of messages over time, highlighting peak activity periods.
- **Top Contributors:** Reveals the most active members of the group, based on the number of messages sent.
- **Word Cloud:** Visualizes the most frequently mentioned words, shedding light on the group's main topics of interest.
- **Deleted Message Analysis:** Quantifies and explores the context around messages that were deleted by the group's admins.
- **English Word Usage:** Differentiates between English and non-English words used in conversations, providing a linguistic overview.

## Requirements

To run this notebook, you'll need the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- emoji
- nltk
- wordcloud

You can install these packages using pip:

```bash
pip install pandas numpy matplotlib seaborn emoji nltk wordcloud
```
## Make sure to download the necessary NLTK data:

```
import nltk
nltk.download('stopwords')
nltk.download('words')
nltk.download('punkt')
nltk.download('wordnet')
```
### Usage
1. Preparing Your Data: Export your WhatsApp group chat and save it as _chat.txt in the same directory as the notebook.

2. Running the Notebook: Open the notebook in Jupyter or another compatible environment and execute the cells sequentially.

3. Interpreting the Results: Each section includes visualizations and summaries. Review these to gain insights into the group's communication patterns.
