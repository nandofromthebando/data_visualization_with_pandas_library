# data_visualization_with_pandas_library
Deep Analysis of "Billionaires Statistics Dataset (2023)" which was uploaded by NIDULA ELGIRIYEWITHANA on Kaggle.com
# Billionaires Statistics Analysis

This Python script is designed to perform data analysis and visualization on a dataset containing information about billionaires. The script offers insights into the distribution of billionaires across industries, gender, countries, and whether they are self-made. Additionally, it calculates statistics related to the age and final worth of billionaires.

## Usage

1. **Clone or Download the Repository:**

   You can clone this repository to your local machine using Git, or you can simply download it as a ZIP file. Here's how you can clone it:

   ```bash
   git clone https://github.com/yourusername/billionaires-stats.git
## Install Required Python Libraries:
Make sure you have the necessary Python libraries installed. You can install them using pip:
bash
* Copy code: pip install pandas numpy matplotlib
* Replace the Data File:
* Replace the sample data file (/YourFilePath/Billionaires Statistics Dataset.csv) with your own dataset. You can specify the path to your data file in the load_data function within the script.
* Run the Script:
* Execute the script to generate visualizations and statistics:
* Copy code: python billionaires_stats.py
* This will create and save plots and display statistics.
## Functions

The script includes the following functions:

* load_data(file_path): Loads data from a CSV file and returns it as a Pandas DataFrame.
* plot_industry_distribution(data): Generates a plot showing the distribution of billionaires across different industries.
* plot_gender_distribution(data): Creates a pie chart illustrating the gender distribution of billionaires.
* plot_country_distribution(data): Produces bar charts displaying the distribution of billionaires by country. The data is split into * three parts for clarity.
* plot_selfmade_distribution(data): Generates a pie chart showing the ratio of self-made billionaires compared to those who are not self-made.
* calculate_statistics(data): Calculates and prints statistics on the age and final worth of billionaires, including median, mean, mode, and standard deviation.
# Results

The script will generate the following output:

* Industry Distribution Plot: A bar chart showing the distribution of billionaires across different industries. This plot will be saved as industry_distribution.png.
* Gender Distribution Plot: A pie chart illustrating the gender distribution of billionaires. This plot will be saved as gender_distribution.png.
* Country Distribution Plots: A set of bar charts displaying the distribution of billionaires by country. The data is split into three parts for clarity. These plots will be saved as country_distribution.png.
* Self-Made Distribution Plot: A pie chart showing the ratio of self-made billionaires compared to those who are not self-made. This plot will be saved as selfmade_distribution.png.
* Statistics: The script will calculate and print statistics on the age and final worth of billionaires, including the median, mean, mode, and standard deviation.
