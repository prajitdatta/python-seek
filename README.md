# python-seek
Q1.Write a function in python to sum up a given set of numbers other than itself
Input: An array of n integers nums,
Output: An array output such that output[i] is equal to the sum of all the elements
of nums except nums[i].
For example, given [1,2,3,4], return [9,8,7,6].

Q2.Jobposts Data Exploration and Analysis
a) Download the following Kaggle dataset:
Jobposts Data: https://www.kaggle.com/madhab/jobposts/
b) Extract the following fields by processing content in the jobpost column:
1. Job Title
2. Position Duration
3. Position Location
4. Job Description
5. Job Responsibilities
6. Required Qualifications
7. Remuneration
8. Application Deadline
9. About Company
c) Identify the company with the most number of job ads in the past 2 years
d) Identify the month with the largest number of job ads over the years
e) Clean text and generate new text from Job Responsibilities column: The new text
shall not contain any stop words, and the plural words shall be converted into
singular words.
f) Write functions to identify null/NA values and to replace null/NA values with a
custom message in “Duration” column
g) Store the results in a new Dataframe/SQL table(s)
h) Write the results to an S3 bucket (optional)

Q3. Semantic similarity
a) Using the output from Q2, identify semantically similar job ads and group them
together.
b) Display the top groups
(Extra points for using word embeddings)
(Extra points for utilizing job descriptions, job responsibilities data and/or others)

Q4. Music and Artists
a) Extract raw text from https://en.wikipedia.org/wiki/1990s_in_music
b) Extract best-selling music artists from https://en.wikipedia.org/wiki/List_of_best-
selling_music_artists
c) Find out how many best-selling music artists are from 1990s through extracted raw
text from (a)
