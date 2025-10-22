# Task1_Data-Cleaning
##Task 1: Data Cleaning
Data Cleaning and Preprocessing Summary (Mall_Customers Dataset):
    In this task, I performed data cleaning and preprocessing on the Mall_Customers dataset to prepare it for analysis.
The following steps were completed:

* Removed duplicates to ensure data integrity.
* Handled missing values using appropriate replacements or removal.
* Standardized categorical values (e.g., gender values formatted consistently as Male and Female).
* Cleaned column names (converted to lowercase, replaced spaces with underscores).
* Verified and corrected data types (e.g., numerical columns as integers or floats).
* Formatted data for better readability and analysis readiness.

  Interview Questions and Answer:

  1. What are missing values and how do you handle them?
      Missing values occur when no data is stored for a variable in a record.They can be handled by Using “Not Available” or similar text (for categorical data).
2. How do you treat duplicate records?
      Duplicate records are identical rows that appear multiple times. They can be removed using Excel’s Remove Duplicates feature or in Python with drop_duplicates() to ensure each entry is unique.
3. What is the difference between dropna() and fillna() in Pandas?
* dropna() → Removes rows or columns with missing (NaN) values.
* fillna() → Fills missing values with a specific value (like mean, median, or 0).
4. What is outlier treatment and why is it important?
      Outliers are extreme values that differ from the rest of the data.They are important to handle because they can skew results and affect analysis.Common treatments include removing them, capping them, or using transformation methods like log-scaling.
5. Explain the process of standardizing data.
      Standardizing means bringing data into a common format.
For example:

    * Converting all text to lowercase.
    * Using the same units or date format.
    * Ensuring consistent naming (e.g., “Male” and “Female” instead of “M”/“F”).
6. How do you handle inconsistent data formats (e.g., date/time)?
     In Excel, I can use the Format Cells → Date option or functions like TEXT().
7. What are common data cleaning challenges?
* Missing or inconsistent data.
* Duplicates and incorrect data entries.
* Wrong data types (e.g., numbers stored as text).
* Unstandardized values (e.g., “India”, “IND”, “IN”).
* Handling outliers and formatting errors.
8. How can you check data quality?
By verifying:
  * Completeness: Are all fields filled?
  * Accuracy: Are values correct and realistic?
  * Consistency: Are data formats and categories uniform?
  * Uniqueness: Are there any duplicates?
