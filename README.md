# Sentiment Analysis Tool

This Python tool performs sentiment analysis on textual data stored in a CSV file. It utilizes the TextBlob library to analyze the sentiment polarity of the specified column in the CSV file.

## Features

- **CSV Data Analysis**: Analyze sentiment polarity of textual data in a specified CSV column.
- **TextBlob Integration**: Uses TextBlob to perform sentiment analysis.
- **Output Saving**: Saves the results of sentiment analysis in a new CSV file.
- **Timestamped Results**: Output CSV files are timestamped for easy tracking and management.

## Usage

1. **CSV Data**: Ensure your data is in a CSV file format.
2. **File Path and Column Selection**: Modify the `csv_file_path` variable with the relative path to your CSV file and `col_to_analyze` variable with the column name containing text data.
3. **Run the Script**: Execute the script to perform sentiment analysis on the specified CSV column.
4. **Results**: The tool generates a new CSV file in the "results" folder, containing the original data along with an additional column "sentiment" representing the sentiment polarity of the text.

## Prerequisites

- Python 3.x
- `pandas` Python library (Install using `pip install pandas`)
- `textblob` Python library (Install using `pip install textblob`)

## Installation and Usage

```bash
git clone https://github.com/lazy-szilard/FeedbackAnalyzer.git
cd FeedbackAnalyzer
python main.py

