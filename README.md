# Soccer---UEFA Champions League-Analysis (UCL)
An insight uncovering trends, player performances, and club achievements through analysis.

# UEFA Champions League Analysis
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
- Identify the player with the highest number of appearances in the history of the Champions League.
- Identify the top 10 players by most goals.
- Determine the top 10 players by most appearances.
- Identify the top 10 Coaches with the highest number of appearances.
- Explore the countries with the highest number of titles in the history of the Champions League.
- Identify the top clubs by games played.
- Identify the top clubs by goals scored.
- Identify the top 5 all-time winners' ranking.
  


  ### Results/Findings
  
  Here are the findings for the questions;
  **1. Top 10 players with the highest number of appearances in the history of the Champions League.**

 *Visual in Python using Matplotlib library.*

 ---
  ### Code
<img width="677" alt="Matplotlib code for Players by Appearance" src="https://github.com/Echecorneliusjr001/Soccer---UCL-Analysis/assets/149030759/4bb23c95-46de-474b-b069-ea108e9816cc">

 ---

 *output result:*
 
<img width="960" alt="Players by Total Appearances-py(Matplotlib)" src="https://github.com/Echecorneliusjr001/Soccer---UCL-Analysis/assets/149030759/e93a5ae6-2f74-4f1c-bc8d-cbaa40bb4684">


 *Visual in Python using Plotly library.*

 ---
   ### Code
 <img width="683" alt="Code for Players by appearances (Plotly)" src="https://github.com/Echecorneliusjr001/Soccer---UCL-Analysis/assets/149030759/46cadc3f-59be-428b-b000-0410af3b9c2c">



 ---
 *output result:*
  
  <img width="960" alt="Players by Most Appearances-Py(Plotly)" src="https://github.com/Echecorneliusjr001/Soccer---UCL-Analysis/assets/149030759/24cbd013-56fe-4a35-a8c3-f03e050bce14">

  
  *Tableau Dashboard Visual*
  
  <img width="960" alt="Players by Total Appearances" src="https://github.com/Echecorneliusjr001/Soccer---UCL-Analysis/assets/149030759/b02028e3-3d6a-40e0-9caf-06a5e601aaff">


 **2. Top 10 players with the highest number of goals in the history of the Champions League.**

  *Visual in Python using Plotly library.*

---
   ### Code
<img width="683" alt="Code for players by goal (Plotly)" src="https://github.com/Echecorneliusjr001/Soccer---UCL-Analysis/assets/149030759/0e6f64ce-22d0-4e23-9e7d-e5cd8cabcc07">

 ---
 *output result:*
 
<img width="960" alt="Players by Most Goals-Py(Plotly)" src="https://github.com/Echecorneliusjr001/Soccer---UCL-Analysis/assets/149030759/6c3af0d1-d8ad-411f-b864-7b69f24a49b3">

  *Tableau Dashboard Visual*

<img width="960" alt="Players by Most Goals" src="https://github.com/Echecorneliusjr001/Soccer---UCL-Analysis/assets/149030759/64892868-b5a8-4ae5-963c-58a8d24880c0">


  **3. Cristiano Ronaldo is the player with the highest number of goals & highest number of appearances in the history of the Champions League.**
  
  
  **4. The top 10 Coaches with the highest number of appearances.**

  *Visual in Python using Matplotlib library.*

  ---
   ### Code
<img width="688" alt="Code for Coaches by appearance (Matplotlib)" src="https://github.com/Echecorneliusjr001/Soccer---UCL-Analysis/assets/149030759/e09fc144-8bf3-45b1-9278-3c91e0809d76">

 ---
 *output result:*
  
  <img width="960" alt="Coaches by Total Appearances-Py(Matplotlib)" src="https://github.com/Echecorneliusjr001/Soccer---UCL-Analysis/assets/149030759/b1ba028e-cd6c-45fd-85ef-23db98eb566f">
  
  *Tableau Dashboard Visual*
  
  <img width="960" alt="Coaches by Total Appearances" src="https://github.com/Echecorneliusjr001/Soccer---UCL-Analysis/assets/149030759/f249f7cc-44a5-41b9-9ed0-a67c8fd2b57c">

  **5. The countries with the highest number of titles in the history of the Champions League.**

   *Visual in Python using Plotly library.*

---
   ### Code
<img width="673" alt="code for countries by Title (Plotly)" src="https://github.com/Echecorneliusjr001/Soccer---UCL-Analysis/assets/149030759/8ae7f781-5635-4cdc-987f-fcdc20ee3ca5">

 ---
 *output result:*
   
  <img width="960" alt="Countries By Most Titles-Py(Plotly)" src="https://github.com/Echecorneliusjr001/Soccer---UCL-Analysis/assets/149030759/bbdeee87-818d-4804-84f2-ea2b98e854d2">

  *A map plot showing locations/countries that have secured most of the UCL titles in history.*

  ---
   ### Code
<img width="679" alt="code for Map plot (Plotly)" src="https://github.com/Echecorneliusjr001/Soccer---UCL-Analysis/assets/149030759/f8ead107-29dd-4354-a18d-5ebb6ab28d0e">

 ---
 *output result:*
  
  <img width="960" alt="Map plot of Countries by Most Titles" src="https://github.com/Echecorneliusjr001/Soccer---UCL-Analysis/assets/149030759/c6b16684-b3a2-4ad8-be5e-be5fbe53339d">


  **6. The top clubs by games played & top clubs by goals scored.**

  *Top Clubs by Games Played- showing the number of games won and games lost*

  <img width="960" alt="Top Clubs by Games Played" src="https://github.com/Echecorneliusjr001/Soccer---UCL-Analysis/assets/149030759/5be4af97-ec5a-4b31-94f9-457202029df4">


  *Top Clubs by Goals Scored- showing the goals scored by the club and goals that were scored against them, whereby you can deduce their goal differences*
  
