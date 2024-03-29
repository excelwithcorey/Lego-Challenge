<p align="center">
  <img width="860" height="500" src="https://github.com/excelwithcorey/Lego-Challenge/assets/153139454/2b7e7aca-6cd3-41e6-b2ea-a77763337edd">
</p>

# Lego Challenge by Maven Analytics
[Corey's Entry](https://mavenanalytics.io/project/12340) 

## About this project
The primary objective of this project is to develop a dashboard showcasing the evolution of LEGO over the past five decades. Tailored with user-friendliness and LEGO enthusiasts in mind, the aim is to craft an engaging dashboard that facilitates seamless navigation, empowering users to gain comprehensive insights effortlessly. 2 dashboards will demonstrate Lego's success throughout the years. The dashboards will be interactive and dynamic for users to fully access the history of Lego sets. 
- The first dashboard provides a detailed analysis of Legos over 5 decades, revealing significant insightful findings for business.
- In the second dashboard, we dive into comprehensive price trends spanning over the years, uncovering valuable insights into the evolution of pricing dynamics over time.

## Objective:
- The objective of the project is stated from Maven Analytics.

"Piece together an interactive dashboard or visual that lets users explore the history and evolution of Lego sets from the past 5 decades."

- For more information on Maven's Lego Challenge follow the link [here](https://mavenanalytics.io/challenges/maven-lego-challenge/29). 

## About the Data

| Column                  | Description                             | Data Type       |
| :---------------------- | :-------------------------------------- | :-------------- |
| set_id                  | official lego item number               | VARCHAR (50)    |
| name                    | name of lego set                        | VARCHAR (100)   |
| year                    | release year                            | NUMERIC         | 
| theme                   | lego theme the set belongs to           | VARCHAR (50)    |
| subtheme                | subtheme within the theme               | VARCHAR (50)    |
| theme_group             | overall group the theme belongs to      | VARCHAR (50)    |
| category                | type of set                             | VARCHAR (10)    |
| pieces                  | number of pieces in the set             | NUMERIC         |
| minifigs                | number of mini figures included         | NUMERIC         |
| agerange_min            | minimum age recommended                 | NUMERIC         |
| price                   | US retail price at launch               | DECIMAL (100, 2)|


## Methods:
### Data Cleaning
- Replaced null values in subtheme and theme_group with “unknown”
- Changed the data description of year to ‘date’
### Exploratory Data Analysis (EDA)
- Summarize the important information for the intended audience.
- Developed in-depth analysis of the data to share with the audience.
### Creating a Dynamic Dashboard
- Implemented filters for users to fully explore the data.
- Created visualizations for important information for the target audience.

## Dashboard:
This dashboard is intended for audiences that are interested in learning more about Lego's 5 decades of growth. The dashboard displays information on its sets, age, minifigs, themes, and retail price. I wanted to lean into analyzing the different themes and highlight their growth over the years.

The first dashboard allows its users to navigate through the years with the "Years" filter to learn about the progression of its featured themes.

1. How long has a theme been a part of Lego's business?

2. Which Lego theme has the most pieces?

3. What is the ratio between sets having minifigs?

4. What does Lego's overall growth look like over the years?
After analyzing the dataset overall Lego has dominated the market.

- Piece and set numbers have steadily increased from 1970 to 2022, indicating a clear upward trend. 

- Duplo holds the longest-lasting theme that plays a significant presence in building sets. 

- 45.5% of Lego sets feature minifigures. 

- Arts and Crafts stands out as the dataset's most favored theme, eclipsing all others in popularity.
The second dashboard explores pricing trends over time, including total and average retail prices. Also, someone who is a Lego enthusiast who wants to collect all sets to calculate the total price they may have to pay to obtain each set. This dashboard is interactive and allows its users to navigate retail prices by selecting various filters such as year, category, theme, etc.

Limitations:

The price is limited due to the dataset having multiple empty values. Although missing values may affect the analysis, this dashboard evaluates prices based solely on the information provided in the CSV file. NO MANIPULATION of the empty values was changed in the dataset.
Audiences for this specific dashboard will mainly be interested in

1. What are the top 10 most expensive sets? 

2. What is the MIN and MAX price set that you can expect to pay for a Lego set? 

3. How do the theme groups compare in price? 

4. What is the trend of retail price over 5 decades? 
Insights for retail price analysis concludes:

- AT- AT and Millennium Falcon are the most expensive sets. 

- You can expect to pay as low as $1.99 and upwards to $849.99 for a set from Lego between the years of 1970 to 2022. 

- The price table evaluates a bundle of information. The key insight is that the 'Licensed' theme has the most productions and will cost the most to acquire. 

The total retail price trend shows a consistent increase over the years, mirroring the growth in the number of sets released annually.

