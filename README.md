# team8-capitalbikeshare-ridership
## Analysis and Data Visualization of Capital Bikeshare Ridership dataset
The project analyzes and visualizes ridership data from the Capital Bikeshare dataset, which contains hourly information on weather, season, time of day, and bike rental counts. The goal is to identify trends and patterns in bike rental programs when taking into account factors like weather, time of day, month of the year, season, etc.

# User Installation Instructions
## 1. Prerequisites
Python 3.9 or higher

pip (Python package manager)

## 2. Clone the repository
- Run IDE of choice (I'm using Google Colab)
- Run the following cells:
- !git clone https://github.com/sjsu-cs133-s26/team8-capitalbikeshare-ridership.git
- %cd team8-capitalbikeshare-ridership
- Download hour.ipynb
- Upload hour.ipynb to IDE of choice

### Example Output:
![Example Output](https://github.com/anthony-tan-sjsu/team8-capitalbikeshare-ridership/raw/main/example_output.png)

## 3. Install Dependencies
- Run the following cell: !pip install pandas numpy matplotlib seaborn

### Example Output:
![Example Output](https://github.com/anthony-tan-sjsu/team8-capitalbikeshare-ridership/raw/main/example_output_2.png)

## 4. Run all cells to see analysis and data visualizations

# Research Questions:
- How does temperature affect bike ridership across different seasons and times of day?
- How does bike ridership vary by season? Which seasons see the highest ridership?
- To what extent is bike usage driven by work commuting patterns versus leisure, and how does this differ by season?

# Key Findings:
Temperature has a clear positive effect on bike ridership, with higher temperatures generally leading to increased usage.

![Example Output](https://github.com/anthony-tan-sjsu/team8-capitalbikeshare-ridership/raw/main/ridership%20count%20vs%20temperature.png)

Bike ridership varies significantly by season. The boxplot shows that Summer has the highest overall ridership with the highest median and mean. Spring and Fall have similar levels of ridership, both moderately high. Winter has the lowest ridership.

![Example Output](https://github.com/anthony-tan-sjsu/team8-capitalbikeshare-ridership/raw/main/ridership_count_by_season.png)

Bike ridership is strongly influenced by commuting patterns, as shown by the scatterplot by time of day across all seasons. The peak hours of 8 am and 5 pm align with typical work commute times, indicating that many users rely on bike-sharing for transportation. As for leisure behaviour, we see that warmer seasons consistently have higher counts observed even at non-peak times. Overall, people tend to rely more on bike-sharing during warmer seasons for both work commute and leisure
![Example Output](https://github.com/anthony-tan-sjsu/team8-capitalbikeshare-ridership/raw/main/ridership_count_vs_hour_by_season.png)

# Contributors
Omar Adrianne Bapora, Manit Khanna, Thet Noe, Antony Tan
