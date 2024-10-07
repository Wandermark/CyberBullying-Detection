# CyberBullying-Detection

I'm working with the [dataset from Kaggle](https://www.kaggle.com/datasets/sayankr007/cyber-bullying-data-for-multi-label-classification/data?select=final_hateXplain.csv) which contains annotated social media comments specifically curated for the analysis and detection of cyberbullying.

The data is labeled across multiple categories including race, religion, gender, sexual orientation, and miscellaneous attributes. Each comment has been carefully reviewed and annotated by multiple annotators to ensure accuracy and reliability.

My goal is to train NLP models which would be able to successfully detect comments which consist of hatespeech and offensive language. My north star is F1 Metric 0.7.

# About Dataset

This dataset contains annotated social media comments specifically curated for the analysis and detection of cyberbullying. The data is labeled across multiple categories including race, religion, gender, sexual orientation, and miscellaneous attributes. Each comment has been carefully reviewed and annotated by multiple annotators to ensure accuracy and reliability.

**final_hateXplain.csv**

Different Label Categories and Their Respective Values:

- Race: no_race, african, arab, asian, caucasian, hispanic, indian, indigenous
- Religion: nonreligious, buddhism, christian, hindu, islam, jewish
- Gender: no_gender, men, women
- Sexual Orientation: no_orientation, asexual, bisexual, heterosexual, homosexual
- Miscellaneous: none, disability, economic, minority, other, refugee
