# Finlatics-Banking-Project
Materials related to the Finlatics capstone project

This was a capstone project I did for the finlatics Data Science Program with Python. The data provided was related to the direct marketing campaigns of a Portuguese banking institution. I carried out data preprocessing, cleaning and preparation. Then carried out some exploratory data analysis and finally investigated the factors that might lead to increased term deposit subscription, if any. There were a total of 18 questions to be answered from the dataset.

### Data
The data can be found in the "**banking_data.csv**" file. The description of the variables present is in the "**Banking data description.docx**" file. It consists of 45216 rows and 19 columns.

### Data preprocessing and cleaning
I removed missing value rows (There were a total of 6 such rows, so it could be removed without influencing the data significantly) from martial_status and education columns. Then I dropped redundant and repeated columns. The columns dropped were marital and day_month. Some columns were renamed. 

### Exploratory data analysis
I looked at the distribution of each of the variable, looked at their key statistical info (quartiles, mean, mode, standard deviation, etc.), kurtosis and skew and presence of outliers. Distribution plots of a couple of variables

![agehistogram](https://github.com/SarkarRohan1/Finlatics-Banking-Project/assets/82277560/d196bbe2-c88b-489c-8bb5-a6c8a95633cf)

![educationbarplot](https://github.com/SarkarRohan1/Finlatics-Banking-Project/assets/82277560/8f4a6f3c-59c2-4660-97bb-7acc6f5d0157)


