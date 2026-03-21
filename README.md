# ICSS Final Project: Topic Modeling of Newspaper Articles on Climate Change/Activism over Time

This project is divided into three main parts:

1. [Data Collection & Preprocessing](01_data_collection.ipynb)  
   Retrieval and basic processing of data from The Guardian and New York Times API.

2. [Exploratory Data Analysis (EDA)](02_EDA.ipynb)  
   Exploration of article volume over time and by section.

3. [Model Application](03_model_application.ipynb)  
   Application of BERTopic, sentiment analysis, and NER.

All collected, preprocessed and embedded data as well as fitted topic models are stored in the [data](data) folder. Further, note the attached [Project Report](Project_report.pdf) and [Declaration of Authorship](Declaration_of_authorship.pdf). The according video demonstration is available [here](https://cloud.uni-konstanz.de/index.php/f/227241252).

All dependencies from the used environment can be found in [requirements.txt](requirements.txt) and installed using "pip install -r requirements.txt". 

---
### Data Sources:

NYT API: https://developer.nytimes.com/docs/articlesearch-product/1/overview

The Guardian API: https://open-platform.theguardian.com/

