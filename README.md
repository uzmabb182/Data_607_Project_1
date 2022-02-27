# Data_607_Project_1:
The purpose of this project, to read a text file with chess tournament results where the information has some structure. The aim is to create an R Markdown file that generates a .CSV file (that could for example be imported into a SQL database) with the following information for all of the players. Player’s Name, Player’s State, Total Number of Points, Player’s Pre-Rating, and Average Pre Chess Rating of Opponents.


# Below are the steps taken during this process:

- Step1: # Required Libraries are imported.

- Step2: # Removing the unwanted rows from the dataset.

- Step3: # Performed the process of fetching the rows that we need from the dataset.


- Step4: # Removed the empty spaces from column V1 and V2.


- Step5: # Fetched the rows V1 and V2 for state names and players scores into vectors.


- Step6: # Find the location of the score strings needed for fetching and cleaning od extra spaces.


- Step7: # Create a temporary data frame for next set of rows to be fetched.

- Step8: # Fetched the rows V1 and V2 for player's number, name and points into vectors and performing cleaning steps.

- Step9:  # Created new data frame for storing the vectors.

- Step10: # Performed the steps for fetching each player's opponent scores.

- Step11: # Fetched, extracted, and removed spaces of opponent's numbers for calculating averages.


- Step12: # Locate the working directory path and exporting data frame into a CSV file.




