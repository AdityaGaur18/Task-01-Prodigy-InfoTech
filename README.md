# Task-01-Prodigy-InfoTech

# Population Data Visualization Project

A data visualization project analyzing and visualizing global population trends from 1960 to 2022.

## Project Overview

This project demonstrates data analysis and visualization techniques using Python to explore population distribution across different countries. The analysis includes histogram and bar chart visualizations to understand population trends and identify the most populous countries.

## Features

- **Population Distribution Analysis**: Histogram visualization showing the distribution of population in 2022
- **Top 10 Countries Analysis**: Bar chart displaying the 10 most populous countries in 2022
- **Data Cleaning**: Handles missing values and data preprocessing
- **Statistical Analysis**: Comprehensive data exploration and insights

## Technologies Used

- **Python 3.x**
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical operations
- **Matplotlib**: Data visualization
- **Seaborn**: Statistical data visualization

## Dataset

**Source**: World Bank Population Data (1960-2022)

**Columns**:
- `Country Name`: Name of the country
- `Country Code`: ISO country code
- `Indicator Name`: Total Population
- `Indicator Code`: Population indicator code
- Year columns (1960-2022): Population by year

## Getting Started

### Prerequisites

```bash
pip install pandas numpy matplotlib seaborn
```

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/population-visualization.git
cd population-visualization
```

2. Ensure you have the CSV file (`population.csv`) in the same directory

3. Run the Jupyter notebook or Python script
```bash
jupyter notebook Task_01.ipynb
```

## Visualizations

### 1. Population Distribution (2022)
- **Type**: Histogram with KDE
- **Purpose**: Shows the frequency distribution of population across countries
- **Insights**: Identifies population concentration patterns

### 2. Top 10 Most Populous Countries (2022)
- **Type**: Bar Chart
- **Purpose**: Displays the 10 countries with highest population
- **Insights**: Easy comparison of population sizes among leading countries

## Code Structure

```
Task_01.ipynb
├── Import Libraries
├── Load Dataset
├── Data Exploration
├── Data Cleaning
│   └── Remove null values
├── Visualizations
│   ├── Histogram (Population Distribution)
│   └── Bar Chart (Top 10 Countries)
└── Analysis & Insights
```

## Key Insights

- Global population trends from 1960 to 2022
- Identification of most populous nations
- Understanding of population distribution patterns
- Data-driven insights for demographic analysis

## Sample Output

The project generates:
1. **Histogram**: Red-colored distribution plot with KDE curve showing population frequency
2. **Bar Chart**: Pastel-colored visualization of top 10 populous countries with rotated labels

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Contact

**Aditya Gaur**
- Email: work.adityagaur@gmail.com
- LinkedIn: [linkedin.com/in/adityamnnit03](https://linkedin.com/in/adityamnnit03)

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments

- Data source: World Bank
- Created as part of Data Science internship at Prodigy InfoTech
- Visualization inspiration from modern data analysis practices

---

⭐ **Star this repository if you found it helpful!**
