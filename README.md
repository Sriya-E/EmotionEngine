TechMoodSwing: AI-Powered Sentiment Analysis of Tech Articles

Overview:
TechMoodSwing is a Python-based project developed as part of an internship assignment for analyzing technology-related articles.
The goal is to extract insights from articles using sentiment analysis, calculate positive/negative scores, polarity, subjectivity, and other readability metrics.
This tool demonstrates how natural language processing (NLP) and text analytics can help understand the mood or tone of tech content published online.

Assignment/Internship Context:
- The project was created during an internship opportunity where we were tasked to:
  - Analyze tech articles programmatically
  - Generate quantitative sentiment scores
  - Summarize content readability and complexity
- This showcases both Python coding skills and understanding of data-driven text analytics.

Features:
- Reads article URLs from a text file (input_urls.txt)
- Downloads and saves articles as individual text files
- Cleans the text and removes stopwords
- Uses positive, negative, and tech-specific dictionaries to analyze sentiment
- Calculates metrics:
  * Positive Score
  * Negative Score
  * Polarity Score
  * Subjectivity Score
  * Average Sentence Length
  * Percentage of Complex Words
  * Gunning Fog Index
  * Average Word Length
  * Syllables per Word
  * Personal Pronouns Count

Folder Structure:
TechMoodSwing/
|
├─ main.py                  # Main Python file
├─ input_urls.txt           # List of URLs to analyze
├─ MasterDictionary/        # Word dictionaries
│   ├─ positive-words.txt
│   ├─ negative-words.txt
│   └─ tech-words.txt
├─ StopWords/               # Stopwords
│   ├─ general-stopwords.txt
│   └─ tech-stopwords.txt
├─ Articles/                # Folder where articles are saved
└─ .gitignore

How to Run:
1. Clone this repository or download it.
2. Make sure you have Python installed (>=3.8)
3. Install required libraries:
   pip install pandas requests beautifulsoup4 nltk
4. Put URLs to analyze in input_urls.txt (one URL per line)
5. Run the main file:
   python main.py
6. Each article will be saved in the Articles/ folder
7. Sentiment analysis results are saved as individual text outputs in the same folder

Tech Stack:
- Python
- NLTK for tokenization and text processing
- BeautifulSoup4 for web scraping
- Pandas for data management

Fun Facts:
- This project is like giving AI a mood ring for tech articles!
- Even articles on code reviews, cloud computing, or AI frameworks get a happy, sad, or meh score.

License:
This project is for educational purposes and open for experimentation. Feel free to fork it, tweak it, or use it for your own projects!

Note on Internship Experience:
This project was completed as part of an internship assignment. Unfortunately, after submitting the assignment, the internship contact did not follow through, and communication was lost. 
While the experience was disappointing, it provided an excellent opportunity to practice real-world data analysis, web scraping, and sentiment analysis skills independently.
