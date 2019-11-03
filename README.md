Expose - understand your news
===================================

Installation
------------

Download the word-embeddng data set from [[glove.6B.zip](https://nlp.stanford.edu/projects/glove/)] and put it under data/word_embeddings/glove/


Natural Language Processing - subjectiveness classification
------------------------
You can input a text file from the command line: 
```bash
python -m subjectivity.classify < data/name_of_the_text.txt
```

The output will look like the following:
```text
Objective characters:
<number of characters in objective sentences in the text>

Subjective characters:
<number of characters in subjective sentences in the text>
```

You can also run /Jupyter/NYT_classifications.ipynb to run 100 New York Times article one time and plot their distribution. 

Web Crawler - news articles
--------------------------------------

```bash
python3 /webcrawler/crawler_usage.py <start-url-string> <number-of-documents-to-crawl> <results-directory-path>
```


On-going App Engine -  google cloud
-----------------


