# Swiggy Restaurant Data Analysis


<img align="right" alt="Coding" width="400" src="https://github.com/shridharkamathe/Hotel-Data-Analysis/assets/124047047/67d373a6-af43-4e80-831d-a0d41d186f72">

This repository contains an analysis of restaurant data scraped from the food delivery platform Swiggy. The analysis aims to suggest an ideal location and cuisine for a client planning to open a cloud kitchen. Additionally, the data is utilized to generate insights and create a dashboard with various metrics related to the restaurants on Swiggy.

## Dataset

The dataset used for this analysis is sourced from Swiggy using web scraping techniques. The following files are included in the repository:

- `Cap Cleaning Table 2.ipynb`: Jupyter Notebook containing the data cleaning process for Table 2.
- `Capstone Swiggy.xlsx`: Excel file containing the DashBoard and the main dataset for the project.
- `Restaurant_Details.xlsx`: Excel file with details of the restaurants.
- `Resto_info.xlsx`: Excel file with additional restaurant information.
- `Swiggy Table 2.xlsx`: Excel file containing the cleaned data for Table 2.
- `Web Scraping.ipynb`: Jupyter Notebook containing the web scraping code.

## Analysis

The analysis covers the following steps:

1. **Data Collection**: The data is scraped from Swiggy using web scraping techniques and saved in Excel files.

2. **Data Cleaning**: The collected data is cleaned and organized to ensure consistency and accuracy.

3. **Table 1: restaurant_info**: The cleaned data is used to create Table 1, which includes attributes such as restaurant ID, Swiggy URL, name, rating, price, and cuisine.

4. **Table 2: restaurant_details**: The cleaned data is further processed to create Table 2, which includes attributes such as restaurant ID, name, location, dish category, dish name, price, and delivery review numbers.

5. **Dashboard Creation**: An interactive dashboard is created using the data from Tables 1 and 2. The dashboard provides visualizations and insights based on aggregations and metrics derived from the data.

6. **Insights and Recommendations**: Various insights are generated from the data analysis, including area-wise distribution of restaurants, cheapest and most expensive restaurants for each cuisine, locations with the highest number of restaurants with delivery review numbers exceeding 1000, interesting insights from the data, locations with the highest number of poorly rated restaurants, area-wise comparison of cheap and expensive restaurants and their average prices, and the number of restaurants for each type of cuisine. Based on these insights, recommendations are provided for the client regarding the suitable location for their cloud kitchen and pricing of different types of dishes during the initial phase.

## Repository Structure

The repository is structured as follows:

- **data**: This directory contains the Excel files that store the raw and cleaned datasets.

- **notebooks**: This directory includes Jupyter notebooks used for data cleaning, data analysis, and web scraping.

- **dashboard**: This directory contains files related to the interactive dashboard created for data visualization.

- **README.md**: This file, providing an overview of the repository and its contents.

## Dash Board


![send](https://github.com/shridharkamathe/Hotel-Data-Analysis/assets/124047047/2b49ed5d-6b2a-46aa-bdb0-5f65d6951139)




## Challenges Faced

During the data scraping process of Swiggy, we encountered a significant challenge in dealing with the complexity of the scraped data. Specifically, the categories of the dishes were mostly absent or incorrect, making it a daunting task to clean and organize the data effectively.

To address this challenge, we devised a solution that involved leveraging keywords to categorize the dishes correctly. This approach required iterating over every row of the scraped data and examining the presence of specific keywords. By carefully analyzing the keywords associated with each dish, we were able to assign them to their respective categories accurately.

This process of cleaning and categorizing the data proved to be crucial in ensuring the accuracy and usability of the final dataset. By diligently applying keyword-based categorization techniques, we were able to transform the initially disorganized data into a well-structured and comprehensive dataset.

Our approach not only enabled us to overcome the hurdles posed by the absence or inaccuracy of dish categories but also enhanced the overall quality of the dataset. The cleaned data now provides a solid foundation for further analysis, modeling, and insights generation in the context of Swiggy's food offerings.

For more details on the methodology and techniques employed in the data cleaning process, please refer to the accompanying code and documentation in this GitHub repository.

## Usage

To explore the Swiggy restaurant data analysis and access the interactive dashboard:

1. Clone or download this repository to your local machine.

2. Review the Jupyter notebooks in the `notebooks` directory to understand the data cleaning process, data analysis, and web scraping techniques. Execute the notebooks in the specified order.

3. Explore the datasets in the `data` directory, including `Capstone Swiggy.xlsx`, `Restaurant_Details.xlsx`, `Resto_info.xlsx`, and `Swiggy Table 2.xlsx`. These files contain the raw and cleaned data used for analysis.

4. Open the interactive dashboard files in the `dashboard` directory using a compatible web browser to visualize the insights from the analysis.

5. Customize and modify the analysis and dashboard as required for your specific use case.

## Contributing

Contributions to this repository are not currently being accepted, as it is a sample repository. However, feel free to fork the repository and adapt it to your own requirements.

## Acknowledgments

We would like to acknowledge the efforts put into this analysis and the creation of the interactive dashboard. The insights and recommendations provided are based on thorough research and data exploration.

Please note that the recommendations provided should be further evaluated and adapted based on the specific context and objectives of the client's cloud kitchen business.
