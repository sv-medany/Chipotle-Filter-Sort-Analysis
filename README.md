
# Chipotle Data Analysis: Filtering and Sorting

This project involves the filtering and sorting of Chipotle order data using Python and the Pandas library. The dataset is obtained from [this source](https://raw.githubusercontent.com/justmarkham/DAT8/master/data/chipotle.tsv), and it contains information about items ordered, their quantities, prices, and more.

## Project Overview

This repository contains Python code for filtering and sorting Chipotle order data using the Pandas library. The analysis includes steps to load the dataset, filter products by price, sort items by name, and answer questions related to quantity and specific items. The primary goals of this project are:

- Filter and sort Chipotle order data using Pandas.
- Answer questions about the dataset, such as the number of products costing more than $10, price of each item, most expensive item quantity, and more.

## Steps in the Analysis

1. Import necessary libraries, including Pandas and NumPy.
2. Import the Chipotle dataset from the provided source.
3. Assign the dataset to a variable called `chipo` and set 'order_id' as the index.
4. Convert the 'item_price' column to a numerical format.
5. Determine the number of products costing more than $10.
6. Display the price of each item using a DataFrame with 'item_name' and 'item_price' columns.
7. Sort the data by the name of the item.
8. Determine the quantity of the most expensive item ordered.
9. Count the number of times a "Veggie Salad Bowl" was ordered.
10. Count the number of times someone ordered more than one "Canned Soda".

## Repository Structure

```
Chipotle-Filter-Sort/
│
├── chipotle_filter_sort.ipynb      # Jupyter Notebook with analysis code
├── chipotle.tsv                   # Dataset file
└── readme.md                      # Project summary
```

## Usage

1. Clone the repository using: `git clone https://github.com/your-username/Chipotle-Filter-Sort.git`
2. Navigate to the repository: `cd Chipotle-Filter-Sort`
3. Open the `chipotle_filter_sort.ipynb` notebook to see the detailed analysis steps and results.

## Acknowledgments

- The dataset is sourced from [justmarkham](https://github.com/justmarkham) on GitHub.
- Special thanks to the contributors of the Pandas and NumPy libraries for providing the tools for data analysis.

