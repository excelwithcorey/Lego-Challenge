<p align="center">
  <img width="900" height="500" src="https://github.com/excelwithcorey/Lego-Challenge/assets/153139454/2b7e7aca-6cd3-41e6-b2ea-a77763337edd">
</p>

# Lego Challenge by Maven Analytics
[Corey's Entry](https://mavenanalytics.io/project/12340) 

## About this project
Lego Data Analysis

## Objective:
The objective of the project is stated from MAVEN and the team.

"Piece together an interactive dashboard or visual that lets users explore the history and evolution of Lego sets from the past 5 decades."

For more information on Maven's Lego Challenge follow the link [here](https://mavenanalytics.io/challenges/maven-lego-challenge/29). 

## Description:
In this Project I want to showcase Lego's evolution from 1970-2022. There are 2 dashboards that will demonstrate Lego's success throughout the years. The dashboards will be interactive and dynamic for users to fully access the history of Lego sets. The first dashboard demonstrates descriptive analysis of the dataset provided by Maven Analytics that demonstrates various findings. The second dashboard discovers the price trends throughout the years.

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
| agerange_min            | minimum age recommeneded                | NUMERIC         |
| price                   | US retail price at launch               | DECIMAL (100, 2)|


## Methods:
### Data Cleaning
- Replaced null values in subtheme and theme_group with “unknown”
- Changed the data description of year to ‘date’
### Exploratory Data Analysis (EDA)

### Creating a Dynamic Dashboard

## Dashboard:
This dashboard intended for audiences that is interested in learning more about Lego's 5 decade of growth. The dashboard displays information on its sets, age, minifigs, themes and retail price. I wanted to lean into analyzing the different themes and highlight its growth over the years.

The first dashboard allows its user to navigate through the years with the "Years" filter to learn about the progression of its featured themes.

1. How long has a theme been a part of Lego's business?

2. Which Lego theme has the most pieces?

3. What is the ratio between sets having minifigs?

4. What does Lego's overall growth look like over the years?
After analyzing the dataset overall Lego has dominated the market.

- Piece and set numbers have steadily increased from 1970 to 2022, indicating a clear upward trend. 

- Duplo holds the longest-lasting theme that plays a significant presence in building sets. 

- 45.5% of Lego sets feature minifigures. 

- Arts and Crafts stands out as the dataset's most favored theme, eclipsing all others in popularity.
The second dashboard explores pricing trends over time, including total and average retail prices. Also someone who is a Lego enthusiast that wants to collect all sets to calculate the total price they may have to pay to obtain each set. This dashboard is interactive that allows its users to navigate retail price by selecting various filters such as year, category, theme, etc.

Limitations:

The price is limited due to the dataset having multiple empty values. Although missing values may affect the analysis, this dashboard evaluates prices based solely on the information provided in the CSV file. NO MANIPULATION of the empty values were done here.
Audiences for this specific dashboard will mainly be interested in

1. What is the top 10 most expensive sets? 

2. What is the MIN and MAX price set that you can expect to pay for a Lego set? 

3. How do the theme group's compare in price? 

4. What is the trend of retail price over 5 decades. 
Insights for retail price analysis concludes:

- AT- AT and Millennium Falcon to be the most expensive sets. 

- You can expect to pay as low as $1.99 and upwards to $849.99 for a set from Lego between the years of 1970 to 2022. 

- The price table evaluates a bundle of information. The key insights is that 'Licensed' theme has the most productions and will cost the most to acquire. 

- Total retail price trend shows a consistent increase over the years, mirroring the growth in the number of sets released annually.

