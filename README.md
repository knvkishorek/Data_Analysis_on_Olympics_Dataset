# Data_Analysis_on_Olympics_Dataset
Data Analysis on Summer and Winter Olympics Datasets belonging to various countries

Input:
1. Winter Olympics Dataset
2. Summe Olympics Dataset
3. Various Countries Information

Tasks:
Explanatory Data Analysis Challenge
1. Data Import and Inspection
   1.1. Import the Datasets Summer, Winter, Dictionay and Inspect
2. Merging and Concatenating
   2.1. Merge Summer and Winter (one row for each Medal awarded in any Olympic Games) and save the mergerd DataFrame in olympics
   2.2. An additional column (eg: Edition) shall indicate the Edition -> Summer or Winter
   2.3. Add the full Country name from dictionary to olympics (eg: France for FRA)
3. Data Cleaning (Part 1)
   3.1. If you haven't done it yet: Assign appropriate Column Headers to Country Codes (eg: Code) and full Country Names (eg: Country)
   3.2. Remove Spaces from column headers in olympics and dictionary
   3.3. For some country codes, there is no corresponding full country names (eg: URS) -> missing values in olympics. Identify these county codes and search the Web for the full country names. Replace the missing values
4. Data Cleaning (Part 2)
   4.1. Remove rows from olympics where the country code is unknown (Make sure you reset the Index -> RangeIndex)
   4.2. Convert the column Medal into an odered Categorical column (Bronze < Sivler < Gold)
5. What are the most successful countries of all times ?
  - For the next questions, use Seaborn plots
   5.1. What are the Top 10 Counties by total medals ?
   5.2. Split the total medals of Top 10 countries into Summer/Winter. Are there typical Summer/Winter Games Countries ?
   5.3. Split the total medals of Top 10 countries into Gold, Silver, Bronze
6. Do GDP, Population and Politics matter
   6.1. Create the following aggregated and merged DataFrame with Top 15 countries (you can see an excerpt with the first 12 countries). The column Total_Games shows the number of participants (as an approximation, determine the number of editions where countries have won at least one medal)
   6.2. Convert the absolute values in the dataframe into ranks and save the ranks dataframe in new variable (see screenshot). Ranks are more meaningful than absolute numbers
7. Statistical Analysis and Hypothesis Testing with scipy
   7.1. In the following, work with Ranks. Check whether GDP (standard of living), Total_Games (Political stability measure) and Population (Size) have an effect on Total Medals (hint: work with spearman correlation, not with pearson correlation)
8. Aggregating and Ranking
   8.1 Create the following Seaborn Heatmap with Medal Ranks for Top 50 Countries (Total Medals, Summer Games Medals, Winter Games Medals, Men, Women)
9. Summer Games vs Winter Games - does Geographical Location matter ?
   - Identify Countries that are
   9.1. equally seccessful in Summer and Winter Games
   9.2. more successful in Summer Games
   9.3. more successful in Winter Games
   - What could be the reason ?
10. Men vs Women - does Culture & Religion matter ?
   - Identify countries where
   10.1. Men and Women are equally successful
   10.2. Men are more successful
   10.3. Women are more successful
   - What could be the reason ?
11. Do Tradition matter ?
   11.1. Create the following Seaborn Heatmap that showsthe Ranks of Top 50 Countries by Sports
   11.2. Identify traditional sports/national sports for eg. UK and China.

Output:
Ref, Olympics_Case_Study_Output.PNG
