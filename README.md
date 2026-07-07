# MSCS634_Project_Deliverable1

## Project Overview
I selected the Gym Members Exercise Dataset because it provides a comprehensive collection of health and fitness information that is well suited for data mining and predictive analytics. The dataset contains over 900 records and multiple attributes related to demographics, body composition, workout habits, heart rate, hydration, and calories burned, meeting the project requirements for both size and feature diversity.

This dataset was also chosen because it represents a practical, real-world application of data analysis in the health and fitness domain. By exploring relationships between exercise habits and fitness outcomes, the analysis can help identify factors that influence workout performance and overall health. The dataset includes both numerical and categorical variables, making it suitable for a variety of data mining techniques such as exploratory data analysis, regression, classification, clustering, and association rule mining.

Additionally, I have a personal interest in strength training and fitness, which makes the project more engaging and meaningful. Working with a dataset that aligns with my interests will allow me to better interpret the results and gain insights into exercise behaviors, performance trends, and factors that contribute to successful fitness outcomes.

## Loading the Dataset

The `head()` function displays the first five rows of the dataset. This provides a quick preview of the data, allowing us to verify that the dataset was loaded correctly and to gain an initial understanding of the available features and their values.

<img width="1379" height="586" alt="image" src="https://github.com/user-attachments/assets/bd7f4c19-0460-4352-9890-1dfaf8b04410" />


## Inspect the Dataset

### Determine the Dataset Dimensions

The `shape` attribute returns the number of rows and columns in the dataset. This helps verify that the dataset meets the project requirements and provides an overview of its size before beginning further analysis.

<img width="791" height="154" alt="image" src="https://github.com/user-attachments/assets/bf7b059a-9498-4ba7-b6b3-06cb059671de" />

### Inspect the Dataset Structure

The `info()` function provides a summary of the dataset, including the number of entries, column names, data types, and the number of non-null values. This information is useful for identifying missing values and determining whether any variables require type conversion before analysis.

<img width="778" height="514" alt="image" src="https://github.com/user-attachments/assets/d398387f-5f4b-4cfb-8c52-63041064e2b3" />

### View the Dataset Attributes

The `columns` attribute displays the names of all variables in the dataset. Reviewing the column names helps identify the available features and ensures they are correctly labeled before data cleaning and analysis.

<img width="813" height="593" alt="image" src="https://github.com/user-attachments/assets/405c58ee-e34e-4ac1-995b-dac0f37954a4" />

### Generate Summary Statistics

The `describe()` function calculates descriptive statistics for all numerical variables, including the mean, standard deviation, minimum, maximum, and quartiles. These statistics provide an overview of the data distribution and help identify potential outliers or unusual values.

<img width="1280" height="781" alt="image" src="https://github.com/user-attachments/assets/a072d4fa-82a3-4b6f-a43f-fec6169cd352" />

