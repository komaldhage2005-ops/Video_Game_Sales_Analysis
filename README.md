# Vedio_Game_Sales_Analysis
Welcome to the **Video Game Sales Analysis** project! This project explores video game sales data to understand which games, platforms, genres, and publishers perform best across different regions. Using Python libraries for data analysis and visualization, the notebook identifies sales patterns and compares the North America, Europe, Japan, and Other regional markets.

## Getting Started

- **Dataset:** The analysis uses the `vgsales.csv` dataset.
- **Notebook:** Open `Vedio_Game_Sales (1).ipynb` in Jupyter Notebook or JupyterLab.
- **Libraries:** Make sure Python and the required libraries are installed before running the notebook.
- **Run the Analysis:** Execute the notebook cells in order to perform data preparation, analysis, and visualization.

## Features

- **Data Preparation:** Checks missing values, handles missing year and publisher values, and prepares the data for analysis.
- **Exploratory Data Analysis:** Uses descriptive statistics and grouped sales summaries to explore the dataset.
- **Top-Selling Games:** Identifies the best-selling video games based on global sales.
- **Platform Analysis:** Compares total and average global sales across gaming platforms.
- **Genre Analysis:** Examines sales by game genre and tracks genre sales over time.
- **Publisher Analysis:** Compares leading publishers and their performance across regions.
- **Regional Sales Analysis:** Studies sales distribution and trends across North America, Europe, Japan, and Other regions.
- **Visualizations:** Presents findings through bar charts, pie charts, and line charts.

## Analysis Breakdown

- **Top-Selling Games:** Wii Sports (Wii) ranks first in the notebook's global sales analysis, with 82.74 million copies, followed by Super Mario Bros. (NES) with 40.24 million.
- **Platform Performance:** PS2 records the highest total global sales in the dataset, with 1,255.64 million copies, followed by Xbox 360 with 979.96 million.
- **Genre Performance:** Action games lead total global sales with 1,751.18 million copies, followed by Sports and Shooter games.
- **Regional Performance:** North America is the largest market in the analysis, with 4,392.95 million copies (52.9%), followed by Europe with 2,434.13 million copies (29.3%).
- **Genre Trends:** The notebook explores how genre sales change over the years and notes the strong performance of Action games in many years.
- **Publisher Performance:** Nintendo leads publisher sales in several regional comparisons, while publisher rankings vary by market.

## Visualizations

The following charts are generated from the project notebook.

### Total Sales by Platform
![Total Sales by Platform](images/cell_12_figure_1.png)

### Total Sales by Genre
![Total Sales by Genre](images/cell_13_figure_0.png)

### Global Sales by Region
![Global Sales by Region](images/cell_15_figure_0.png)

### Top 10 Best-Selling Video Games
![Top 10 Best-Selling Video Games](images/cell_19_figure_0.png)

### Global Sales Trends by Year and Genre
![Global Sales Trends by Year and Genre](images/cell_32_figure_0.png)

### Top Publishers by Global Sales
![Top Publishers by Global Sales](images/cell_36_figure_1.png)

### Publisher Sales Across Regions
![Publisher Sales Across Regions](images/cell_46_figure_0.png)

### Regional Sales Trends by Year
![Regional Sales Trends by Year](images/cell_52_figure_0.png)

### Sales by Genre and Region
![Sales by Genre and Region](images/cell_55_figure_1.png)

## Technologies Used

- **Python** – Programming language
- **Pandas** – Data cleaning, manipulation, and analysis
- **Seaborn** – Statistical data visualization
- **Matplotlib** – Charts and graphs
- **Jupyter Notebook** – Development environment

## How to Run the Project

1. Clone or download this repository.
2. Make sure the `vgsales.csv` dataset is available at the file path used in the notebook, or update the `pd.read_csv()` path to match your dataset location.
3. Install the required libraries:

   ```bash
   pip install pandas seaborn matplotlib jupyter
   ```

4. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open the video game sales notebook and run the cells from top to bottom.

## Project Structure

```text
Video-Game-Sales-Analysis/
│
├── Vedio_Game_Sales (1).ipynb   # Jupyter Notebook containing the analysis
├── README.md                    # Project documentation
└── images/                      # Visualizations used in this README
```

> **Note:** The dataset is not included in this repository. Add `vgsales.csv` to your project or update the dataset path in the notebook before running it.

## Conclusion

This project provides an overview of video game sales across games, platforms, genres, publishers, and regions. The analysis highlights the strong performance of Action games, the leading contribution of North America, and the popularity of the PS2 platform and Wii Sports title in the dataset. The visualizations make it easier to compare sales patterns and identify trends in the video game market.

## Contributions

Suggestions and improvements are welcome. If you find an issue or have an idea to improve the analysis, feel free to open an issue or submit a pull request.
