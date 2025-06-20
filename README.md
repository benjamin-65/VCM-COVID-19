# VCM-COVID-19

This code includes applying a varying coefficient model or VCM to monthly COVID-19 hospitalization data. Multiple models were compared to determine which would predict the monthly hospitalization rate most accurately. Leave-one-out cross-validation was used to ensure that prediction was occuring on a new data point unseen by the model. Ultimately, the VCM performed better than other models like linear and random forest indicating that when the coefficients of a model vary based on time (months in this case), we are able to better predict new values of hospitalization rates. 
