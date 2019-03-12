# Wireshark-Packet-Analysis
The objective of this project is to perform packet analysis on Wireshark packets. In order to do this, we will leverage some of Python's libraries like Scapy, Pandas and Seaborn. 

![alt-img]("https://github.com/bedangSen/Wireshark-Packet-Analysis/blob/master/Images/Port%20Destination.png")
![alt-img]("https://github.com/bedangSen/Wireshark-Packet-Analysis/blob/master/Images/Address%20Destination.png")
      

## Getting Started 

1. Sign up for an [IBM Cloud Account](https://console.bluemix.net/registration/)
1. Login to [Watson Studio](https://www.ibm.com/cloud/watson-studio)

## Running the Jupyter notebook

### 1. Sign up for Watson Studio

Sign up for IBM's [Watson Studio](https://dataplatform.ibm.com/).

### 1. Create a new Project

> Note: By creating a project in Watson Studio a free tier `Object Storage` service will be created in your IBM Cloud account. Take note of your service names as you will need to select them in the following steps.

* On Watson Studio's Welcome Page select `New Project`.

* Choose the `Data Science` option and click `Create Project`.

* Name your project, select the Cloud Object Storage service instance and click `Create`

## 1. Import notebook to Watson Studio

* Create a **New Notebook**.

* Import the notebook found in this repository

* Give a name to the notebook and select a `Python 3.5` runtime environment, then click `Create`.

## 6. Follow the steps in the notebook

The steps in the notebook should allow you to understand how to download the dataset, create a model that uses Naive Bayes Classification and then visualize it using a Confusion Matrix and Heat map. 

Finally you should be able to test the model and check it's accuracy.

## Resources 
+ [Unofficial guide to using Scapy](https://theitgeekchronicles.files.wordpress.com/2012/05/scapyguide1.pdf)
+ [Seaborn Documentation](https://seaborn.pydata.org/)
+ [Learning Packet Analysis with Data Science](https://secdevops.ai/learning-packet-analysis-with-data-science-5356a3340d4e)
+ [Cyber Talents - Packet Abomination Challenge](https://cybertalents.com/challenges/forensics/packet-abomination)
