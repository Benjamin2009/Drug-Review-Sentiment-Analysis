![](https://www.fda.gov/files/styles/main_image_1/public/How_to_Buy_Medicines_Safely_From_an_Online_Pharmacy_1600x900.png?itok=y5olqkV2)

# Drug Review Sentiment Analysis

### Goal

We have a dataset that provides patient reviews on specific drugs, which were obtained by crawling online pharmaceutical review sites. The objective is to distinguish a positive review from a negative one based on review text analysis.

We will performance some exploratory data analysis to gain useful insights. Since we are dealing with patient review, we are interested in sentiment analysis. We will attempt to predict whether a review is positive or negative using sentiment analysis and a machine learning model, Light Gradient Boosting Machine (LightGBM).

### Dataset

The Drug Review Dataset is available from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Drug+Review+Dataset+%28Drugs.com%29). This Dataset provides patient reviews on specific drugs along with related conditions. There are six features: 

- **drugName:** name of drug 
- **condition:** the condition the patient is suffering from
- **review:** patient review for the drug
- **rating:** 10-star rating for the drug, reflecting the overall patient satisfaction
- **date:** date of review entry 
- **usefulCount:** number of users who found the review useful

### Python Libraries

Data wrangling and exploration:
- Pandas
- NumPy
- qgrid
- ipywidgets

Data Visualization:
- Matplotlib
- Seaborn
- wordcloud

Text Preprocessing:
- NLTK
- TextBlob

Modeling:
- sklearn
- lightgbm

---

Please read the notebook:

[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/Benjamin2009/Drug-Review-Sentiment-Analysis/blob/main/Drug_Review_Sentiment_Analysis.ipynb)
