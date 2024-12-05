# Student Performance Analysis

This project analyzes student performance data to identify key factors influencing outcomes and to predict performance using machine learning models. 

## Project Overview

1. **Data Loading and Preprocessing**:
   - Reads student performance data from a CSV file.
   - Handles missing values and encodes categorical features.

2. **Exploratory Data Analysis (EDA)**:
   - Visualizes data relationships using histograms, scatter plots, and correlation heatmaps.

3. **Feature Engineering**:
   - Creates additional features to enhance predictive modeling.

4. **Model Training and Evaluation**:
   - Applies machine learning models such as Ridge Regression and Decision Trees.
   - Evaluates models using metrics like accuracy and R-squared scores.

5. **Insights and Recommendations**:
   - Summarizes key findings from the analysis.
   - Provides actionable insights based on the data.

## Requirements

- Python 3.7+
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - Jupyter Notebook

## How to Run the Notebook

1. Clone the repository or download the `student.ipynb` file.
2. Install the required Python libraries using pip:
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Open the notebook in Jupyter:
   ```
   jupyter notebook student.ipynb
   ```
4. Follow the cells step-by-step to load data, perform analysis, and train models.

## Results

- The Ridge Regression model achieved the highest accuracy (90%) for predicting student performance.
- Visualizations and statistical analyses revealed significant factors influencing outcomes.

## Contributing

Feel free to open issues or submit pull requests for enhancements.

## License

This project is open-source and available under the MIT License.
