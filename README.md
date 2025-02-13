Data Extraction and NLP

Objective:
The objective of this project is to extract textual data articles from the given URLs and perform text analysis to compute specific linguistic and readability metrics.

Data Extraction:
Input: Input.xlsx

For each article listed in Input.xlsx, extract the article text and save it as a text file with the corresponding URL_ID as the file name.

Ensure that only the article title and article text are extracted. Exclude website headers, footers, and any irrelevant content.

Note: Use Python programming for data extraction.

You may use libraries such as BeautifulSoup, Selenium, Scrapy, or any other suitable Python tools for web scraping.

Data Analysis:
For each extracted text file, perform textual analysis and compute the variables as specified in Text Analysis.docx. The results should be stored in Output Data Structure.xlsx following the given format.

Variables Computed
The following metrics will be calculated from the extracted article text:

POSITIVE SCORE

NEGATIVE SCORE

POLARITY SCORE

SUBJECTIVITY SCORE

AVG SENTENCE LENGTH

PERCENTAGE OF COMPLEX WORDS

FOG INDEX

AVG NUMBER OF WORDS PER SENTENCE

COMPLEX WORD COUNT

WORD COUNT

SYLLABLE PER WORD

PERSONAL PRONOUNS

AVG WORD LENGTH

Output Data Structure

The final output will contain:

All input variables from Input.xlsx

The computed textual analysis metrics

The output format should strictly follow the structure defined in Output Data Structure.xlsx.

Tools & Libraries

Data Extraction: BeautifulSoup, Selenium, Scrapy
Data Analysis: NLTK, TextBlob, re, pandas, numpy

License:

This project is open-source and available under the MIT License.
