
# Prodigy Infotech Internship Task 04

This repository contains the work completed for Task 4 of my Prodigy Infotech internship, which involves the analysis and visualization of sentiment patterns in social media data, specifically Twitter messages. Using a dataset with three sentiment categories—Positive, Negative, and Neutral—this project aims to gain insights into public opinion and attitudes toward various topics or entities.
## Dataset

The project uses a Twitter sentiment analysis dataset containing:

* Training Data: Used to build and test the sentiment analysis pipeline.

Each data entry consists of:

* Entity: The target entity (e.g., product or person) being analyzed.
* Message: The tweet text.
* Sentiment: The associated sentiment (Positive, Negative, Neutral).
## Tools and Libraries:

* Jupyter notebook 
* pandas, numpy for data manipulation.
* matplotlib, seaborn for visualizations.
## Key Steps

1. Data Loading and Preprocessing:

* The dataset is loaded from a CSV file, and the columns are manually named as Entity, Sentiment, and Message.
* The train_data dataframe is cleaned by renaming columns for better understanding.
* The shape and summary statistics of the data are printed to provide an overview of the dataset's structure.

2. Sentiment Distribution Visualization:

* Countplot: A countplot is created to visualize the distribution of sentiment labels (Positive, Negative, Neutral) in the dataset. The plot is color-coded based on sentiment and shows the frequency of each sentiment category.
* The legend is removed for a cleaner plot.

3. Entity Frequency Analysis:

* Top Entities: The top 10 entities mentioned in the dataset are identified by counting the occurrences of each entity in the Entity column.
* A bar chart is created to show the top 10 entities based on the number of mentions.

4. Sentiment Distribution by Entity:

* Group-by Operation: The data is grouped by Entity and Sentiment to calculate the sentiment distribution for each entity.
* A stacked bar chart is plotted for the top 5 entities, showcasing the sentiment breakdown (Positive, Negative, Neutral) for each entity.
* The chart uses a coolwarm colormap to distinguish between sentiment categories visually.

5. Pie Chart of Sentiment Distribution:

* A pie chart is generated to visualize the proportion of each sentiment (Positive, Negative, Neutral) in the dataset.
* The segments of the pie chart are color-coded (orange for Positive, lightgreen for Neutral, salmon for Negative), and the percentages are displayed for each sentiment.

6. Pie Chart of Top 5 Entities by Mention:

* The top 5 entities by mention count are identified and displayed in a pie chart.
* The chart visually shows the share of mentions for each of the top 5 entities, with each segment representing a specific entity. Different colors are used for distinction.
## Conclusion

It provides insights into the sentiment distribution across the dataset, sentiment breakdown for top entities, and a deeper look into the most frequently mentioned entities through both bar and pie charts. The analysis is aimed at understanding sentiment trends in relation to specific entities mentioned in tweets.

Thank you for reviewing my submission!