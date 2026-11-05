# Olympics Data Analysis

A comprehensive data analysis project exploring the historical Olympic Games dataset to uncover patterns, trends, and insights across countries, sports, and time periods.

## Overview

This project analyzes over 100 years of Olympic Games data to understand participation trends, country performance, sport evolution, and medal distributions. The analysis uses exploratory data analysis techniques and statistical methods to derive meaningful insights.

## Features

- **Exploratory Data Analysis:** Comprehensive data exploration and cleaning
- **Temporal Analysis:** Trends across different Olympic eras
- **Country-wise Analysis:** Performance metrics by nation
- **Sport Analysis:** Participation and medal distribution by sport
- **Visualizations:** Multiple charts and graphs for data storytelling

## Tech Stack

- **Python:** Primary programming language
- **pandas:** Data manipulation and analysis
- **numpy:** Numerical computing
- **matplotlib:** Data visualization
- **seaborn:** Statistical data visualization
- **Jupyter Notebook:** Interactive analysis environment

## Project Structure

```
Olympics/
├── dataset_olympics.csv      # Main Olympic events dataset
├── noc_region.csv            # NOC (National Olympic Committee) regions
├── olympics.ipynb            # Analysis notebook
└── README.md                 # This file
```

## Installation

1. Navigate to the project directory:
```bash
cd "resume portfolo projects/Olympics"
```

2. Install required dependencies:
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

## Usage

### Running the Analysis

Open the Jupyter notebook:
```bash
jupyter notebook olympics.ipynb
```

The notebook is organized into sections:
1. Data loading and cleaning
2. Exploratory data analysis
3. Country performance analysis
4. Sport-wise analysis
5. Temporal trends
6. Visualizations and insights

## Dataset

### Olympic Events Dataset (`dataset_olympics.csv`)
Contains information about:
- Athlete details (name, sex, age, height, weight)
- Event information (year, season, city, sport, event)
- Medal information (gold, silver, bronze, or no medal)
- NOC codes (National Olympic Committee)

### NOC Regions Dataset (`noc_region.csv`)
Maps NOC codes to countries/regions for better geographical analysis.

## Key Insights

The analysis explores:
- **Participation Trends:** How Olympic participation has grown over time
- **Gender Parity:** Evolution of female participation in the Olympics
- **Country Performance:** Top performing nations by medals
- **Sport Evolution:** Introduction and popularity of different sports
- **Seasonal Differences:** Summer vs Winter Olympics comparisons
- **Demographics:** Age, height, and weight distributions by sport

## Visualizations

The notebook includes:
- Participation growth over time
- Medal distribution by country
- Sport popularity trends
- Gender participation trends
- Age distribution by sport
- Regional performance heatmaps

## Notable Findings

- [Insert key findings from your analysis]
- [Add interesting patterns discovered]
- [Include any surprising insights]

## Future Improvements

- [ ] Add predictive modeling for medal counts
- [ ] Implement interactive visualizations with Plotly
- [ ] Add geographical mapping with Folium
- [ ] Create a dashboard for real-time Olympic analysis
- [ ] Analyze athlete career trajectories

## References

- [Kaggle Olympic Dataset](https://www.kaggle.com/datasets/heesoojin/120-years-of-olympic-history-athletes-and-results)

## License

This project is for educational and portfolio purposes.
