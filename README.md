# Analysis of Liberal Democracy Trends
## Political Data Analytics Project

This project explores global patterns and dynamics of liberal democracy using the Varieties of Democracy (V-Dem) dataset. It performs data preprocessing, visualization, and basic statistical analysis to understand how liberal democratic values have evolved over time and across regions.
 # Overview 
Load and inspect the V-Dem dataset

Handle missing data and clean key indicators

Visualize trends in liberal democracy across countries and years

Identify countries with increasing or declining democratic scores

Generate insights that can inform political or socio-economic research

Dataset: V-Dem (V14)
Source: [Varieties of Democracy (V-Dem) Institute](https://www.v-dem.net/).

Variables: Political rights, civil liberties, electoral systems, judiciary independence, etc.

Timeframe: Covers multiple decades and over 200 countries

# Tools 
| Library        | Purpose                          |
| -------------- | -------------------------------- |
| `pandas`       | Data handling and transformation |
| `seaborn`      | Visualization                    |
| `matplotlib`   | Plotting trends                  |
| `numpy`        | Numerical operations             |
| `Google Colab` | Cloud-based execution platform   |

Methodology
Data Loading

Dataset loaded from Google Drive using pandas

Preprocessing

Handling missing values

Filtering relevant columns (e.g., democracy index, country, year)

Data type conversions

Exploratory Data Analysis

Trend plots for liberal democracy over time

Comparison between regions (e.g., Africa vs. Europe)

Highlighting outliers or rapid transitions

📈 Example Visualizations
Line plot of liberal democracy index over time by region

Bar chart of top/bottom countries in recent years

Heatmaps showing regional democratic shifts

📌 Future Enhancements
Apply clustering (e.g., k-means) to group countries by democratic similarity

Predict future democracy scores using time-series models

Integrate other indicators (GDP, education, media freedom)

✅ How to Run
Upload the notebook to Google Colab

Mount your Google Drive to access the dataset

Run each cell in sequence:

python
Copy
Edit
from google.colab import drive
drive.mount('/content/drive')




