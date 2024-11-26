Import mwclient and time library to get data from wkipedia site wit the use of an API
Assign extracted data to 'revs' list
Create a sentiment-analysis pipeiine to train revs into negative and positive sentiments
Write a function to append sentiment score to sentiments list
WRite mean function to  calculate average of a list
Assign data to 'edits_df' dataframe
Generate a range of dates from the start of 2014 to present day and assign to dates
Reindex edits_df dataframe to generated range of dates
Calculate rolling average of edits_df and assign to rolling_edits df
Drop NAN values from rolling_edits dataframe
Convert rolling_edits df to wikipedia csv file
Import yfinance and os libraries
Get the stock price data for ethereum against the dollar using yahoo finance API aand assign to eth dataframe
Explorative data analysis: drop columns that are not needed for model building
Read wikipedia csv file to wiki dataframe and parse dates
Merge wiki dataframe with eth dataframe
Assign shifted 'close' column prices to just created tomorrow column
Assign categorical data(1/0) to target; if 'tomorrow' column > 'close' column
Import RandomForestClassifier model, group data into train and test sets, indicate predictor columns and fit RFC model accordingly to train data
Use precision score model, predict test data, and convert to series.
Write function to combine actual and predicted values
Write a backtest function to get predictions for as many rows  as possible while respecting the order of data
Import XGBoost to make predictions to backtest function on eth dataset on specified predictors
Write compute_rolling function to calculate rolling averages and create new features for different time horizons
