## Additional Lecture Notes


### Session 8: K-Means Clustering Examples

Here are the animations we saw in class for how K-Means clustering works:

* [Visualizing K-Means](http://tech.nitoyon.com/en/blog/2013/11/07/k-means/)

* [Naftali Harris: Visualizing K-Means Clustering](http://www.naftaliharris.com/blog/visualizing-k-means-clustering/)


### Session 12: Recommender Systems
* Recommendation Engines [slides](slides/18_recommendation_engines.pdf)
* Recommendation Engine Example [code](code/18_recommenders_class.py)

**Resources:**
* [The Netflix Prize](http://www.netflixprize.com/)
* [Why Netflix never implemented the winning solution](https://www.techdirt.com/blog/innovation/articles/20120409/03412518422/why-netflix-never-implemented-algorithm-that-won-netflix-1-million-challenge.shtml)
* [Visualization of the Music Genome Project](http://www.music-map.com/)
* [The People Inside Your Machine](http://www.npr.org/blogs/money/2015/01/30/382657657/episode-600-the-people-inside-your-machine) (23 minutes) is a Planet Money podcast episode about how Amazon Mechanical Turks can assist with recommendation engines (and machine learning in general).


### Session 13: Naive Bayes
* Briefly discuss [A Plan for Spam](http://www.paulgraham.com/spam.html)
* Probability and Bayes' theorem
    * [Slides](slides/13_naive_bayes.pdf) part 1
    * [Visualization of conditional probability](http://setosa.io/conditional/)
    * Applying Bayes' theorem to iris classification ([code](code/13_bayes_iris.py))
* Naive Bayes classification
    * [Slides](slides/13_naive_bayes.pdf) part 2
    * Example with spam email
    * [Airport security example](http://www.quora.com/In-laymans-terms-how-does-Naive-Bayes-work/answer/Konstantin-Tt)
* Naive Bayes classification in scikit-learn ([code](code/13_naive_bayes.py))
    * Data set: [SMS Spam Collection](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection)
    * scikit-learn documentation: [CountVectorizer](http://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.CountVectorizer.html), [Naive Bayes](http://scikit-learn.org/stable/modules/naive_bayes.html)

**Resources:**
* The first part of the slides was adapted from [Visualizing Bayes' theorem](http://oscarbonilla.com/2009/05/visualizing-bayes-theorem/), which includes an additional example (using Venn diagrams) of how this applies to testing for breast cancer.
* For an alternative introduction to Bayes' Theorem, [Bayes' Rule for Ducks](https://planspacedotorg.wordpress.com/2014/02/23/bayes-rule-for-ducks/), this [5-minute video on conditional probability](https://www.youtube.com/watch?v=Zxm4Xxvzohk), or these [slides on conditional probability](https://docs.google.com/presentation/d/1psUIyig6OxHQngGEHr3TMkCvhdLInnKnclQoNUr4G4U/edit#slide=id.gfc69f484_00) may be helpful.
* For more details on Naive Bayes classification, Wikipedia has two useful articles ([Naive Bayes classifier](http://en.wikipedia.org/wiki/Naive_Bayes_classifier) and [Naive Bayes spam filtering](http://en.wikipedia.org/wiki/Naive_Bayes_spam_filtering)), and Cross Validated has an excellent [Q&A](http://stats.stackexchange.com/questions/21822/understanding-naive-bayes).
* If you enjoyed Paul Graham's article, you can read [his follow-up article](http://www.paulgraham.com/better.html) on how he improved his spam filter and this [related paper](http://www.merl.com/publications/docs/TR2004-091.pdf) about state-of-the-art spam filtering in 2004.

**Homework:**
* Download all of the NLTK collections.
   * In Python, use the following commands to bring up the download menu.
   * ```import nltk```
   * ```nltk.download()```
   * Choose "all".
   * Alternatively, just type ```nltk.download('all')```
* Install two new packages:  ```textblob``` and ```lda```.
   * Open a terminal or command prompt.
   * Type ```pip install textblob``` and ```pip install lda```.


### Session 14: Natural Language Processing
* Overview of Natural Language Processing ([slides](slides/14_natural_language_processing.pdf))
* Real World Examples
* Natural Language Processing ([code](code/14_nlp_class.py))
* NLTK: tokenization, stemming, lemmatization, part of speech tagging, stopwords, Named Entity Recognition (Stanford NER Tagger), TF-IDF, LDA, document summarization
* Alternative: TextBlob

**Resources:**
* [Natural Language Processing with Python](http://www.nltk.org/book/): free online book to go in-depth with NLTK
* [NLP online course](https://www.coursera.org/course/nlp): no sessions are available, but [video lectures](https://class.coursera.org/nlp/lecture) and [slides](http://web.stanford.edu/~jurafsky/NLPCourseraSlides.html) are still accessible
* [Brief slides](http://files.meetup.com/7616132/DC-NLP-2013-09%20Charlie%20Greenbacker.pdf) on the major task areas of NLP
* [Detailed slides](https://github.com/ga-students/DAT_SF_9/blob/master/16_Text_Mining/DAT9_lec16_Text_Mining.pdf) on a lot of NLP terminology
* [A visual survey of text visualization techniques](http://textvis.lnu.se/): for exploration and inspiration
* [DC Natural Language Processing](http://www.meetup.com/DC-NLP/): active Meetup group
* [Stanford CoreNLP](http://nlp.stanford.edu/software/corenlp.shtml): suite of tools if you want to get serious about NLP
* Getting started with regex: [Python introductory lesson](https://developers.google.com/edu/python/regular-expressions) and [reference guide](https://github.com/justmarkham/DAT3/blob/master/code/99_regex_reference.py), [real-time regex tester](https://regex101.com/#python), [in-depth tutorials](http://www.rexegg.com/)
* [SpaCy](http://honnibal.github.io/spaCy/): a new NLP package