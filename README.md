# Crowdfunding Projects Analysis

## Introduction
Crowdfunding platforms like Kickstarter and Indiegogo grew in success and popularity since the late 2000s. From independent content creators to famous celebrities, more and more people used crowdfunding to launch new products and generate buzz. However, not every project found success.

To receive funding, a project had to meet or exceed an initial goal. Many organizations dedicated considerable resources to examining past projects in an attempt to discover the factors leading to success. This analysis involved organizing and analyzing a database of 1,000 sample projects to uncover any hidden trends.

## Data Analysis Instructions
### Step 1: Conditional Formatting
- Used conditional formatting to fill each cell in the outcome column with a different color, depending on whether the associated campaign was successful, failed, canceled, or was currently live.
### Step 2: Percent Funded Column
- Created a new column called Percent Funded that used a formula to find how much money a campaign made relative to its initial funding goal.
- Used conditional formatting to fill each cell in the Percent Funded column according to a three-color scale. The scale started at 0 with a dark shade of red, and it transitioned to green at 100 and blue at 200.
### Step 3: Average Donation Column
- Created a new column called Average Donation that used a formula to find how much each project backer paid on average.
### Step 4: Category Splitting
- Created two new columns, one called Parent Category and another called Sub-Category, that used formulas to split the Category and Sub-Category column into two new, separate columns.
### Step 5: Campaign Outcome Pivot Table
- Created a new sheet with a pivot table that analyzed the initial worksheet to count how many campaigns were successful, failed, canceled, or were currently live per category.
- Created a stacked-column pivot chart that could be filtered by country based on the table created.
### Step 6: Sub-Category Outcome Pivot Table
- Created a new sheet with a pivot table that analyzed the initial sheet to count how many campaigns were successful, failed, canceled, or were currently live per sub-category.
- Created a stacked-column pivot chart that could be filtered by country and parent category based on the table created.
### Step 7: Date Conversion Columns
- The dates in the deadline and launched_at columns used Unix timestamps. Used a formula to convert these timestamps to a normal date.
- Created a new column named Date Created Conversion that converted the data in launched_at into Excel's date format.
- Created a new column named Date Ended Conversion that converted the data in deadline into Excel's date format.
### Step 8: Outcome by Date Pivot Table
- Created a new sheet with a pivot table that had a column of outcome, rows of Date Created Conversion, values based on the count of outcome, and filters based on parent category and years.
- Created a pivot-chart line graph that visualized this new table.
## Crowdfunding Goal Analysis
- Created a new sheet with 8 columns: Goal, Number Successful, Number Failed, Number Canceled, Total Projects, Percentage Successful, Percentage Failed, Percentage Canceled.
- In the Goal column, created 12 rows with specific goal ranges.
- Used the COUNTIFS() formula to count how many successful, failed, and canceled projects were created within each goal range.
- Populated the Number Successful, Number Failed, and Number Canceled columns with these data points.
- Added up each of the values in the Number Successful, Number Failed, and Number Canceled columns to populate the Total Projects column.
- Used a mathematical formula to find the percentage of projects that were successful, failed, or canceled per goal range.
- Created a line chart that graphed the relationship between a goal amount and its chances of success, failure, or cancellation.
## Statistical Analysis
- Evaluated the number of campaign backers to assess the success of a crowdfunding campaign.
- Created a summary statistics table for successful and unsuccessful campaigns.
- Created a new worksheet with columns for the number of backers of successful and unsuccessful campaigns.
- Used Excel to evaluate the following values for both successful and unsuccessful campaigns: mean, median, minimum, maximum, variance, standard deviation.
- Used the data to determine whether the mean or the median better summarized the data.
- Analyzed the variability of successful versus unsuccessful campaigns and provided insights.
