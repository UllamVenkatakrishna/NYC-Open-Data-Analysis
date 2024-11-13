# Project Title: School Data Analysis and Visualization

## Project Description
This project aims to analyze and visualize school data to understand trends in student enrollment and grade distributions across different years. Using a dataset with information on school names, years, and grades, the project presents findings on an interactive map. The primary objectives are to:
- Identify enrollment patterns
- Compare grades across schools
- Create a user-friendly visualization for educational stakeholders.

## Features
- **Data Cleaning and Preprocessing**: Ensures accurate, complete data by handling missing values and standardizing school information.
- **Comparative Analysis by Year and Grade**: Analyzes and visualizes changes in student enrollment across multiple years and grades.

## Programming Language
- **Python**

## Libraries
- **Pandas**: For data manipulation and analysis.
- **Matplotlib/Seaborn**: For data visualization.
- **Plotly**: Optional, for interactive mapping and visualization.

## Project Structure
- **notebook.ipynb**: Main Jupyter notebook containing data loading, cleaning, and analysis.
- **Data Files**:
  - `school_data.csv`: Main dataset file with information on school names, years, and grades.

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
git clone https://https://github.com/UllamVenkatakrishna/NYC-Open-Data-Analysis.git
cd School_Data_Analysis
```

## Prepare Data Files

- Place `school_data.csv` in the same directory as the notebook.
- Adjust the file path in the notebook if stored in a different location.

## Open and Run the Notebook

1. **Start Jupyter Notebook:**

    ```bash
    # Launch Jupyter Notebook to open the project notebook
    jupyter notebook notebook.ipynb
    ```

2. **Run Each Cell in Sequence:**

    - **Data Import**: Loads the school dataset.
    - **Data Cleaning**: Checks for and handles missing values, standardizes school information.
    - **Comparative Analysis**: Visualizes enrollment changes by year and grade.
    - **Interactive Map (Optional)**: Plots schools on a map based on location data, if available.

## Version Control Strategy

### Branch
Each team member should work on a separate branch based on their task (e.g., `data-cleaning`, `analysis`, `visualization`).
To create a branch, use:

```bash
git checkout -b data-analysis-nyc-open-data
```
