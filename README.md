# Restaurant Reviews - UTS

## Dataset
Thanks to [Harshit Joshi on Kaggle](https://www.kaggle.com/hj5992/restaurantreviews)

## Requirements

- Check [requirements.txt](https://github.com/jacenyang/restaurant-reviews-uts/blob/master/requirements.txt) and make sure those packages are installed.
- Download stopwords from ntlk by running the script below.
```sh
import nltk
nltk.download('stopwords')
```

## Algorithms

- Multinomial Naive Bayes
```sh
Accuracy of prediction is 77.67%.
Precision of prediction is 0.78.
Recall of prediction is 0.77.
```
- Bernoulli Naive Bayes
```sh
Accuracy of prediction is 77.0%.
Precision of prediction is 0.76.
Recall of prediction is 0.78.
```
- Logistic Regression
```sh
Accuracy of prediction is 76.67%.
Precision of prediction is 0.8.
Recall of prediction is 0.71.
```
