<h1 align="center">
  <br>
  <img src="https://github.com/1Tatsumaru1/anomaly-detection/blob/master/img/shap1.png" alt="SHAP">
  <br>
  Anomaly detection
  <br>
</h1>

<h4 align="center">
  Based on this 
  <a href="https://www.kaggle.com/competitions/home-credit-default-risk/data" target="_blank">Kaggle datasets</a>.
</h4>

<p align="center">
  <a href="#description">Description</a> •
  <a href="#contents">Contents</a> •
  <a href="#credits">Credits</a> •
  <a href="#links">Links</a>
</p>

## Description

This project was part of my IA Engineering course at OpenClassrooms. 
The aim was to :<br>
* Analyse the past credit and risk information

![screenshot](https://github.com/1Tatsumaru1/anomaly-detection/blob/master/img/ext_src3.png)

* Merge the datasets together and create new variables through various methods of feature engineering (1-hot, polynomial, aggregation, etc.) in order to find explanatory factors for credit default

* Engineer the decision metrics by balancing precision and recall (F3 has been used here)

* Built a decision model that maximize the ROC AUC and chosen metric (F3) by confronting various classification algorithms (boosting tree, random forest, etc.) and adjusting the decision threshold

* Develop an application that takes as input only the minimum required information from a customer, outputs the decision (whether or not to issue a credit for this customer), and provide detailed explanation about the most influential variables (the SHAPly value has been used here)

![screenshot](https://github.com/1Tatsumaru1/anomaly-detection/blob/master/img/shap2.png)


## Contents

* **EDA and Model development** (Jupyter notebook) : A detailed (and lengthy) EDA about all provided datasets, the merging and feature engineering process, as well as the model comparison and selection
* **Application** (Jupyter notebook) : A demo application that takes various CVS files as input and displays the results directly in the notebook

## Credits

This project makes use of the following packages:

- [Pandas](https://pandas.pydata.org/)
- [Numpy](https://numpy.org/)
- [Scikit-learn](https://scikit-learn.org/stable/index.html)
- [SHAP](https://shap.readthedocs.io/en/latest/index.html)
- [Imblearn](https://pypi.org/project/imblearn/)

## Links

> <a href="https://anthony.ledouguet.com"><img src="https://github.com/1Tatsumaru1/azure_reco_api/blob/main/img/world.png" alt="website" width="20" /> anthony.ledouguet.com</a><br>
> <a href="https://github.com/1Tatsumaru1"><img src="https://github.com/1Tatsumaru1/azure_reco_api/blob/main/img/github.png" alt="github" width="20" /> GitHub</a><br>
> <a href="https://www.linkedin.com/in/anthony-le-douguet/"><img src="https://github.com/1Tatsumaru1/azure_reco_api/blob/main/img/linkedin.png" alt="linkedin" width="20" />
LinkedIn</a>
