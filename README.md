# Bacteria Analysis using Excel

Source: https://www.kaggle.com/datasets/kanchana1990/bacteria-dataset
---------------------------------------------------------------------
Stage 1: Data Cleaning & Transformation

I utilized a new Excel spreadsheet to organize the row data. Initially, I eliminated duplicate entries and removed extra spaces. Following that, I employed the unique() function to compile a comprehensive list of bacteria names and families. Additionally, I used the same function to identify the various locations where bacteria can be located. To distinguish between harmful and non-harmful bacteria, I employed the if() function to label the harmful bacteria as 0 and the non-harmful bacteria as 1.

Stage 2: Data Analysis

After completing the data cleaning process, I transitioned to data analysis. I identified the total quantity of bacteria present, categorized them by their respective families, and detailed their various locations. Additionally, I conducted an assessment to determine the quantity of bacteria that pose a threat to human health versus those that do not.

Stage 3: Data Visualization & Communication

    # Pie Chart: How many bacteria are harmful to humans?

      By looking at the visualization, 47.7% of the bacteria in the current list are harmful for humans when the rest 52.3% is beneficial for us.

    # Bar Chart: Where can you find bacteria that are neutral for human?

      There are bacteria that live in different environments like contaminated water, water systems and infected animals that are harmful for our body. Also, bacteria that are found on skin, nasal passages, throat,       lungs etc. can be harmful too. On the contrary, bacteria that belong to the human body, intestines,unfected wounds or ecosystems with freshwater, hot springs, sugary, salty and deep see environments, salt           lakes, even radioactive environments are not harmful for us. This analysis shows that some bacteria that live with us or in our surroundings are important and essential for our survival. 
