# Bacteria Analysis using Excel

Source: https://www.kaggle.com/datasets/kanchana1990/bacteria-dataset

Stage 1: Data Cleaning & Transformation

I used a new excel sheet to clean the row data. Firstly, I remove duplicates and trimed whitespaces. Next, I used the function unique() so that I find all the bacteria names and families. I also used the same function to identify all the unique places bacteria can be found. As some bacteria are harmful for human and some are not, I used if() to specify the harmful bacteria as 0 and the non harmful as 1.

Stage 2: Data Analysis

After cleaning my data, I moved to data analysis. I found the total amount of bacteria, the families and all the different places bacteria can be found. Furthermore, I calculated the amount of bacteria that are harmful for human and the ones that are not. 

Stage 3: Data Visualization & Communication

# Pie Chart: How many bacteria are harmful to humans?

By looking at the visualization, 47.7% of the bacteria in the current list are harmful for humans when the rest 52.3% is beneficial for us.

# Bar Chart: Where can you find bacteria that are neutral for human?
