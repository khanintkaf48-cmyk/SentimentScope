# SentimentScope — US Elections Sentiment Analysis

SentimentScope is a Python/Jupyter Notebook project that explores tweets about the 2020 US presidential election and compares public discussion of Donald Trump and Joe Biden.

## What the notebook does

- Loads tweet datasets for Donald Trump and Joe Biden.
- Combines and explores tweet counts, likes, and geographic distribution.
- Cleans tweet text and uses TextBlob sentiment polarity/subjectivity.
- Visualizes sentiment results and word clouds for both candidates.

> **Note:** This is an exploratory analysis of tweets, not a scientific measurement of the full electorate or a reliable prediction of election results.

## Project files

- `US Elections Sentiment Analysis.ipynb` — the original notebook.
- `Link to DataSet.txt` — link to the Kaggle dataset.

## Requirements

Use Python 3.9–3.11 if possible. The notebook imports these packages:

- numpy
- pandas
- matplotlib
- seaborn
- tensorflow
- textblob
- nltk
- wordcloud

Install them in a terminal:

```bash
python -m pip install numpy pandas matplotlib seaborn tensorflow textblob nltk wordcloud
```

## Get the dataset

1. Open `Link to DataSet.txt` or visit: https://www.kaggle.com/manchunhui/us-election-2020-tweets
2. Download the dataset from Kaggle (a Kaggle account may be required).
3. Place `hashtag_donaldtrump.csv` and `hashtag_joebiden.csv` in the same folder as the notebook. These are the filenames referenced in the notebook.

## Run in VS Code

1. Install Python and the **Python** and **Jupyter** extensions in VS Code.
2. Open the `SentimentScope` folder.
3. Open `US Elections Sentiment Analysis.ipynb`.
4. Select a Python kernel/interpreter.
5. Run the notebook cells from top to bottom.

If NLTK reports that a resource is missing, follow the download instructions shown in the error message and rerun the cell.

## Important

The original notebook is preserved; this README and the top-level project folder name are the only intended organizational changes. The CSV datasets are not included in this ZIP and must be downloaded separately from the Kaggle source above.
