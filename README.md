# 5530_assignment_1
Assignment 1

Question 1.
The first stage of reproducible workflow is collecting and inputing the data. Once the raw data is collected, it should be saved in a CSV file and stored in a useful location. Along with the CSV file, a readme file should be created with metadata. In this example, the readme.txt file would note that height is in inches, weight is in pounds, age is in years, and grip strength is in kilograms.

The second stage is cleaning the data. This can include manual data entry, reviewing, filtering, and manipulating the data. 

The third stage is data analysis. This includes statistical tests and data visualization. An example of this would be plotting a line chart to show correlation between age and grip strength, or weight and grip strength. This could be used to make predictions on frailty as women age.

Folder structure for this project:

|-- frailty_data_project
    |-- raw_data
        |-- raw_frailty_data.csv
        |-- readme.txt
    |-- data_clean
        |-- clean_frailty_data.csv
    |-- results
        |--results.txt
    |-- src
        |-- analysis.r


Question 2. 
Through the data visualization tasks, we can make a few observations about the data. First, with the histograms, we can see that the math scores are spread out more than the other two subjects. However, the math scores seem to average around 60-65. Very few people scored under 20 on the reading and writing tests. Most students scored between 60 and 80 on both subject tests. 
From the pie chart, we can see that over a third of the students have free or reduced lunch. We can use this to make a correlation between socioeconomic status and test scores of this sample. 
The bar chart shows how students performed in each subject (average) according to their parents' level of education. From looking at the chart, we can see that students whose parents have a college degree performed better, on average, than those whose parents did not. 
The scatter plots show that the students who performed well in math likely also performed well in reading and writing. Using colors to show the difference in gender, we see that, on average, females performed better than males in all tests, except for a few outliers who did not perform well in either subject. 

Folder structure for this project:
|-- students_performance_project
    |-- data_raw
        |-- studentsperformance.csv
        |-- readme.txt
    |-- data_clean
    |-- results
        |-- results.txt
    |-- src
        |-- students_performance_analysis.py
