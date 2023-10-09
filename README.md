# Premier-League-Club-Investment-Analysis
An Exploratory Data Analysis (EDA) Project using Python

Domain: Sports (Football)

## OBJECTIVE 

The purpose of this exploratory data analysis is to identify potential investments in one of the top-performing English Premier League clubs. Several established clubs are already owned by competitors, so the management of the firm is seeking to identify clubs with great potential for future success.

## DATA

The dataset comprises crucial information about all the clubs that have participated in premier league tournaments. Here is a data dictionary that outlines the information we have about the clubs and their performance.

### DATA DICTIONARY:

  ⚽ Club: Name of the football club

  ⚽ Matches: Number of matches the club has played in the Premier League

  ⚽ Wins: Number of matches won by the club in the Premier League

  ⚽ Loss: Number of matches lost by the club in the Premier League

  ⚽ Clean Sheets: Number of matches in which the club has prevented the opposing side from scoring

  ⚽ Draws: Number of matches drawn by the club in the Premier League

  ⚽ Team Launch: Year in which the club was founded

  ⚽ Winners: Number of times the club has won the Premier League

  ⚽ Runners-up: Number of times the club has finished as runners-up in the Premier League

  ⚽ lastplayed_pl: Year in which the team last played in the Premier League

## KEY LEARNINGS:

➡️ **Data cleaning** is the process of identifying and correcting or removing errors, inconsistencies, and inaccuracies in a dataset. Some variables may need **data type conversion**, **converting the existing data to a particular forma**t, and not all null values need to be replaced with mean/median/mode. We need to **treat the null values based on domain knowledge** and formulate a default value.

Reference from the project: Winners and Runner column (null values are treated based on domain knowledge i.e. default value as zero), last_played (formatted to ‘YYYY’).  

➡️ **Feature engineering** refers to the process of using domain knowledge to select and **transform the raw data into relevant information that can be used in the analysis.** Some variables might be not relevant which gets transformed.

Reference from the project: Win Rate, Loss Rate, Drawn Rate, Clean Sheet Rate, Average No. of Goals from Wins, Loss, Draws, Clean Sheets, Goals and Matches Played.

➡️ **Outliers** are unusual values in your dataset which can distort statistical analyses. We identify and remove them during EDA. But, that’s not always the case.                                                      **Removing the outliers might not provide us with the relevant insight we are looking for.**

Reference from the project: The outliers are the ones that showed the clubs that are significant from others, with the high potential to win.

➡️ We built a **framework by assigning scores** to each club from the inference obtained during EDA, which led us to a conclusion. To **avoid being deceived by the weightage result**, a **thorough examination of the whole dataset** should be done by checking if there might be any **columns or correlations to re-consider in the dataset.**

Reference from the project: We recommended the second highest team as the first team was inconsistent and not currently active which was discovered after closely examining the last_played column (contains the information when it played last).

## CONCLUSION:

We concluded the analysis by recommending to invest in **LEICESTER CITY**!🏆

They have a proven track record of **success and consistency**. We believe that this club is well-positioned for success in the future. 

Please let me know your thoughts in the comments. 

THANK YOU! :)
