# Air Passenger Time-Series Analysis 
## Project Overview
This project performs an Exploratory Data Analysis (EDA) on a historical aviation dataset containing monthly passenger totals from 1949 to 1960. The analysis focuses on uncovering seasonal patterns, long-term growth trends, and the cyclical nature of air travel using Python's data science ecosystem. 
## Dataset Attributes
The dataset consists of three primary features:
- Year: The specific year of observation (1949–1960).
- Month: The month of the flight trip.
- Passengers: The total number of passengers (in thousands) for that period. 
## Analysis Highlights & Methodology
- Time-Series Visualization: Utilized Seaborn's lineplot to visualize the consistent upward trajectory of global air travel over the 12-year period.
- Seasonality Profiling: Created box plots and bar charts to identify peak travel months (e.g., July and August) versus off-peak seasons.
- Heatmap Matrix: Pivoted the data using Pandas pivot() to generate a Seaborn heatmap, providing a color-coded overview of passenger density across months and years.
- Growth Rate Calculation: Computed year-over-year percentage increases to quantify market expansion during the post-war aviation boom. 
## Key Insights
 -Consistent Growth: There is a clear, linear increase in passenger numbers year-over-year, reflecting the rapid expansion of the airline industry.
- Summer Surges: July and August consistently show the highest passenger counts across all years, indicating strong holiday seasonality.
- Low Variance in Winter: February often represents the lowest travel volume, though it still follows the overall annual growth trend. 
## Technologies Used
 -Python 3.x
- Pandas: Data manipulation and pivoting.
- Seaborn & Matplotlib: Statistical data visualization.
- Jupyter Notebook: Interactive development environment
