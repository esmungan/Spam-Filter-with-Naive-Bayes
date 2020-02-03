## SMS Spam filter with Multinomial Naive Bayes Algorithm
This project is done as a part of Conditional Probability class on DataQuest.

* **Concepts learned:** Naive Bayes Algorithm, Pandas-Numpy usage, Impact of different data cleaning schemes on the model's outcome
* **Main challenges:** Underflow of the probability values for long texts, Finding vectorized solutions, Understanding the difference between the results for different cleaning methods.

The goal of this project is to determine whether an SMS message is spam or not with an accuracy greater than 80%.To achieve this purpose, a multinomial naive Bayes model is employed.

The data used in this project is from [UCI machine learning repository](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection). It contains English, real and non-enconded messages, labeled according being legitimate (ham) or spam.
