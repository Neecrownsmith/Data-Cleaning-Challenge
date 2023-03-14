# FIFA 2021 Data Cleaning Project
This project was completed as part of a data cleaning challenge in the data tech space. The goal of the challenge was to clean a messy and raw FIFA 2021 dataset containing 18979 rows and 77 columns. The dataset was sourced from Kaggle and included information which can be found in the 'fifa data dictionary.txt' file.

# Tools Used
For this project, I used Python and the Pandas library to clean the dataset. I used various techniques such as data type conversions, replacing missing values, and sorting contract data to clean and organize the dataset. I also renamed some columns for clarity and consistency.

# Files
The repository includes the following files:
* fifa21 raw data v2.csv: The original dataset downloaded from Kaggle.
* Cleaned FIFA 2021 data.csv: The cleaned dataset produced as part of this project.
* fifa data dictionary.txt: The file explaining the information in the raw data.
* DataCleaning Challenge.ipynb: A Jupyter notebook containing the Python code used to clean the dataset.
* README.md: This README file.

# Cleaning Steps
The cleaning process involved several steps, including:

* Removing special characters from some columns and converting their data types to integers.
* Checking for unique values in certain columns.
* Converting the 'Hits' column to a numeric data type and filling missing values with zeros.
* Sorting contract data into three separate columns: contract start date, contract end date, and contract type.
* Renaming some columns for clarity and consistency.

# Conclusion
This project allowed me to practice my data cleaning skills using Python and Pandas. I really thank the organisers of this challenge for this opportunity. The cleaned dataset can be used for further analysis and modeling.
