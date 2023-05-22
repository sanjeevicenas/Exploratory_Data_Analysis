# Capital Bike Sharing Company Exploratory_Data_Analysis

In this project, I worked with a dataset containing hourly bike sharing data. I used Python and various libraries like pandas, matplotlib, and seaborn to analyze and visualize the dataset. Let me walk you through the key concepts involved."
"Firstly, I loaded the dataset using the pandas library's read_csv() function, which allowed me to bring the data into a DataFrame, a tabular data structure in pandas. This step was crucial as it provided a convenient and structured way to work with the dataset."

"Once the data was loaded, I performed Exploratory Data Analysis (EDA) to understand the dataset better. I used the head() function to display the first few rows of the dataset, giving me a quick glimpse of the data. Additionally, I calculated summary statistics like mean, median, standard deviation, minimum, maximum, and descriptive statistics using the mean(), median(), std(), min(), max(), and describe() functions respectively. These statistics helped me gain initial insights into the distribution and characteristics of the data."

"To dive deeper into the dataset, I utilized data slicing and subsetting techniques. The loc() method allowed me to extract specific rows and columns based on criteria. For example, I retrieved rows between indices 2 and 4 and selected the 'registered' column for analysis. This enabled me to focus on specific subsets of the data and perform calculations or visualizations as needed."

"Data aggregation and grouping were other important concepts I utilized in this project. I employed the groupby() function to group the data based on certain columns, such as 'season' or 'hour', and calculated aggregate statistics within each group. This allowed me to explore patterns and trends specific to different seasons or hours of the day."

"To gain a visual understanding of the dataset, I created various types of plots. For instance, I generated scatter plots to examine the relationship between the hour and the bike sharing count. I also created line plots to compare the number of casual and registered riders over the first two days. Additionally, I utilized box plots to visualize the distribution of ridership counts grouped by the hour of the day. Histograms were useful in displaying the frequency distribution of the bike sharing counts."

"To explore the relationships between variables, I performed correlation analysis. I calculated the correlation coefficients between variables such as 'casual' and 'registered', or 'temperature' and 'humidity'. I visualized the correlation matrix using a heatmap, which provided a quick overview of the strength and direction of these relationships."

"In summary, this project demonstrated my proficiency in loading and exploring data using pandas, performing data slicing and aggregation, and creating various types of plots for data visualization. It also showcased my ability to analyze correlations between variables. These concepts were essential in gaining insights from the dataset and communicating findings effectively. Overall, this project highlights my strong skills in data analysis and visualization using Python."
