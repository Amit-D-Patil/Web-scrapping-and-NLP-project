# Web-scrapping-and-NLP-project
This Python project extracts article text from URLs in an Excel file and performs NLP analysis to compute variables such as sentiment scores, readability measures, and word usage statistics. It uses web scraping libraries such as BeautifulSoup or Scrapy and NLP libraries such as NLTK or spaCy. The results are stored in a new Excel or CSV file.


# Web Scraping and NLP Project

This Python project extracts article text from a list of URLs provided in an Excel file and performs text analysis on each article to compute various variables. It uses web scraping libraries such as BeautifulSoup or Scrapy to extract article text from each URL, and NLP libraries such as NLTK or spaCy to perform text analysis on each article. The program computes various variables such as sentiment scores, readability measures, and word usage statistics and stores the results in a new CSV or Excel file.

## Project Objectives

* Extract article text from a list of URLs provided in an Excel file
* Perform text analysis on each article to compute various variables
* Use web scraping libraries such as BeautifulSoup or Scrapy to extract article text from each URL
* Use NLP libraries such as NLTK or spaCy to perform text analysis on each article
* Compute various variables such as sentiment scores, readability measures, and word usage statistics
* Store the results in a new CSV or Excel file

## Input Data

The input data is provided in the form of an Excel file named Input.xlsx, which contains a list of URLs along with their associated URL_ID, Title, and Publication Date.

## Output Data

The output data structure is provided in the form of an Excel file named Output Data Structure.xlsx, which contains a list of input variables along with computed variables such as Positive Score, Negative Score, Polarity Score, Subjectivity Score, Average Sentence Length, Percentage of Complex Words, FOG Index, Average Number of Words per Sentence, Complex Word Count, Word Count, Syllable per Word, Personal Pronouns, and Average Word Length. The program computes these variables for each article and stores the results in a new CSV or Excel file with the same format as Output Data Structure.xlsx.

## Usage

To run the program, execute the following command:

css
Copy code
python main.py input_file.xlsx output_file.xlsx
Replace input_file.xlsx with the name of the input file containing a list of URLs, URL_ID, Title, and Publication Date. Replace output_file.xlsx with the name of the output file where the computed variables will be stored.

## Contributing

If you have any suggestions or contributions to this project, feel free to create a pull request or open an issue on GitHub.


## Acknowledgments

Thank you to the developers of BeautifulSoup, Scrapy, NLTK, spaCy, and other libraries used in this project.
