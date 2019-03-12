# Wireshark-Packet-Analysis
The objective of this project is to perform packet analysis on Wireshark packets. In order to do this, we will leverage some of Python's libraries like Scapy, Pandas and Seaborn. 

<img src="https://github.com/bedangSen/Wireshark-Packet-Analysis/blob/master/Images/wireshark.png?raw=true" width="500" alt="Wireshark Packet Analysis" align="middle">
<img src="https://github.com/bedangSen/Wireshark-Packet-Analysis/blob/master/Images/Address%20Destination.png?raw=true" width="600" alt="Destination Address Traffic" align="middle">
<img src="https://github.com/bedangSen/Wireshark-Packet-Analysis/blob/master/Images/Port%20Destination.png?raw=true" width="600" alt="Destination Port Traffic" align="middle">

## Getting Started 

1. Sign up for an [IBM Cloud Account](https://console.bluemix.net/registration/).
1. Login to [Watson Studio](https://www.ibm.com/cloud/watson-studio).

## 1. Running the Jupyter notebook

### 1. Sign up for Watson Studio

Sign up for IBM's [Watson Studio](https://dataplatform.ibm.com/).

### 2. Create a new Project

> Note: By creating a project in Watson Studio a free tier `Object Storage` service will be created in your IBM Cloud account. Take note of your service names as you will need to select them in the following steps.

* On Watson Studio's Welcome Page select `New Project`.

* Choose the `Data Science` option and click `Create Project`.

* Name your project, select the Cloud Object Storage service instance and click `Create`.

## 2. Import notebook to Watson Studio Project

* Create a **New Notebook**.

* Import the notebook found in this repository.

* Give a name to the notebook and select a `Python 3.5` runtime environment, then click `Create`.

## 3. Import dataset to Watson Studio Project

* Click on `Add to Project` and select `Data`.

* A panel should appear on the right where you can drag and drop your data assets. 

* Download the Packet file from the repository and drag and drop it onto the panel. 

* You can now use it in your Watson notebook. 

## 4. Follow the steps in the notebook

## Resources 
+ [Unofficial guide to using Scapy](https://theitgeekchronicles.files.wordpress.com/2012/05/scapyguide1.pdf)
+ [Seaborn Documentation](https://seaborn.pydata.org/)
+ [Learning Packet Analysis with Data Science](https://secdevops.ai/learning-packet-analysis-with-data-science-5356a3340d4e)
+ [Cyber Talents - Packet Abomination Challenge](https://cybertalents.com/challenges/forensics/cypher-anxiety)
