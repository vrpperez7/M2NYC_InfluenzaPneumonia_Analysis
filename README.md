# Department of Health and Mental Hygiene Analysis

## Project Overview
We're assisting the Department of Health and Mental Hygiene within NYC to explore which areas need medicine most. We investigated the data to gain further insight of boroughs in NYC and their frequency of influenza/pneumonia visits.

# Which borough needs more influenza/pneumonia medication?

## Data Cleaning

- Took a random sample of 50,000 encounters in the hospital between the years of 2020-2022. <r/>
- Crossed referenced our sample with larger data set to check for similar ratios of zip codes. (zip code 10000 is least represented) <br/>
<img width="297" height="241" alt="Screenshot 2025-07-17 at 10 59 29 AM" src="https://github.com/user-attachments/assets/40853560-ca50-4d38-b23a-d0d41d73abd3" />
<br/>
- Removed time from "date" column for more utility. <br/>
- Changed "date" column to DateTime for our visualizations. <br/>
- Renamed "mod_zcta" to "zip_code" for legibility. <br/>
- Created new column for "borough" by filtering and using a for loop through "zip_code" column. <br/> <br/>
<img width="205" height="131" alt="Screenshot 2025-07-17 at 10 59 37 AM" src="https://github.com/user-attachments/assets/0ac68e00-08e5-4750-bc49-e6a572fa71a1" />
<br/>

## Medical Analysis
1. Brooklyn has the **HIGHEST** number of pneumonia/infleunza visits.

<br/>
<img width="582" height="436" alt="Screenshot 2025-07-17 at 11 23 30 AM" src="https://github.com/user-attachments/assets/d58849fc-a775-4c5d-a0e3-1517ad485429" />
<br/>
<br/>

2. Brooklyn has the **HIGHEST** number of pneumonia/infleunza admissions.

<br/>
<img width="792" height="602" alt="Screenshot 2025-07-17 at 11 35 21 AM" src="https://github.com/user-attachments/assets/d06bb7e9-70a1-4b37-a049-6bd0f7b9f2fb" />
<br/>
<br/>

3. Brooklyn's pneumonia/influenza visits has had the **HIGHEST RATE** of increase between all boroughs from the years 2020-2022.

<br/>

<img width="954" height="512" alt="Screenshot 2025-07-17 at 11 23 16 AM" src="https://github.com/user-attachments/assets/42cbd123-1e75-4856-b845-d5f72751e8d4" />

<br/>
<br/>

## As shown in our analysis, we recommend sending more influenza/pneumonia medicine to Brooklyn due to:
The **severity** of infleunza/pneumonia visits, as Brooklyn had the most admissions as shown in analysis 1.

<br/>

The **frequency**  of visits due to influenza/pneumonia as shown in analysis 2.

<br/>

**Over time**, Brooklyn has consistently had the **highest** trajectory over the past two years as shown on analysis 3.

<br/>
If you'd like to know more about the sample we used, check out our Dashboard:
<br/>
Tablaeu Dashboard: https://public.tableau.com/app/profile/thomas.segal/viz/Book1_17526901770690/Dashboard?publish=yes

<br/>
<br/>

## Reflection:

- We focused mainly on visits as frequency highlights the demand for medication in a borough. <br/>
- Our most important insight is the understanding of why boroughs have the numbers they do. We then were able to specify which borough needs the most medicine. <br/>

## 4/3 UPDATES to Tableau:
### Seasonality
- Now contains a filter to adjust for the seasons (Winter, Fall, Spring, Summer).
    - Useful to specify seasonal differences between boroughs.

### KPIs
- Two KPIs implemented for total amount of hospital visits and admissions to highlight magnitude.
- Compares 2021 to 2022 year-over-year and finds percent difference.
    - Numbers change when adding filters for more interactivity.

## April 3 Updates (Tableau):
### Seasonality
- Added a season filter (Winter, Spring, Summer, Fall).
- Enables comparison of seasonal patterns across boroughs.
- Helps highlight how trends vary depending on the time of year.

### Key Performance Indicators (KPIs)
- Introduced two KPIs:
    - Total hospital visits
    - Total admissions
- Displays year-over-year comparison (2021 vs. 2022) with percentage change.
- KPIs dynamically update based on selected filters for more interactive analysis.

### Linked Ins:
Thomas: https://www.linkedin.com/in/thomas-segal-093370369
<br/>
Vincent: https://www.linkedin.com/in/thevinceperez/
<br/>
<br/>
Used dataset for educational purposes.
