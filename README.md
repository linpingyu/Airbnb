# Airbnb Seattle

This repository contains a notebook which digs a little bit into airbnb market in Seattle, WA. Within the notebook, I did a basic study of airbnb locations, market growth, and major airbnb attributes, mainly focusing on data visualization, with a little machine learning technique to make recommendations. 

**Motivation**

Sharing economy is heated recently, Airbnb is one of the bigges leaders. [Inside Airbnb](http://insideairbnb.com/about.html) has provided wonderful data scrapped from Airbnb. The data has each of the listings information in major cities across the world. By digging in those data, we can discover some interesting facts, and study the growth of Airbnb. 

**Summary**

Airbnb grew exponentially during the past few years. People seems to be benefit from this sort of sharing economy as a new concept. But there are some potential issue that Airbnb may not want you to see or know. Some of them can be find [here](http://insideairbnb.com/index.html).

**Files**
1. `airbnbSeattle.ipynb`
  The notebook created for analysis, visualization and etc.
2. `seattle`
  Folder that contains the datasets of Seattle. The one used intensively in the notebook is `seattle/listings_new.csv` which is last updated on Nov 15, 2018. You can download the latest version from [here](http://insideairbnb.com/get-the-data.html).
3. `boston`
  Folder that contains the datasets of Boston. You can change the directory in the notebook to get some interesting facts about Boston Airbnb Market as well.
  
**Libraries**

1. `Numpy` & `Pandas` for essential data manipulation
2. `Matplotlib.pyplot` & `Seaborn` for essential data visualization
3. `Sklearn`: `feature_extraction.text.TfidfVectorizer` & `metrics.pairwise.linear_kernel` for modeling


**Reference** 

One good Kaggle notebook: https://www.kaggle.com/rdaldian/airbnb-content-based-recommendation-system/notebook
