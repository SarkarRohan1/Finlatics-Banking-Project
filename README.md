# Finlatics-Banking-Project
Materials related to the Finlatics capstone project

This was a capstone project I did for the finlatics Data Science Program with Python. The data provided was related to the direct marketing campaigns of a Portuguese banking institution. I carried out data preprocessing, cleaning and preparation. Then carried out some exploratory data analysis and finally investigated the factors that might lead to increased term deposit subscription, if any.

### Data
The data can be found in the "**banking_data.csv**" file. The description of the variables present is in the "**Banking data description.docx**" file. It consists of 45216 rows and 19 columns.

### Data preprocessing and cleaning
I removed missing value rows (There were a total of 6 such rows, so it could be removed without influencing the data significantly) from martial_status and education columns. Then I dropped redundant and repeated columns. The columns dropped were marital and day_month. Some columns were renamed. 
