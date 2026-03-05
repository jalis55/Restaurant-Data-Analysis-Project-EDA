# Restaurant Data Analysis EDA

This project performs exploratory data analysis on restaurant data to uncover insights about customer ratings, voting patterns, and cost structures.

## Key Analyses
- **Top 10 Highest-Rated Restaurants**: Identified the highest-rated establishments with their vote counts and pricing
- **Restaurant Popularity**: Analyzed voting patterns across different restaurant types
- **Online Ordering Impact**: Compared ratings between restaurants with and without online ordering
- **Cost Analysis**: Examined the relationship between pricing and customer satisfaction

## How to Run
1. Ensure required packages are installed:
   ```bash
   pip install pandas matplotlib seaborn
   ```
2. Open `scripts.ipynb` in Jupyter Notebook
3. Execute all cells to reproduce the analysis

## Dataset
The project uses `data.csv` containing:
- Restaurant names
- Rating information (extracted from original format)
- Vote counts
- Approximate cost for two people
- Online order availability
- Restaurant type classification

## Key Visualizations
- Count plots for restaurant categories
- Line plots for vote distribution by restaurant type
- Box plots comparing online vs offline rating distributions
- Heatmap of order preferences by restaurant type
- Histograms of rating distributions

## Project Structure
```
Restaurant data analysis project EDA/
├── data.csv               # Original dataset
├── scripts.ipynb          # Analysis notebook with visualizations
└── README.md              # This documentation file
```


This analysis provides actionable insights for restaurant owners and customers alike, highlighting what factors contribute to restaurant success in the dataset.