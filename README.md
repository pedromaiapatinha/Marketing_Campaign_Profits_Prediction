# Marketing Campaign Profits Prediction using several Supervised Learning Models
  
## Table of Content
  * [Overview](#Overview)
  * [Business Understanding](#Business-Understanding)
  * [The Challenge](#The-Challenge)
  * [Models](#Models)
  * [Installation](#Installation)
  * [Directory Tree](#Directory-Tree)
  * [Technologies Used](#technologies-used)
  * [Team](#team)
  * [Credits](#credits)

## Overview
This is an academic project with fictional data and it was developed under the scope of Machine Learning curricular unit at NOVA IMS.

## Business Understanding
LaGoste Stores is a company that operates in the fashion, sports and luxury sectors. Their products offer consists in five categories: Sneakers, Rackets, T-Shirts, Watches and Hats, each one divided in Premium Brand and Mainstream Articles. All the products can be purchased in physical stores, in their website or ordered through their quaterly catalogs. Currently, they sell their products to more than one million consumers every year and they have around 300 000 registered customers

## The Challenge
In spite of having solid revenues and a healthy bottom line for the past five years, the company's profit growth perspectives for the next two years are not optimistic. In order to change those perspectives the company is outlining some strategic initiatives. One of the strategies being studied and that will play an important role in the profit growth is the efficiency of the marketing campaigns.

The marketing department is planning a direct campaign aiming the sell of a new product, as this campaign has costs the Marketing department has already carried out pilot campaign where they contacted 2500 clients and took note if the client accepted (bought the new product) or not the campaign. 12,5% of the customers contacted has accepted the campaign which lead the company to a negative profit of around 3750€.

Our job is to build a predictive model for a dependent variable representing Customers that have higher potential of answering positively to the new product from the direct marketing campaign. To be able to build a good predictive model, we'll study several models and access which is the best one.

In the end, we will calculate an approximation of the profit that the company will have after contacting only the customers that have the biggest potential to buy the new product, saving the costs of contacting customers that wouldn't buy it. The cost per contact is 4€ and the revenue per accepted offer is 20€.

## Objective
Build a predictive model that will produce the highest profit for the next direct marketing campaign of the company – the sixth campaign this year that is scheduled for next month. The campaign aims at selling a new product to the customer database (potential of 250,000 customers).

## Models
  * Random Forest
  * Decision Tree
  * Logistic Regression
  * Support Vector Machine
  * Neural Network

## Installation
The Code is written in Python 3.7. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```

## Directory Tree 
```
├── PredictiveModel.ipynb
├── marketing_dataset.xlsx
├── README.md
└── requirements.txt
```

## Technologies Used

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)


## Team
[![Domingos Lemos]()]() |
[![Maria Branco]()]() |
[![Pedro Patinha]()]() |

## Credits
Team work made this long project possible, as we performed a long and detailed data processing. Besides having time constrains and being at the beginning of our learning curve, we nailed it.
