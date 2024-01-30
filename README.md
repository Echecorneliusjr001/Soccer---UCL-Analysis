# Soccer---UEFA Champions League-Analysis
An insight uncovering trends, player performances, and club achievements through analysis.

# UEFA Champions League-Analysis
An analysis of the UEFA Champions League that is viewed worldwide by various nations. It uncovers insights based on the coaches, Players, Clubs, and Countries' Appearances & performances.

## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Recommendations](#recommendations)

- ### Project Overview
  ---

The "UEFA Champions League-Analysis(1992-2022)" project: In the ever-evolving world of football, the UEFA Champions League stands as a pinnacle, showcasing the brilliance of clubs, coaches, and players on the grandest stage. The project "UEFA Champions League-Analysis(1992-2022)" is a comprehensive exploration using a blend of advanced data analysis tools including Tableau, Pandas, Plotly, Seaborn, and Matplotlib within the Jupyter Notebook environment.
The primary goal of this project is to delve into the intricate details of the UEFA Champions League spanning from 1992 to 2022, unraveling compelling insights that transcend the boundaries of the game.


  ### Data Sources
  Data Sources:
The primary data source is a dataset containing information about the Champions League from the 1992/93 season to the 2021/22 season. The dataset includes details such as Top club by scored goals,  Top clubs by games played, Top 5 all-time winners ranking, top 10 players by most goals, top 10 players by total appearances, top 10 countries by titles won, and more.
  

  ### Tools
- Python Libraries
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn
- Plotly
- Tableau


  ### Data loading, cleaning & Preparation
  
Load the dataset(Excel & CSV files) into the Jupyter Notebook using Pandas.
Perform data preprocessing, which may involve data describing, the number of duplicates if present, and removing unnamed index columns, and duplicates.

  ### Data Analysis
  
  Include some interesting code/features worked with
  
  ---
       
    
**To find the values of the aggregate functions in two decimal places
df15.describe().round(2)

output result:

Goals
count-186.00, mean-20.11, std-16.44, min-10.00, 25%-11.00, 50%-15.00, 75%-21.00, max-140.00


  ---
  
  ### Exploratory Data Analysis (EDA)

  Here's an exploratory data analysis with some questions to answer, the analysis includes the following key aspects:

- Identify the player with the highest number of goals.
- Identify the player with the highest number of appearances in a season and the history of the Champions League.
- Identify the top 10 Coaches with the highest number of appearances.
- Explore the countries with the highest number of titles in the history of the Champions League.
- Identify the top 10 players by most goals.
- Identify the top clubs by games played.
- Identify the top clubs by goals scored.
- Determine the top 10 players by most appearances.
- Identify the top 5 all-time winners' ranking.
  


  

  ### Results/Findings
  
  Here is the findings for the questions;
  **1. 2017 was the year with the highest count of shows.**
  
  ![Highest count of shows](https://github.com/Echecorneliusjr001/Netflix-EDA-Visualization/assets/149030759/fa643e36-29fa-422f-81ae-6aaef890c1bb)

 **2. More movies were showed on netflix than TV shows.**
 
  ![Movies VS TV shows](https://github.com/Echecorneliusjr001/Netflix-EDA-Visualization/assets/149030759/909ea3d5-2ec8-4c40-901b-50e16a654c31)

  **3. Movies are the most prevalent on Netflix.**
  
  **4. United States of America has the highest contribution to netflix content.**
  
  **5. The United states of America leads in all categories.**
  ![Top 10 countries](https://github.com/Echecorneliusjr001/Netflix-EDA-Visualization/assets/149030759/44acf179-ba7e-4e09-b145-2c17e9609bb0)

  **6. TV-MA has the highest rating category with the highest count.**
  ![Ratings](https://github.com/Echecorneliusjr001/Netflix-EDA-Visualization/assets/149030759/d7bcc424-8f26-485c-8b2a-8b3f1f08390d)

  **7. Documentaries is the genre with the highest count.**
  ![Top 5 genre](https://github.com/Echecorneliusjr001/Netflix-EDA-Visualization/assets/149030759/e82f2c47-041b-4d95-8b7a-9853b4815fc5)

    
    
### Recommendations
  

Based on the insights gathered from the analysis of Netflix content between 2011 and 2017, the following recommendations can be made:

- Diversify TV Shows: While movies are prevalent on Netflix, there is an opportunity to diversify and expand the library of TV shows. Consider investing in original and engaging TV series to attract a wider audience, especially viewers who prefer episodic content.

- Global Partnerships: Given the significant contribution of the United States to Netflix content, continue collaborating with U.S.-based production companies and creators. Additionally, explore partnerships and content acquisition from other countries to further diversify the platform.

- Content Ratings: Recognizing that TV-MA is the highest-rated category with the highest count, focus on producing content that caters to mature audiences while ensuring content in other rating categories is also available to meet various age group preferences.

- Documentaries: Given the popularity of documentaries, consider producing more high-quality documentary content that covers a wide range of topics. This genre has a broad appeal and can attract a diverse audience.



### Contributions
In line with the insights gained, Netflix could collaborate with content creators, production companies, and filmmakers to achieve the following:

- Content Diversity: Collaborate with global filmmakers and production companies to create diverse content, including TV shows, to cater to a wider international audience.

- Original Series: Collaborate with creative talents to produce unique and engaging TV series that can capture the attention of viewers who prefer serialized storytelling.

- Quality Documentaries: Partner with documentary filmmakers and researchers to develop high-quality documentaries on a variety of topics, ensuring that this popular genre continues to thrive on the platform.

- Viewer-Driven Content: Collaborate with content creators to produce shows and movies that align with viewer preferences and demographic data to maintain and expand Netflix's global reach.

By following these recommendations and engaging in strategic collaborations, Netflix can continue to provide an extensive and diverse content library that meets its subscribers' evolving demands and interests. 📺🤝 #Netflix #ContentStrategy #Contributions

### Limitations
Using Plotly. express and Matplotlib to obtain the visualization was a lot, so I decided to run a few of the visualizations with Seaborn to get the visualizations 
ready to go with the kind of data I had in my dataset.

I had some encoding issues while reading various files(Excel & CSV files), so I had to use the 'latin1'.


### References
 Seaborn Cheatography by Sanjeev95
 AlextheAnalyst
 
 Champions League dataset (Website).
