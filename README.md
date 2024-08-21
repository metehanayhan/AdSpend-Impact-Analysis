# Advertising Project

## Project Overview
This project aims to analyze the impact of investments in TV, Radio, and Newspaper advertising on sales figures. The goal is to answer the question, "How much will my sales increase if I invest in these channels?" by developing a multiple linear regression model.

## Technologies and Libraries Used
- **Python**
- **Pandas** - For data manipulation and analysis.
- **Matplotlib** - For plotting and visualization.
- **Seaborn** - For advanced data visualization.
- **Scikit-learn** - For model development, training, and evaluation.

## Dataset
The dataset used for this project is obtained from the `advertising.csv` file. It includes data on TV, Radio, and Newspaper advertising expenditures and their impact on sales.

### Dataset Summary
- **TV:** Investment in TV advertising 
- **Radio:** Investment in Radio advertising 
- **Newspaper:** Investment in Newspaper advertising 
- **Sales:** Sales figures 

## Data Analysis and Modeling
1. **Data Analysis:**
   - The dataset was examined for missing and outlier values.
   - The distribution of the data was visualized.

2. **Model Development:**
   - TV, Radio, and Newspaper expenditures were used as independent variables, with sales as the dependent variable.
   - The dataset was split into training and testing sets, followed by the application of a multiple linear regression model.
   - Model performance was evaluated using R-squared (`r2_score`) and Mean Squared Error (`mean_squared_error`).

3. **Results:**
   - Investment in Radio advertising has the most significant impact on sales.
   - TV advertising also shows a considerable effect, while Newspaper advertising has a minimal impact.

## Usage
You can clone or download the project files to run them. Use the following command to install the necessary libraries:

```bash
pip install -r requirements.txt
