# WeRateDogs-Data-Wrangling
This project wrangled WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations. Below is a breakdown of the 4 steps used in this project.
Step 1 : Data was gathered from 3 resources:
the first was already downloaded and stored locally (file name: twitter_archive_master.csv), the second was downloaded from an url, (file name: twitter_predict.csv),
the third was acquired from Twitter API. (file name: selected_attr.csv).
Step 2 : Data gathered from these 3 sources was then assessed in this step. 10 data quality issues and 2 tidiness issues were identified from all three files. All the identified issues were documented in the Jupyter Book, in the “Summary for Step 2 (Assess)” section.
Step 3: This step intended to solve the issues identified in the last step. All three datasets were cleaned. For example, data types were modified and missing values were addressed. Also, some columns were combined to make sure each variable forms a column. For example, the four columns “doggo, floofer, pupper, puppo” all described the stage of the dog. Therefore, one new column was created to represent this information. At the end of Step 3, all three datasets were combined, and only columns meaningful for the purpose of this analysis were included. The final combined, clean dataset was store in the file: twitter_archive_master_clean.csv.
Step 4: Based on data in the final cleaned dataset, analysis and visualization was conducted. Four questions were addressed in this last step.
• 1 In which hours do Tweets receive more favorites?
• 2 In which hours do Tweets get more retweets?
• 3 Is there a relationship between rating and favourites?
• 4 Is there a relationship between rating and retweet?
However, the main goal of this project is to gain experience in gathering, assessing, and cleaning data. Therefore, Step 1 to Step 3 were the focus of this project.
