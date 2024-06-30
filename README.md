# WhatsApp-Chat-Analyzer
```sh
(view app: https://whatsappcanalyzer-7419bf9fb243.herokuapp.com/)
```
This projrct is a WhatsApp Chat Analyzer that provides various insight and statistics about your WhatsApp chayts.

## Features

- Analyze the number of messages, words, and links shared by individually or overall.
- View monthly and daily timelines of messages.
- Visualize activity maps showing the busiest days and months.
- Generate word clouds of the most common words.
- Analyze emoji usege.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/princ0301/WhatsApp-Chat-Analyzer.git
   cd WhatsApp-Chat-Analyzer
   

2. Install the required packages:
   ```sh
   pip install -r requirements.txt

## Usage
1. Run the Streamlit application:
   ```sh
   streamlit run app.py
   ```
2. Upload you Whatsapp Chat file in the sidebar.
4. Select the user to analyze and click "Show Analysis".

## Dataset
For this project, I used my personal WhatsApp chat dataset. This includes chats from variours group and individual conversations over a period of time.
- Format: The dataset is in text (.txt) format, exporting from WhatsApp.
- Content: It contains text messages, media messages (represented as "<Media omitted>"), links and emojis.

## Project Structure

 - app.py                      # Main application file
 - preprocessor.py             # Data preprocessing functions
 - helper.py                   # Helper functions for analysis
 - requirements.txt            # Required Python packages
 - README.md                   # This file