<img width="960" alt="Top Clubs by Goal Scored" src="https://github.com/Echecorneliusjr001/Soccer---UCL-Analysis/assets/149030759/38b73ab9-b1d2-4b40-a8e0-4cd363f19df1">

  **7. The top 5 all-time winners' ranking.**
  
*The Big Boys in the UEFA Champions League*
  
<img width="581" alt="Top 5 All Time Winners Ranking" src="https://github.com/Echecorneliusjr001/Soccer---UCL-Analysis/assets/149030759/c9bbc0fb-a396-47dc-95bf-9303c17f7879">


### Recommendations
  

Based on the insights gathered from the analysis of the Champions League between 1992/93 and the 2021/22 season, the following recommendations can be made:

  ## For Clubs:

- Real Madrid's Blueprint: Real Madrid stands out as the most successful club in the history of the Champions League. Clubs aspiring for continuous success should study Real Madrid's strategies, emphasizing consistency, quality recruitment, and a winning mentality.

- Strategic Recruitment: Clubs aiming to dominate should focus on strategic player recruitment, balancing experience and emerging talents. AC Milan and Liverpool FC's historical successes showcase the importance of building well-rounded squads.

- Emphasis on Goal Scoring: Bayern Munich and FC Barcelona's prominence is partly attributed to their goal-scoring prowess. Clubs should prioritize offensive strategies, ensuring a balance between attack and defense to create a formidable force.

  ## For Coaches:

- Learn from Sir Alex Ferguson: Sir Alex Ferguson's longevity and success make him a coaching icon. Aspiring coaches should adopt his leadership principles, emphasizing player development, squad management, and adapting tactics to various situations.

- Innovation in Coaching: Coaches like Josep Guardiola have demonstrated innovation in tactics and playing styles. Continuous learning, tactical flexibility, and adapting to evolving football trends are crucial for sustained success.

  ## For Players:

- Strive for Individual Excellence: Cristiano Ronaldo and Lionel Messi's goal-scoring records underscore the importance of individual brilliance. Players should focus on personal development, setting high standards for performance, and contributing consistently to their teams.

- Consistency in Appearances: Cristiano Ronaldo's remarkable number of appearances highlights the significance of consistent participation. Players aiming for long, successful careers should prioritize fitness, recovery, and smart workload management.

  ## For Countries:

- Invest in Football Infrastructure: Spain's dominance in UEFA Champions League titles indicates a robust football infrastructure. Countries should invest in youth development, coaching programs, and facilities to nurture talent from an early age.

- Competitive Domestic Leagues: Success in European competitions often correlates with the competitiveness of domestic leagues. Encourage competitive balance, financial stability, and fair competition within national leagues to prepare clubs for European challenges.

Moreover, the pursuit of UEFA Champions League success requires a combination of strategic planning, talent development, adaptability, and a relentless pursuit of excellence. Clubs, coaches, players, and countries should learn from the successes of historical giants while innovating and evolving to meet the demands of modern football.


### Contributions
  The contribution I've provided is a comprehensive strategy for elevating the UEFA Champions League to unprecedented levels of excellence. The key recommendations cover various aspects, including sustainability, coaching, player development, technology, international partnerships, environmental stewardship, and fan engagement. Here's a summary:

- Encouraging Sustainable Success:
UEFA is urged to introduce initiatives that incentivize clubs to invest in long-term success, reinforcing Financial Fair Play regulations for stability and strategic planning.

- Coaching Excellence Program:
A proposed UEFA Coaching Excellence Program aims to equip coaches with the latest methodologies through regular workshops, exposure to emerging tactics, and mentorship programs.

- Player Development Initiatives:
Collaboration with member nations is suggested to implement standardized player development programs, enhance grassroots structures, create pathways for young talents, and ensure quality standards in youth academies.

- Technological Integration:
Embracing technology is emphasized to enhance the viewer experience and officiating standards. This includes further investment in cutting-edge technologies like VAR for streamlined decision-making.

- Inclusive International Partnerships:
UEFA is encouraged to forge partnerships with football associations globally to promote international inclusivity. Collaborations on football development projects, coaching exchanges, and tournaments aim to foster a global football community.

- Environmental Stewardship:
Demonstrating leadership in environmental sustainability is proposed, with initiatives ranging from green stadium practices to carbon-neutral events, setting a standard for responsible sports management.

- Fan Engagement and Experience:
Prioritizing fan experience through digital platforms, immersive content creation, and facilitated fan interactions are highlighted. Enhancing accessibility and inclusivity aims to strengthen the Champions League's global fanbase.

In conclusion, the UEFA Champions League has the potential to evolve into a beacon of excellence, setting the standard for football competitions globally. The proposed recommendations, if implemented, could lead to a future where the Champions League continuously redefines the pinnacle of European football while honoring its rich history.


   ⚽🏆🌟🏟️ #UCL 🤝 #UEFA #VAR(Video Assistant Referee) #Contributions

### Limitations
  Using Plotly. express and Matplotlib to obtain the visualization was a lot, so I decided to run a few of the visualizations with Seaborn to get the visualizations 
  ready to go with the kind of data I had in my dataset.

  I had some encoding issues while reading various files(Excel & CSV files), so I had to use the 'latin1'.


### References
  Seaborn Cheatography by Sanjeev95.
  AlextheAnalyst.
  Champions League dataset (Website).
