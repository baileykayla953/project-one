# Mindful Thinking with Thinking with Mental Health in Tech
In this presentation we analyzed overall mental health in tech companies, and the limitations/consequences that can interfere with their work.

# Description
-Tech and non tech companies are fairly comparable but non tech workers know more about their benefits/are offered benefits.

-Employees are more likely to become knowledgeable and utilize company Benefits by their late career.

-More people seek treatment later in their career and people later in their career have more knowledge about their options.

# Getting Started
## Dependencies
-CSV File from https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey

-PANDAS Library

-Numpy

-Matplotlib


-Scipy.Stats

 ## Installing
- run in Jupyter Notebook/ Visual Studio 
 
- Python File

- Ran in PythonData 3.7 Environment
  
# Executing Program
## mental_health_tech.ipynb

![image](https://user-images.githubusercontent.com/118647940/218614097-d8d3d02c-dcf5-49a0-9fd1-78d638ee29ea.png)
-Importing libraries/csv file and creating a DataFrame. Filtering to gender.

<img width="480" alt="image" src="https://user-images.githubusercontent.com/118647940/218614737-7a3bf040-aa5c-4cf4-978e-1f585b2db672.png">
-Filtering and Cleaning duplicates/ odd values in gender and creating a cleaned DataFrame for mental health. 

<img width="475" alt="image" src="https://user-images.githubusercontent.com/118647940/218615073-26109272-4ec7-4ea1-80bc-4cfc99946d44.png">
-Create a new DataFrame with filtered columns out of cleaned data. 

<img width="488" alt="image" src="https://user-images.githubusercontent.com/118647940/218615248-fabe6616-2ef4-4f9c-87d3-65a0bec1ac79.png">
- Combine "Not Sure" and "No" Responses and filter tech vs no tech 

<img width="486" alt="image" src="https://user-images.githubusercontent.com/118647940/218615436-b720ea97-fdae-462f-97fc-849f4d214a45.png">
-Create Pie Chart of those seeking help in tech, empyers who offer benefits in tech , and observed negative consequences in tech.

<img width="443" alt="image" src="https://user-images.githubusercontent.com/118647940/218615887-0ac2d52e-9b3d-4720-b54c-9e0593c51e5e.png">
-Create Pie Chart of those seeking help in nontech, employers who offer benefits in nontech, and observed negative consequences for nontech.

<img width="398" alt="image" src="https://user-images.githubusercontent.com/118647940/218616159-5f7734d9-e5ad-48cf-965c-c538ba570a3f.png">
-Creating a dataframe filtered to age bins

<img width="400" alt="image" src="https://user-images.githubusercontent.com/118647940/218616288-4fb58eed-b053-459b-a270-0cb54df7f31a.png">
-Creating a bargraph based on age bins for those seeking treatment. 
-Creating a DataFrame for knowledge of option by age bins

<img width="405" alt="image" src="https://user-images.githubusercontent.com/118647940/218616520-ecfd6ae2-0be9-41f6-8eed-f464e5bd1f06.png">
-Bargraph of Knowledge of options
-Ttest results of consequences by age 

## Summary_Stats_.ipynb

<img width="404" alt="image" src="https://user-images.githubusercontent.com/118647940/218616846-2225b239-e725-40f3-a594-e080070a23e4.png">
-Importing Libraries and CSV File and create DataFrame
-Renaming and Filtering DataFrame to needed columns

<img width="406" alt="image" src="https://user-images.githubusercontent.com/118647940/218617109-ed92a6dc-d38c-42a7-a8ea-5a6986be8ce6.png">
-Filter to tech only
-Create a new DataFrame with Age, Employer Benefits, and Employee Wellness Program

<img width="403" alt="image" src="https://user-images.githubusercontent.com/118647940/218617288-22abef3a-1c67-46dc-b449-67c73555e5d4.png">
-Created age cateogry bins and DataFrame for Early Career age group

<img width="393" alt="image" src="https://user-images.githubusercontent.com/118647940/218617464-36116580-b1d6-4168-a2e4-f53dd709a262.png">
-Filtered Early Career to Age, Employer Benefits and Employee Wellness Program
-Created a Bargraph for Early Career wtih Age, Employer Benefits and Employee Wellness Program

<img width="404" alt="image" src="https://user-images.githubusercontent.com/118647940/218617703-a5927bc6-7abb-4e5b-a170-f7425f939fe3.png">
-Created Early/Mid career dataframe
-Filtered Early/Mid Career to Age, Employer Benefits and Employee Wellness Program

<img width="392" alt="image" src="https://user-images.githubusercontent.com/118647940/218617898-c3a3fd6d-61b7-464c-b1ae-699f4a7508f9.png">
-Create bargraph for Early/Mid career for Age, Employer Benefits and Employee Wellness Program.
- Created DataFrame for Mid Career and filtered to Employer Benefits and Employee Wellness Program.

<img width="392" alt="image" src="https://user-images.githubusercontent.com/118647940/218618187-c4d6923d-dbe9-4635-aaea-ebf34e9c9a7d.png">
-Created a bragraph for Mid Career for Employer Benefits and Employee Wellness Program
-Create a DataFrame for Late Career and filter to Employer Benefits and Employee Wellness Program
-Merge "Don't Know" and "No" 

<img width="465" alt="image" src="https://user-images.githubusercontent.com/118647940/218618493-15dc6959-025e-439d-a879-e81c0d339559.png">
-Created a bragraph for Late Career for Employer Benefits and Employee Wellness Program

## Data_Analysis.ipynb

<img width="457" alt="image" src="https://user-images.githubusercontent.com/118647940/218618784-60db35ea-b519-497b-9f4a-78c7ac1ee338.png">
Import Libraries and CSV
-Create a DataFrame for CSV
-Rename DataFrame
-Filter down to Family History 

<img width="424" alt="image" src="https://user-images.githubusercontent.com/118647940/218619002-86e36790-bd75-4058-b46a-513f5952e38b.png">
<img width="415" alt="image" src="https://user-images.githubusercontent.com/118647940/218619371-b8fb7518-9825-4a20-874d-e27ed6b582ab.png">
 Pie Charts for family history, Work Interference,anonymity. 


# Authors
-Brittany Wright  github:brittanynicole7

-Kayla Bailey     github:baileykayla953

-Holly Cornett    github:cornettholly



















