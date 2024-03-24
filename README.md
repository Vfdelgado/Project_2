# Crowdfunding Data Analysis
## Project_2: Option 1 - Python/Pandas

This mini-project aims to analyze crowdfunding data extracted from Excel files and transform it into structured DataFrames. The data includes information about categories, subcategories, campaigns, and contacts. By extracting, transforming, and organizing the data, we can gain insights into the crowdfunding landscape and prepare it for further analysis or visualization.

## Part 1: Create the Category and Subcategory DataFrames

Extract and transform the "crowdfunding.xlsx" Excel data to create a category DataFrame containing unique category titles and their corresponding IDs.
Export the category DataFrame as "category.csv" and save it to the GitHub repository.
Create a subcategory DataFrame containing unique subcategory titles and their corresponding IDs.
Export the subcategory DataFrame as "subcategory.csv" and save it to the GitHub repository.

## Part 2: Create the Campaign DataFrame

Extract and transform the "crowdfunding.xlsx" Excel data to create a campaign DataFrame with essential columns such as campaign ID, contact ID, company name, description, goal, pledged amount, outcome, backers count, country, currency, launch date, end date, category ID, and subcategory ID.
Clean and convert data types for goal, pledged amount, launch date, and end date columns.
Export the campaign DataFrame as "campaign.csv" and save it to the GitHub repository.

## Part 3: Create the Contacts DataFrame

Import the "contacts.xlsx" file into a DataFrame.
Iterate through the DataFrame, converting each row to a dictionary.
Extract dictionary values from keys and add them to a new list.
Create a new DataFrame containing the extracted data.
Split the "name" column value into first and last names and place them in separate columns.
Clean and export the DataFrame as "contacts.csv" and save it to the GitHub repository.

---------------------

By completing the above steps, we have successfully extracted, transformed, and organized the crowdfunding data into structured DataFrames suitable for analysis. These DataFrames can serve as the foundation for further exploration, visualization, or machine learning tasks related to crowdfunding activities. The generated CSV files are readily available in the GitHub repository for easy access and sharing. Users can leverage these datasets to derive valuable insights and make informed decisions in the crowdfunding domain.

### Resources

Class Activities, Online Resources, Instructor and TAs.
