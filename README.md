# Heroes of Pymoli Player Analysis 
Using data from a hypothetical MMORPG called Heroes of Pymoli I used pandas to analyze player behaviors regarding purchases from the in-game store. 

**Player count**
* diplay total number of players: 

![Player Count](/README_images/player_count_df)

**Purchasing Analysis (Total)**
* Run basic calculations to obtain number of unique items, average price, etc.
* Create a summary data frame to hold the results
* Optional: give the displayed data cleaner formatting
* Display the summary data frame

![Purchasing Analysis (total)](/README_images/purchasing_analysis_total)

**Gender Demographics**
* Percentage and count of male players
* Percentage and count of female players 
* Percentage and count of Other/Non-Disclosed 

![Gender demographics](/README_images/gender_demographics_data)

**Purchasing Analysis (Gender)**
* Run basic calculations to obtain purchase count, avg. purchase price, avg. purchase total per person etc. by gender 
* Create a summary data frame to hold the results 
* Optional: give the displayed data cleaner formatting 
* Display the summary data frame 

![Purchasing Analysis (gender)](/README_images/purchasing_analysis_gender)

**Age Demographics** 
* Establish bins for ages
* Categorize the existing players using the age bins. Hint: use pd.cut()
* Calculate the numbers and percentages by age group
* Create a summary data frame to hold the results
* Optional: round the percentage column to two decimal points
* Display Age Demographics Table

![Age Demographics](/README_images/age_demographics)

**Purchasing Analysis (Age)**
* Bin the purchase_data data frame by age
* Run basic calculations to obtain purchase count, avg. purchase price, avg. purchase total per person etc. in the table below
* Create a summary data frame to hold the results
* Optional: give the displayed data cleaner formatting
* Display the summary data frame

![Purchasing Analysis (Age)](/README_images/purchasing_analysis_age)

**Top Spenders** 
* Run basic calculations to obtain the results in the table below
* Create a summary data frame to hold the results
* Sort the total purchase value column in descending order
* Optional: give the displayed data cleaner formatting
* Display a preview of the summary data frame

![Top Spenders](/README_images/top_spenders)

**Most Popular Items**
* Retrieve the Item ID, Item Name, and Item Price columns
* Group by Item ID and Item Name. Perform calculations to obtain purchase count, item price, and total purchase value
* Create a summary data frame to hold the results
* Sort the purchase count column in descending order
* Optional: give the displayed data cleaner formatting
* Display a preview of the summary data frame

![Top Items](/README_images/top_items)

**Most Profitable Items**
* Sort the above table by total purchase value in descending order
* Optional: give the displayed data cleaner formatting
* Display a preview of the data frame

![Most Profitable items](/README_images/most_profitable_item)
