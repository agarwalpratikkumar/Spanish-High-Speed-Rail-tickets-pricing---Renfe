# Spanish-High-Speed-Rail-tickets-pricing - Renfe
This is a Spanish High Speed Train Service (Renfe AVE) tickets pricing monitoring system. 
Ticket pricing changes based on demand and time, and there can be significant difference in price. Keeping this in mind in this work Exploratory Data Analysis (EDA) has been performed and data has been visualized using matplotlib and seaborn.
After performing some feature engineering a machine learning model has been trained which could predict the ticket price.
The work can be proved beneficial for the local people and can help them getting some estimate of the ticket price. 
Users can set up alarms using an email, choosing an origin and destination (cities), time (date and hour range picker) choosing a price reduction over mean price.
<br>
The dataset can be downloaded from the following kaggle website.
<br>
https://www.kaggle.com/thegurus/spanish-high-speed-rail-system-ticket-pricing
<br>
In this work we have used Boosting method. 
# Boosting builds multiple incremental moedels to decrease the bias while keeping the variance small. 
<br>We can get some brief idea about Gradient Boosting from the following link: <br> 
https://machinelearningmastery.com/gentle-introduction-gradient-boosting-algorithm-machine-learning/
<br>
To understand LightGBM: https://lightgbm.readthedocs.io/en/latest/


```
In order to open '.ipynb' file follow below step:

1. search 'Google Colab' on a web browser (E.g: Google Chrome).
2. open 'Google Colab'. (https://colab.research.google.com/notebooks/welcome.ipynb)
3. Goto File option -> select upload notebook option -> Upload my '.ipynb' file. 
4. All my work should visible now.


Now, If you want to run the code by yourself. First you have to upload the dataset. 

Steps to upload the dataset :

1. Open the left Pane. (You will see '>' sign at the corner beside the import statements)
2. Click on the 'Files' tab.
3. Click on 'UPLOAD' button. Now you can upload. A pop-up will generate after you select the required file, just click 'Ok'.
4. You will see below that your file is uploading. Wait for the orange circle to complete.
5. Now you could able to run my code cell by cell.

```
