# walmar-CI-CLT
performed confidence interval and central limit theorem on data from walmart


## Table of Contents
- [Introduction](#introduction)
- [Objective](#objective)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Notebooks](#notebooks)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction
The Walmar Confidence Interval and Central Limit Theorem project is designed to illustrate the concepts of confidence intervals and the central limit theorem through practical examples and simulations. This repository contains Jupyter notebooks and code to demonstrate the statistical concepts used in data analysis.

## Objective
The primary objectives of this project are:
- Explain the concept of confidence intervals and their role in inferential statistics.
- Showcase the central limit theorem and its significance in sampling from a population.
- Use data simulations to understand the behavior of confidence intervals under different scenarios.

## Features
- Visualization and explanation of confidence intervals.
- Simulation of random samples and calculation of sample means.
- Comparison of different confidence intervals for various sample sizes.

## Technologies Used
- Python 3
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- SciPy

*(Feel free to add or modify the list of technologies based on the tools and libraries used in your project)*

## Installation
To run the Walmar Confidence Interval and Central Limit Theorem notebooks locally, follow these steps:

1. Clone the repository to your local machine using the following command:
   ```
   git clone https://github.com/raghav1saboo/walmar-CI-CLT.git
   ```

2. Navigate to the project directory:
   ```
   cd walmar-CI-CLT
   ```

3. Install the required dependencies using the following command:
   ```
   pip install -r requirements.txt
   ```

## Usage
1. Open Jupyter Notebook to access the statistical analysis notebooks:
   ```
   jupyter notebook
   ```

2. In the Jupyter Notebook interface, navigate to the "notebooks" directory and open the desired notebook.

3. Run the code cells in the notebook to explore confidence intervals and central limit theorem concepts.

*(If there are specific usage instructions or guidelines for your project, provide them here)*

## Notebooks
List the available Jupyter notebooks and their purposes. For example:
- `confidence_interval.ipynb`: Demonstrates the concept of confidence intervals and their applications.
- `central_limit_theorem.ipynb`: Illustrates the central limit theorem through simulations and visualizations.

*(Add any additional notebooks relevant to your project)*

## Contributing
Contributions to this project are welcome. If you find any issues or have improvements to suggest, please feel free to open an issue or create a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

## Contact
If you have any questions or need further assistance, you can reach me via email at [your_email@example.com](mailto:your_email@example.com).

*(Replace 'your_email@example.com' with your actual email address)*

---

You can copy and paste this template into a new file named "README.md" in the root of your "walmar-CI-CLT" repository. Customize the content to match the specifics of your project, such as the objective, features, technologies used, notebooks, and contact details. Additionally, consider providing examples of confidence interval calculations or central limit theorem simulations from the notebooks to demonstrate the statistical concepts effectively.

About Walmart

Walmart is an American multinational retail corporation that operates a chain of supercenters, discount departmental stores, and grocery stores from the United States. Walmart has more than 100 million customers worldwide.


Business Problem

The Management team at Walmart Inc. wants to analyze the customer purchase behavior (specifically, purchase amount) against the customer’s gender and the various other factors to help the business make better decisions. They want to understand if the spending habits differ between male and female customers: Do women spend more on Black Friday than men? (Assume 50 million customers are male and 50 million are female).


Dataset

The company collected the transactional data of customers who purchased products from the Walmart Stores during Black Friday. The dataset has the following features:
Dataset link: Walmart_data.csv

User_ID:	User ID
Product_ID:	Product ID
Gender:	Sex of User
Age:	Age in bins
Occupation:	Occupation(Masked)
City_Category:	Category of the City (A,B,C)
StayInCurrentCityYears:	Number of years stay in current city
Marital_Status:	Marital Status
ProductCategory:	Product Category (Masked)
Purchase:	Purchase Amount

What good looks like?

Import the dataset and do usual data analysis steps like checking the structure & characteristics of the dataset.
Detect Null values & Outliers (using boxplot, “describe” method by checking the difference between mean and median, isnull etc.)
Do some data exploration steps like:
Tracking the amount spent per transaction of all the 50 million female customers, and all the 50 million male customers, calculate the average, and conclude the results.
Inference after computing the average female and male expenses.
Use the sample average to find out an interval within which the population average will lie. Using the sample of female customers you will calculate the interval within which the average spending of 50 million male and female customers may lie.
Use the Central limit theorem to compute the interval. Change the sample size to observe the distribution of the mean of the expenses by female and male customers.
The interval that you calculated is called Confidence Interval. The width of the interval is mostly decided by the business: Typically 90%, 95%, or 99%. Play around with the width parameter and report the observations.
Conclude the results and check if the confidence intervals of average male and female spends are overlapping or not overlapping. How can Walmart leverage this conclusion to make changes or improvements?
Perform the same activity for Married vs Unmarried and Age
For Age, you can try bins based on life stages: 0-17, 18-25, 26-35, 36-50, 51+ years.
Give recommendations and action items to Walmart.
