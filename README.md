# Compilation of Documents (PROGRAMMING ASSIGNMENTS)

## Practice Problems:

PROBLEM 1: Save your file as Surname_Pandas-P1.py

Using knowledge obtained from the experiment and demonstrations:

a. Load the corresponding .csv file into a data frame named cars using pandas

b. Display the first five and last five rows of the resulting cars.

..........................................................................................................................................................................................

PROBLEM 2: Save your file as Surname_Pandas-P2.py

Using the dataframe cars in problem 1, extract the following information using subsetting, slicing and
indexing operations.

a. Display the first five rows with odd-numbered columns (columns 1, 3, 5, 7…) of cars.

b. Display the row that contains the ‘Model’ of ‘Mazda RX4’.

c. How many cylinders (‘cyl’) does the car model ‘Camaro Z28’ have?

d. Determine how many cylinders (‘cyl’) and what gear type (‘gear’) do the car models ‘Mazda RX4
Wag’, ‘Ford Pantera L’ and ‘Honda Civic’ have.



## Overview of the P.A.:

Source of the codes provided: cars.csv (Downloadable in main content)

Description: This dataset includes information about different car models, including their specifications like model name, number of cylinders, gear type, and more.



## P.A. Analysis, Explanation, and Process

- Download the Dataset - Make sure to save the provided file "cars.csv" in your working directory or default user folder together with the Jupyter Notebook

- Set Up the Jupyter Notebook - Open a Jupyter Notebook. Create a new notebook and rename it, for example, Surname_Pandas-P2.py

- Load the Dataset - Start the program by importing the pandas library. Import the CSV file into the Data and name it, for example, cars

- (For P1) Display Data - Use the .Head() and .Tail() method to display the first and last five rows of the data.

- (For P2) Perform Data Extraction - Extract Odd-Numbered Columns: Use slicing to select the first five rows of the data with odd number columns - Mazda RX4 Information: Filter the DataFrame to display the row for the 'Mazda RX4' - Camaro Z28 Cylinder Count: Retrieve the number of cylinders for the 'Camaro Z28' model - Information for Selected Models: Create a list of models for 'Mazda RX4 Wag', 'Ford Pantera L', and 'Honda Civic'. Filter the DataFrame to display the cylinders and gear types for these models.

- Run the Cells - Execute each cell sequentially, and review the outputs to confirm that the operations performed well



## Expected Outputs

PROBLEM 1:

The first and last five rows of the dataset.

.........................................................................................................

PROBLEM 2:

The first five rows containing only odd-numbered columns.

The complete details for 'Mazda RX4'.

The number of cylinders for 'Camaro Z28'.

A table showing the cylinder counts and gear types for the specified models.



## Version and Edit History 

- Version 1 - Initial Release: Completed basic analysis tasks as outlined in the assignment.

- Version 2.1 - Refined data extraction methods for improved clarity. Verified the accuracy of outputs and added print statements for better readability.

- Version 2.2 - Final Release: Change of .ipynb file to .py file 

  

# Author's Profile
Name: Charles Ellis S. Reyes

Section: 2ECE-D

P.A. by: Prof. Engr. Ma. Madecheen S. Pangaliman, M.Sc.

Date of Completion: September 18, 2024
