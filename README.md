# Data-Analytics-Using-Pandas-And-Matplotlib
## Overview
This project creates a comprehensive sales data analysis dashboard using Python, focusing on visualizing and analyzing sales patterns across different categories, regions, and time periods. The dashboard generates synthetic sales data and presents various analytical visualizations to help understand sales trends and patterns.

## Features
- Monthly sales trend analysis
- Category-wise sales distribution
- Regional sales breakdown
- Day-of-week sales patterns
- Statistical analysis including:
  - Basic summary statistics
  - Monthly aggregations
  - Category-wise analysis
  - 7-day moving averages

## Requirements
```
python >= 3.7
pandas
matplotlib
numpy
```

## Installation
1. Clone this repository:
```bash
git clone https://github.com/yourusername/sales-analysis-dashboard.git
cd sales-analysis-dashboard
```

2. Install required packages:
```bash
pip install pandas matplotlib numpy
```

## Usage
Simply run the script:
```bash
python sales_analysis.py
```

The script will:
1. Generate synthetic sales data
2. Perform statistical analysis
3. Create a dashboard with four visualizations
4. Print key insights about the sales data

## Dashboard Components
1. **Monthly Average Sales Trend**
   - Line plot showing sales trends over months
   - Includes markers for easy month-to-month comparison

2. **Category Analysis**
   - Bar chart showing average sales by product category
   - Includes value labels for precise reading

3. **Regional Sales Distribution**
   - Pie chart showing sales distribution across regions
   - Includes percentage labels

4. **Daily Sales Patterns**
   - Bar chart showing average sales by day of week
   - Includes value labels and grid lines for easy reading

## Sample Output
The script generates:
- A figure with 4 subplots showing different aspects of the sales data
- Printed statistical analysis including:
  - Summary statistics
  - Monthly sales analysis
  - Category-wise analysis
  - Key insights

## Customization
You can modify the following parameters in the code:
- `colors`: Change the color scheme
- `figsize`: Adjust the size of the dashboard
- `date_range`: Modify the date range for analysis
- Add or remove categories and regions

## License
MIT License - feel free to use this code for any purpose.

