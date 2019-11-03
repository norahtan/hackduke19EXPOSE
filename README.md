Expose - understand your news
===================================

Installation
------------

Download [[glove.6B.zip](https://nlp.stanford.edu/projects/glove/)]


Natural Language Processing - subjectiveness classification
------------------------
pipe a text file from the command line: 
```bash
python -m subjectivity.classify < data/name_of_the_text.txt
```

The output will look like the following:
```text
OBJECTIVE SENTENCES
<list of objective sentences in the text>

SUBJECTIVE SENTENCES
<list of subjective sentences in the text>
```

Web Crawler - news articles
--------------------------------------

```bash
python -m subjectivity.train
```


On-going App Engine -  google cloud
-----------------


