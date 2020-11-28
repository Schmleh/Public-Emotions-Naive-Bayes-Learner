# Public-Emotions

This code was written for "AI In Fiction and Fact", a course at Rensselaer Polytechnic Institute.
The course was taught by Professor Oshani Seneviratne and Professor Jim Hendler, Summer of 2020.

## Contributors

Note that this is an archived version of a private repository made for the duration of the class.

This code was written by Helen Yuan, Iris Liu, Min Yue, and Willie Xia.

(Contributions may vary, as it was written in tandem via Jupyter Notebook.)

* Professor Hendler - https://www.cs.rpi.edu/~hendler/
* Professor Oshani - https://github.com/oshanis
* Helen Yuan - https://github.com/hyuan0v0
* Iris Liu - https://github.com/IrisLiu0
* Min Yue - https://github.com/Schmleh
* Willie Xia - https://github.com/WillieXia


## Code to Run
All of our code is on Python notebooks. Run our code on a software that can run Python notebooks. We recommend the use of either Google Colab or Jupyter.
* NewNaiveBayes.ipynb runs our training and our analysis on your own custom sentences, which you may give it real time.
* GetTweets.ipynb contains the code that creates a formatted training dataset from IEEE Dataport and Hydrator.
* NLTK_sentiment_analyzer.ipynb is an old version of our code which attempted sentiment analysis using the Natural Language Toolkit

## External Resources Used
* [IEEE Dataport Coronavirus (COVID-19) Tweets Dataset](https://ieee-dataport.org/open-access/coronavirus-covid-19-tweets-dataset)
	* This datset contains sentiment scores computed by [TextBlob](https://textblob.readthedocs.io/en/dev/). We use these scores in our dataset used to train our AI model.
* Hydrate the tweet IDs using [Hydrator](https://github.com/DocNow/hydrator)
* [Google Cloud Natural Language API](https://cloud.google.com/natural-language/)

## Requirements.txt

This is created by

```
pip3 freeze > requirements.txt
```
