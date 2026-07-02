# Netflix Catalog Analysis

## Overview
Exploratory analysis of Netflix's content catalog using Python and pandas, with a focus on data cleaning and business insights. This project analyzes the Netflix titles dataset to understand how the platform's content catalog has evolved over time. The analysis covers catalog growth, content type distribution, top producing countries, audience targeting, and genre representation, with the goal of translating raw data into business insights.

## Dataset
* Source: Kaggle - Netflix Movies and TV Shows Dataset
* Size: 8,807 titles, 12 variables
* Key columns: type, country, date_added, rating, duration, listed_in

## Tools
- Python 3
- pandas
- matplotlib
- Google Colab

## Data Cleaning
- Filled missing director, cast, and country values with "Unknown"
- Dropped rows with missing date_added, rating, or duration
- Checked and confirmed no duplicate rows
- Converted date_added to datetime format
- Split duration into duration_minutes (Movies) and duration_seasons (TV Shows)

## Business Questions

1. Has Netflix been growing its catalog over the years, or is growth slowing down?
2. How has the balance between Movies and TV Shows shifted over the years?
3. Which countries are the largest content producers?
4. What audience is Netflix primarily targeting based on content ratings?
5. Which genres have the highest representation, and which are underserved?

## Key Findings
1. Growth was slow through 2015, then surged from 2016 to 2019 (peak of 2,000+ titles in 2019), before slowing in 2020-2021.
2. Movies have consistently outpaced TV Shows, despite steady TV Show growth since 2016.
3. United States leads (2,809 titles), followed by India (972) and the UK (418), with a sharp drop-off after that.
4. Over 60% of titles are rated TV-MA or TV-14, showing a focus on mature audiences. Family content (TV-G, TV-Y, TV-Y7) is underrepresented.
5. International Movies and Dramas dominate the catalog. Kids' TV and Docuseries are underrepresented.
