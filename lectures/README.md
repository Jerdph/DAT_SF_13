## Additional Lecture Notes


### Session 1: Introduction to Data Science

* Overview of Data Science ([slides](DAT13_lec01.pdf))

####Resources:
* Read [Analyzing the Analyzers](http://cdn.oreillystatic.com/oreilly/radarreport/0636920029014/Analyzing_the_Analyzers.pdf) for a useful look at the different types of data scientists.

---

### Session 2: Introduction to Python

* Intro to Python ([slides](DAT13_lec02_Intro_Python.pdf))
* Intro to Version Control ([slides](DAT13_lec02a-Version_Control.pdf))

####Resources:
* Read the first two chapters of [Pro Git](http://git-scm.com/book/en/v2) to gain a much deeper understanding of version control and basic Git commands.
* If you need more practice with Python, review the "1. Python Overview" section of [A Crash Course in Python](http://nbviewer.ipython.org/gist/rpmuller/5920182), work through some of [Codecademy's Python course](http://www.codecademy.com/en/tracks/python), or work through [Google's Python Class](https://developers.google.com/edu/python/) and its exercises.

---

### Session 3: Introduction to Machine Learning with KNN

* Intro to Machine Learning and K-Nearest Neighbors ([slides](DAT13_lec03_Intro_ML_KNN.pdf))

####Resources:
* For a more in-depth look at machine learning, read section 2.1 (14 pages) of Hastie and Tibshirani's excellent book, [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/). (It's a free PDF download!)

---

### Session 4: Regression & Regularization

* Regression and Regularization ([slides](DAT13_lec04_Regression_Regularization.pdf))

####Resources:
* To go much more in-depth on linear regression, read Chapter 3 of [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/)
* This [introduction to linear regression](http://people.duke.edu/~rnau/regintro.htm) is much more detailed and mathematically thorough, and includes lots of good advice.

---

### Session 5: Web APIs, JSON, & Pandas

* Web APIs & JSON ([slides](DAT13_lec05_1_APIs_JSON.pdf))
* Final Project Kickoff ([slides](DAT13_lec05_3_FP_kickoff.pdf))

####Resources:
* Here is a great [Pandas Cheat Sheet](http://nbviewer.ipython.org/github/pybokeh/ipython_notebooks/blob/master/pandas/PandasCheatSheet.ipynb)
	* To learn more Pandas, review this [three-part tutorial](http://www.gregreda.com/2013/10/26/intro-to-pandas-data-structures/), or review these three excellent (but extremely long) notebooks on Pandas: [introduction](http://nbviewer.ipython.org/urls/raw.github.com/fonnesbeck/Bios8366/master/notebooks/Section2_5-Introduction-to-Pandas.ipynb), [data wrangling](http://nbviewer.ipython.org/urls/raw.github.com/fonnesbeck/Bios8366/master/notebooks/Section2_6-Data-Wrangling-with-Pandas.ipynb), and [plotting](http://nbviewer.ipython.org/urls/raw.github.com/fonnesbeck/Bios8366/master/notebooks/Section2_7-Plotting-with-Pandas.ipynb).
* For more on Pandas plotting, read the [visualization page](http://pandas.pydata.org/pandas-docs/stable/visualization.html) from the official Pandas documentation.
* To learn how to customize your plots further, browse through this [notebook on matplotlib](http://nbviewer.ipython.org/github/fonnesbeck/Bios8366/blob/master/notebooks/Section2_4-Matplotlib.ipynb).

---

### Session 6: Decision Trees for Classification & Regression

* Decision Trees ([slides](DAT13_lec06_Decision%20Trees.pdf))
* Decision Trees Lab 1 ([notebook](../labs/Decision%20Tree%20Lab))

####Resources:
* scikit-learn documentation: [Decision Trees](http://scikit-learn.org/stable/modules/tree.html)

**Installing Graphviz (optional):**
* Mac:
    * [Download and install PKG file](http://www.graphviz.org/Download_macos.php)
* Windows:
    * [Download and install MSI file](http://www.graphviz.org/Download_windows.php)
    * Add it to your Path: Go to Control Panel, System, Advanced System Settings, Environment Variables. Under system variables, edit "Path" to include the path to the "bin" folder, such as: `C:\Program Files (x86)\Graphviz2.38\bin`

---

### Session 7: Decision Trees Part 2 & Random Forests

* Decision Trees Lab 2 ([notebook](../labs/Decision%20Tree%20Lab))

####Resources:
* scikit-learn documentation: [Decision Trees](http://scikit-learn.org/stable/modules/tree.html)
* Quora: [How do random forests work in layman's terms?](http://www.quora.com/How-do-random-forests-work-in-laymans-terms/answer/Edwin-Chen-1)

---

### Session 8: K-Means Clustering Examples

* Clustering with K-Means ([slides](DAT13_lec08_Clustering.pdf))
* K-Means Lab ([notebook](http://nbviewer.ipython.org/github/ga-students/DAT_SF_13/blob/master/labs/intro_to_kmeans.ipynb))

####Resources:
Here are the animations we saw in class for how K-Means clustering works:
* [Visualizing K-Means](http://tech.nitoyon.com/en/blog/2013/11/07/k-means/)
* [Naftali Harris: Visualizing K-Means Clustering](http://www.naftaliharris.com/blog/visualizing-k-means-clustering/)
* [Introduction to Data Mining](http://www-users.cs.umn.edu/~kumar/dmbook/index.php) has a nice [chapter on cluster analysis](http://www-users.cs.umn.edu/~kumar/dmbook/ch8.pdf).
* The scikit-learn user guide has a nice [section on clustering](http://scikit-learn.org/stable/modules/clustering.html).

---

### Session 9: Logistic Regression

* Logistic Regression ([slides](DAT13_lec09_Logistic_Regression.pdf))
* Logistic Regression Lab / Solution ([notebook](http://nbviewer.ipython.org/github/ga-students/DAT_SF_13/blob/master/labs/DAT13-lab09-Solution.ipynb))

####Resources:
* For more on logistic regression, watch the [first three videos](https://www.youtube.com/playlist?list=PL5-da3qGB5IC4vaDba5ClatUmFppXLAhE) (30 minutes total) from Chapter 4 of An Introduction to Statistical Learning.
* UCLA's IDRE has a handy table to help you remember the [relationship between probability, odds, and log-odds](http://www.ats.ucla.edu/stat/mult_pkg/faq/general/odds_ratio.htm).
* Better Explained has a very friendly introduction (with lots of examples) to the [intuition behind "e"](http://betterexplained.com/articles/an-intuitive-guide-to-exponential-functions-e/).
* Here are some useful lecture notes on [interpreting logistic regression coefficients](http://www.unm.edu/~schrader/biostat/bio2/Spr06/lec11.pdf).

---

### Session 10: ROC Curves, AUC, & Imbalanced Classes

* Imbalanced Classes & ROC ([slides](DAT13_lec10_Class_Imbalance_ROC.pdf))
* Lab / Solution ([notebook](http://nbviewer.ipython.org/github/ga-students/DAT_SF_13/blob/master/labs/ROC%20curves%20and%20imbalanced%20classes.ipynb))

####Resources:
* scikit-learn has extensive documentation on [model evaluation](http://scikit-learn.org/stable/modules/model_evaluation.html).
* Rahul Patwari has two excellent and highly accessible videos on [Sensitivity and Specificity](https://www.youtube.com/watch?v=U4_3fditnWg&list=PL41ckbAGB5S2PavLIXUETzAmi5reIod23) (9 minutes) and [ROC Curves](https://www.youtube.com/watch?v=21Igj5Pr6u4&list=PL41ckbAGB5S2PavLIXUETzAmi5reIod23) (12 minutes).

---

### Session 11: Databases & Structured Query Language (SQL)

* Imbalanced Classes & ROC ([slides](DAT13_lec11_Databases_SQL.pdf))
* Lab: SQLite ([notebook](http://nbviewer.ipython.org/github/ga-students/DAT_SF_13/blob/master/labs/SQL_sqlite_pandas_update.ipynb))

####Resources:
* [What Every Data Scientist Needs to Know about SQL](http://joshualande.com/data-science-sql/)
* [Brandon's SQL Bootcamp](https://github.com/brandonmburroughs/sql_bootcamp)
* SQL tutorials from [SQLZOO](http://sqlzoo.net/wiki/Main_Page) and [Mode Analytics](http://sqlschool.modeanalytics.com/)

---

### Session 12: Recommender Systems

* Recommender Systems ([slides](DAT13_lec12_Rec_Sys.pdf))
* Python-recsys Lab ([notebook](../labs/Rec_sys_lab))

####Resources:
* [The Netflix Prize](http://techblog.netflix.com/2012/04/netflix-recommendations-beyond-5-stars.html)
* [Why Netflix never implemented the winning solution](https://www.techdirt.com/blog/innovation/articles/20120409/03412518422/why-netflix-never-implemented-algorithm-that-won-netflix-1-million-challenge.shtml)
* [Edwin Chen](http://blog.echen.me/2011/10/24/winning-the-netflix-prize-a-summary/) has a great, detailed breakdown of the techniques employed in attempting to win the Netflix Prize.
* [Visualization of the Music Genome Project](http://www.music-map.com/)
* [The People Inside Your Machine](http://www.npr.org/blogs/money/2015/01/30/382657657/episode-600-the-people-inside-your-machine) (23 minutes) is a Planet Money podcast episode about how Amazon Mechanical Turks can assist with recommendation engines (and machine learning in general).

---

###Session 13 Pre-work:
**The following preparation work is strongly recommended, in order to get the most out of class on Monday 4/20**

* Read Paul Graham's [A Plan for Spam](http://www.paulgraham.com/spam.html) and be prepared to **discuss it in class on Monday**. Here are some questions to think about while you read:
    * Should a spam filter optimize for sensitivity or specificity, in Paul's opinion?
    * Before he tried the "statistical approach" to spam filtering, what was his approach?
    * How exactly does his statistical filtering system work?
    * What did Paul say were some of the benefits of the statistical approach?
    * How good was his prediction of the "spam of the future"?
* Monday's class will depend heavily upon fundamental concepts of probability. Please be sure to review these materials before class:
    * **Basics of probability:** These [introductory slides](https://docs.google.com/presentation/d/1cM2dVbJgTWMkHoVNmYlB9df6P2H8BrjaqAcZTaLe9dA/edit#slide=id.gfc3caad2_00) (from the [OpenIntro Statistics textbook](https://www.openintro.org/stat/textbook.php?stat_book=os)) are quite good and include integrated quizzes. Pay specific attention to these terms: probability, sample space, mutually exclusive, independent.
    * **Conditional Probability:** This [5-minute video on conditional probability](https://www.youtube.com/watch?v=Zxm4Xxvzohk), or these [slides on conditional probability](https://docs.google.com/presentation/d/1psUIyig6OxHQngGEHr3TMkCvhdLInnKnclQoNUr4G4U/edit#slide=id.gfc69f484_00) will introduce the concept of conditional probability.
    * scikit-learn documentation: [CountVectorizer](http://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.CountVectorizer.html), [Naive Bayes](http://scikit-learn.org/stable/modules/naive_bayes.html)
* **Remember that the Midterm Homework 4 is due on Monday 4/20 by 6:00PM!**
* Also, you should be working on your project! **Your [first draft](https://github.com/ga-students/DAT_SF_13/blob/master/project/dat_project.md#april-26-first-draft-due) is due on April 26!**

###Session 13: Naive Bayes

* Naive Bayes ([slides](DAT13_lec13_Naive_Bayes.pdf))
* Naive Bayes Classification Lab ([notebook](http://nbviewer.ipython.org/github/ga-students/DAT_SF_13/blob/master/labs/DAT-SF-13%20Naive%20Bayes%20Lab.ipynb))

####Resources:
* Lecture supplement: Probability & Conditional Probability ([slides](DAT13_lec13_Probability_supplement.pdf))
* For more details on Naive Bayes classification, Wikipedia has two useful articles ([Naive Bayes classifier](http://en.wikipedia.org/wiki/Naive_Bayes_classifier) and [Naive Bayes spam filtering](http://en.wikipedia.org/wiki/Naive_Bayes_spam_filtering)), and Cross Validated has an excellent [Q&A](http://stats.stackexchange.com/questions/21822/understanding-naive-bayes).
* If you enjoyed Paul Graham's article, you can read [his follow-up article](http://www.paulgraham.com/better.html) on how he improved his spam filter and this [related paper](http://www.merl.com/publications/docs/TR2004-091.pdf) about state-of-the-art spam filtering in 2004.
* This [blog post](http://lesswrong.com/lw/774/a_history_of_bayes_theorem/) gives a great history of Bayes Theorem.
* [Here](http://www.cs.cmu.edu/~tom/mlbook/NBayesLogReg.pdf) is a very detailed comparison of Naive Bayes Classification with Logistic Regression. Warning: it is heavy on mathematics and notation.
* If you were intrigued by the sidebar regarding the frequentist vs. Bayesian approaches to statistical inference, pages number 40 - 44 of [this PDF](http://edepot.wur.nl/134085) may interest you.

---

###Session 14: Natural Language Processing

* Guest Speaker: Kirill Kireyev with an Introduction to Natural Language Processing ([slides](https://github.com/ga-students/DAT_SF_13/blob/master/lectures/DAT13_lec14_NLP_guest_speaker.pdf))
* NLP Lab on the vector space model and TF-IDF ([notebook](http://nbviewer.ipython.org/github/ga-students/DAT_SF_13/blob/master/labs/NLP-Lab/NLP-Lab-VSM-Solution.ipynb))

####A note on tf-idf

There are multiple different versions of IDF calculation used in practice:

1. The purist formula is (number of docs in corpus) / (number of docs in which term appears). However, that can lead to division by zero.
2. The standard way to avoid that issue is to add 1 to the denominator, as we saw during class. However, adding 1 to the denominator can yield negative IDF values for terms that occur in every doc in the corpus. Negative IDF values are also "wrong".
3. Lucene, the open source search engine that powers Elasticsearch, adds 1 to the denominator and then handles negative values by adding 1 to the result of log ( n_docs / (1 + df)), thus ensuring the IDF value is always positive ([lucene doc](https://lucene.apache.org/core/4_0_0/core/org/apache/lucene/search/similarities/TFIDFSimilarity.html))
4. scikit-learn takes yet another approach. The Tfidf functions in [scikit-learn](http://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.TfidfVectorizer.html) use idf = log ( n_samples / (1+df)), just as in our lab, _and_ "smooth" the n_samples and df values by adding 1 to each. This also avoids division by zero. The posted lab solution uses (4) and gets the same values as scikit-learn.

If you are interested in diving deeper, I highly recommend reading [this answer](http://stackoverflow.com/questions/18687879/error-in-computing-text-similarity-using-scikit-learn/18692538#18692538) and [this answer](http://stackoverflow.com/questions/12118720/python-tf-idf-cosine-to-find-document-similarity/12128777#12128777) from StackOverflow.

####Resources
* [NLP Extras](https://github.com/ga-students/DAT_SF_13/tree/master/labs/NLP-Extras): Document Classification Example ([notebook](http://nbviewer.ipython.org/github/ga-students/DAT_SF_13/blob/master/labs/NLP-Extras/NLP-Extra-Doc-Classification-Bayes.ipynb))
* [Natural Language Processing with Python](http://www.nltk.org/book/): free online book to go in-depth with NLTK
* [NLP online course](https://www.coursera.org/course/nlp): no sessions are available, but [video lectures](https://class.coursera.org/nlp/lecture) and [slides](http://web.stanford.edu/~jurafsky/NLPCourseraSlides.html) are still accessible
* [Stanford CoreNLP](http://nlp.stanford.edu/software/corenlp.shtml): suite of tools if you want to get serious about NLP
* Getting started with regex: [Python introductory lesson](https://developers.google.com/edu/python/regular-expressions) and [reference guide](https://github.com/justmarkham/DAT3/blob/master/code/99_regex_reference.py), [real-time regex tester](https://regex101.com/#python), [in-depth tutorials](http://www.rexegg.com/)
* [SpaCy](http://honnibal.github.io/spaCy/): a new NLP package

---

###Session 15: Support Vector Machines (SVMs)

* **Pre-work:** For students who enjoy digging into the underlying mathematical concepts, [this reading](http://www.cs.colostate.edu/~asa/pdfs/howto.pdf) details the math behind support vector machines. Some of the examples in the lecture slides are taken from this reading.
* Chetan will be leading this session, as Rob will be out of town on business travel.

---

###Session 16: Dimensionality Reduction (PCA & SVD)

* Dimensionality Reduction ([slides](DAT13_lec16_Dimensionality_Reduction.pdf))
* Principal Components Analysis Lab ([notebook](https://github.com/ga-students/DAT_SF_13/blob/master/labs/PrincipalComponentAnalysis.ipynb))

####Resources

* [This tutorial](http://www.cs.otago.ac.nz/cosc453/student_tutorials/principal_components.pdf) on Principal Components Analysis (PCA) includes good refreshers on covariance and linear algebra

---

###Session 17: Peer Feedback and Final Project Work Session

---

###Session 18: Guest Lecture on Time Series by Francesco Mosconi

* Time Series ([slides](DAT13_lec18_TimeSeries_Francesco.pdf))
* Time Series Visualization ([notebook](https://github.com/ga-students/DAT_SF_13/blob/master/labs/time_series_FM/Time%20Series%20Plots.ipynb))

####Resources

* There are many links to resources for going deeper into time series in Francesco's slides.


