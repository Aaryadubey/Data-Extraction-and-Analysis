# Data-Extraction-and-Analysis
Objective :
The objective of this assignment is to extract textual data articles from a given URL and 
perform text analysis to compute variables.
Approach:
1. Data Extraction: Utilized the `requests` library to fetch the HTML content of the provided 
URL. Employed `BeautifulSoup` for parsing the HTML and extracting only the article title and 
text, excluding any unwanted sections such as headers, footers, or advertisements.
2. Text Analysis: Used the `nltk` library for text processing tasks such as tokenization, 
stopwords removal, and stemming/lemmatization. Conducted various analyses, including 
word frequency analysis, sentiment analysis, or any other relevant analysis specified by the 
assignment.
3. Output Formatting: Saved the output in the exact order as specified in the "Output Data 
Structure.xlsx" file.
Dependencies Required:
• `pandas`: For data manipulation and handling.
• `beautifulsoup4`: For parsing HTML content.
• `nltk`: For natural language processing tasks.
• `requests`: For making HTTP requests to fetch web content.
Brief Explanation:
1. Iterated over rows function to process each article from the given URL.
2. Extracted only the article title and text using BeautifulSoup, ensuring exclusion of 
unwanted sections.
3. Conducted text analysis using nltk library, such as tokenization, stopwords removal, and 
other specified analyses.
4. Formatted the output according to the structure specified in the "Output Data 
Structure.xlsx" file.
Running the .py File:
• After writing the code in your .py file, save it.
• Open a terminal or command prompt.
• Navigate to the directory where your .py file is saved.
• Run the .py file using Python interpreter. Example command: `python your_script.py.'
