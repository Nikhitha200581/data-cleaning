 Data Cleaning and Preprocessing - Task 1

Objective

The objective of this task is to clean and preprocess a raw dataset by handling missing values, removing duplicates, standardizing data formats, and preparing the dataset for analysis.

 Dataset Used

Netflix Movies and TV Shows Dataset

Tools Used

* Python
* Pandas
* Jupyter Notebook

 Data Cleaning Steps Performed

 1. Loaded the Dataset

* Imported the dataset using Pandas.

 2. Checked Dataset Information

* Used "df.info()" to understand the structure of the dataset.
* Identified column names, data types, and missing values.

 3. Handled Missing Values

* Replaced missing values in:

  * 'director' column with "Unknown"
  * 'cast' column with "Not Available"
  * 'country' column with "Unknown"

 4. Removed Duplicate Records

* Used "drop_duplicates()" to remove duplicate rows.

 5. Standardized Text Data

* Removed unnecessary spaces using "strip()".
* Converted text into a consistent format using "title()".

 6. Converted Date Format

* Converted the 'date_added' column into datetime format using "pd.to_datetime()".

 7. Renamed Column Headers

* Converted column names to lowercase.
* Replaced spaces with underscores.

 8. Verified Data Types

* Checked and corrected data types where required.

 9. Exported Cleaned Dataset

* Saved the cleaned dataset as "cleaned_netflix_dataset.csv".

 Outcome

The dataset was successfully cleaned and prepared for further analysis and visualization. Missing values, duplicates, and formatting inconsistencies were handled to improve data quality.

Files Included

* netflix_titles.csv (Raw Dataset)
* cleaned_netflix_dataset.csv (Cleaned Dataset)
* task-1.ipynb
