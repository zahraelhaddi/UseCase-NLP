# UseCase-NLP
This is a NLP use case for INWI & Maroc Telecom tweets sentiment Analysis

## Objectives:
- Ingest fresh tweets their metadata using Selenium for web scraping.
- Extract 10 tweets discussing Inwi and 10 tweets discussing the Moroccan telco sector.
- Store the tweets and their metadata in a SQlite database.
- Analyze the sentiment of tweets and score them from 0 (negative) to 1 (positive).
- Investigate common topics in negative tweets.

## Project Structure

```
UseCase-NLP/
│
├── venv/                # Virtual environment
├── .ipynb_checkpoints/  # Checkpoints for jupyter_notebooks                         
├── .env                 # Environment variables
├── .gitignore           # Git ignore file
├── requirements.txt     # Python dependencies
├── 01_data_preprocessing.ipynb      # Jupyter notebook for tweets extraction and ingestion to the database
├── 02_text_classification.ipynb     # Jupyter notebook for sentiment analysis of tweets using NLP in three methods
|
└── tweetsDB.db          # SQLite database file
```


## Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/zahraelhaddi/UseCase-NLP-Zahra.git
   cd UseCase-NLP-Zahra
   ```

2. **Create and activate a virtual environment**:
   - For **Windows**:
     ```bash
     python -m venv venv
     .\venv\Scripts\activate
     ```

3. **Install the required dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run Jupyter Notebooks**:
   - Launch Jupyter Notebooks to explore and run the notebooks in the `notebooks` folder:
     ```bash
     jupyter notebook
     ```

