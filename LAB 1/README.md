## LAB 1 Date: 19/06/23

# Bank Dataset Analysis

This folder contains Python code to perform analysis on a bank dataset, a CSV file where variables are divided using semicolons. The codes provide functions to open the dataset, retrieve headers, count customers by marital category, and prepare a histogram for age.

## Functions Defined

### `open_dataset()`

This function opens the bank dataset file and returns the dataset content as a list.

### `headers(data)`

This function takes the dataset content as input and prints the headers present in the file.

### `count_of_customers_by_marital_category(data)`

This function takes the dataset content as input and counts the number of customers in each marital category. It prints the count for each category.

### `age_histogram(data)`

This function takes the dataset content as input and prepares a histogram for age. It divides the ages into classes of interval 10 and counts the number of ages in each class. It then prints the histogram showing the age classes and their counts in a visual format.

## Usage

To use this code, follow these steps:

1. Ensure the bank dataset file (`bank.csv`) is in the desired directory.

2. Open the Python script that contains the code.

3. Call the functions in the desired order to perform the analysis. For example:

    python
    dataset = open_dataset()
    headers(dataset)
    count_of_customers_by_marital_category(dataset)
    age_histogram(dataset)
    

4. Run the Python script and observe the results printed in the console.

## Submitted by: 
   Homita Ganguly 
   22112314
   3 BSc Ea 


