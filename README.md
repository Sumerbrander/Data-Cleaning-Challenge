# FIFA '21 Data Cleaning Challenge
## This is a Data Cleaning Challenge organized by [Promise Nonso](https://twitter.com/PromiseNonso_) and [Victor Somadina](https://twitter.com/vicSomadina).



<div align="center">
  <img src="https://github.com/toheebolamilekn/fifa21_data_cleaning_challenge/blob/main/fifa21_logo.jpg" width="1000" height="400"/>
</div>

---
### Introduction
- According to [Wikipedia](https://en.wikipedia.org/wiki/Data_cleansing), Data cleaning or cleansing is the process of detecting and correcting (or removing) corrupt or inaccurate records from a record set, table, or database and refers to identifying incomplete, incorrect, inaccurate or irrelevant parts of the data and then replacing, modifying, or deleting the dirty or coarse data. Data cleansing may be performed interactively with data wrangling tools such as Python, R, SQL, Microsoft Excel, Power Query in Excel or in Power BI or as batch processing through scripting or a data quality firewall.

- After cleansing, a data set should be consistent with other similar data sets in the system. The inconsistencies detected or removed may have been originally caused by user entry errors, by corruption in transmission or storage, or by different data dictionary definitions of similar entities in different stores. Data cleaning differs from data validation in that validation almost invariably means data is rejected from the system at entry and is performed at the time of entry, rather than on batches of data.

- The actual process of data cleansing may involve removing typographical errors or validating and correcting values against a known list of entities. The validation may be strict (such as rejecting any address that does not have a valid postal code), or with fuzzy or approximate string matching (such as correcting records that partially match existing, known records). Some data cleansing solutions will clean data by cross-checking with a validated data set. A common data cleansing practice is data enhancement, where data is made more complete by adding related information. For example, appending addresses with any phone numbers related to that address. Data cleansing may also involve harmonization (or normalization) of data, which is the process of bringing together data of "varying file formats, naming conventions, and columns", and transforming it into one cohesive data set; a simple example is the expansion of abbreviations ("st, rd, etc." to "street, road, etcetera").
---
### About the dataset
- The raw dataset was sourced from [Kaggle](https://www.kaggle.com/datasets/yagunnersya/fifa-21-messy-raw-dataset-for-cleaning-exploring/code) via web scrapping from sofifa.com which can also be access here [fifa21_raw_data_v2](https://github.com/toheebolamilekn/fifa21_data_cleaning_challenge/blob/main/fifa21_raw_data_v2.csv). It consists of all information concerning football players such as player names, age, clubs, nationality, wages, positions, performance ratings, height & weight etc. The raw dataset before cleaning consists of 18979 rows and 76 columns. The cleaned dataset set consists of 18979 rows and 72 columns.
#### Note: python rows and columns counting start from zero (0) not one (1).
---
### Objectives
- The main objective of this data challenge was to learn, improve skills and network with like-mind and get to build a worthy-portfolio project. 
- Other specific objectives are stated below;
 1. Ensure that all the columns have the correct data type.
 2. Numerical columns should be in a format suitable for further calculations and analysis.
- In order to achieve the aforementioned objectives, we are to;
 1. Ensure correct data types, 
 2. Correct inconsistent naming of column and/or values,
 3. Check for null entries and missing entries, 
 4. Remove unnecessary characters as well as irrelevant column.
---
### Process
- The step by step process were perfectly explained together with the cleaning process in Python Jupiter Notebook which can be found uploaded above named [FIFA '21 Messy Raw Dataset Cleaning Challenge]
