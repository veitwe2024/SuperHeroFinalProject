# SuperHeroFinalProject

# Cleaning and formatting Data
Drops na values and columns I'm not interested in like "url", "hair-color", "eye-color", "race", "relatives", and "group-affiliation". 
Also fills in missing values in the alignment columns based off of information found through a few google searches. 
Changes all alignment values so "good"=1, "neutral"=0, and "bad"=-1. 

# Basic Statistics
uses the .describe() function to create a table of mins, maxes, means, std., etc.

# Pie Chart
Creates a pie chart of the alignment column with % included.

# Finding the Most Powerful Character
Character with the highest speed, strength, durability, and power values. 
Ran multiple masks to find top 5 characters. 

# Finding Most Intelligent Character
Ran mask similar to previous to find all characters with intelligence = 100. 

# Finding Most Skilled Combatants
Yet another mask, but this time for all character with combat = 100. 
Lots of Batmen in this list.

# Finding Significant Correlations Between Columns
Creates a correlation table of all numerical columns of data. 
Then stores column names as variables for easy use later.
Creates linear regression models for Strength vs Durability and Intelligence vs Combat. 
Creates a pivot table of Intelligence and alignment withsum function used on alignment. 
Creates a bar chart from the pivot table info.

# Machine Learning
Makes algorithm to predict alignment of characters based on intelligence, speed, strength, and durability. 
Creates a number of nearest-neighbors vs accuracy graph to find optimal number of neighbors. 
Creates a contingency table to display predictions.

