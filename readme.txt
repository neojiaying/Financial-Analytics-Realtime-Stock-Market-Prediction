For Folder: For User (PFE)

Please run the files according to the procedure.

1. Automated 60days Scrapper.ipynb (This is to scrape 60 days of tweets of a particular stock.)
Note: Please input the stock you want to scrape in the input box (E.g. PFE)
A final.csv file will be exported into the same folder when the code executes successfully. 

2. Improved LSTM Model.ipynb
The code here wil read in final.csv and perform analysis using LSTM. After the code runs finish, you can see the RMSE of the LSTM model on the actual predicted price. We also normalised the predicted price at the end so that it can be an input into the dashboard.
Note: Please input how many days you want to forecast in the input box (Enter a number from 1 to 3)
PFE_LSTM_Dashboard.csv and LSTM_PFE_NormalisedPred.csv files will be exported into the same folder when the code executes successfully. These 2 files are used in the dashboard.

If user wants to see how accurate the forecast were, run this file a few days later after the actual price of the dates user has forecasted comes out.
The code here will read in PFE_LSTM_Dashboard.csv and compare actual prices scrapped from yahoo finance with the predicted prices that was done previously by LSTM.

3. Validate Final Outcome.ipynb
Note: Please change the ticker in the yahoo finance code if you are not using PFE.

For Folder: EDA and Testing
The files inside were used for our own testing purposes and EDA, user does not have to run these.