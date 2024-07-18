# IPL-Dashboard---POWER-BI

## Problem Statement

This dashboard provides comprehensive insights into the Indian Premier League (IPL). It allows stakeholders to analyze player performance, team statistics, and match outcomes. By examining various metrics, such as runs scored, wickets taken, and match results, the dashboard helps identify trends, strengths, and areas for improvement for teams and players.




### Steps followed 

- Step 1: Load data into Power BI Desktop. The dataset is a CSV file.
- Step 2: Open Power Query Editor and enable "Column Distribution," "Column Quality," and "Column Profile" options under the Data Preview section in the View tab.
- Step 3: Ensure column profiling is based on the entire dataset, as the default profile considers only 1000 rows.
- Step 4: Identify and handle errors or empty values. Observations showed some columns contained null values.
- Step 5: Null values were excluded from calculations to maintain accuracy, especially in key metrics like player averages and total runs.
- Step 6: In the Report view, a theme was selected to ensure visual consistency.
- Step 7: Added visuals to represent key metrics, such as total runs, wickets, and match outcomes.
- Step 8: Visual filters (Slicers) were added for fields like "Team," "Player," "Season," and "Venue."
- Step 9: Card visuals were added to display key statistics, such as highest run-scorer, leading wicket-taker, and average match score.
- Step 10: Created bar charts to compare team performances, player statistics, and match results across different seasons.
- Step 11: Line charts were used to show trends over seasons, such as changes in average scores or win rates.
- Step 12: Created calculated columns and measures using DAX for more in-depth analysis. For example, calculating strike rates, economy rates, and average scores.
- Step 13: Added text boxes for titles and descriptions to provide context for each visual.
- Step 14: Incorporated images and logos for IPL teams and sponsors to enhance the visual appeal.
- Step 15: Published the report to Power BI Service for sharing and collaboration.

# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] Player Performance



           Top Run-Scorer: Player Name with Number of Runs runs.
    Leading Wicket-Taker: Player Name with Number of Wickets wickets. 
           
### [2] Match Analysis

    a) Average Runs per Match: Average Runs runs.
    b) Average Wickets per Match: Average Wickets wickets.
  
   
  
  ### [3] Team Statistics 
  
      a) Highest Team Score: Team Name with Score runs.
      b) Most Wins: Team Name with Number of Wins wins.


 ### [4] Seasonal Trends
 
     a)Increase in Average Score: Percentage Increase from Year 1 to Year 2.
     b)Winning Trends: Team Name shows a consistent winning trend over the last Number of Seasons seasons.

### [5] Key Insights
     a)Player Performances: Highlighting standout performances by individual players in various metrics.
     b)Team Comparisons: Analyzing how different teams have performed over the seasons.
     c)Match Outcomes: Understanding the factors that lead to wins or losses in matches.

By leveraging these insights, stakeholders can make informed decisions to enhance team strategies, player training, and overall performance in the IPL.
