# Titanic ML Seaborn Analysis

## Overview
This project explores the Titanic dataset using the Seaborn library to visualize key relationships between different features. The dataset is loaded from Seaborn's built-in datasets, and various visualization techniques are applied to analyze correlations, distributions, and patterns among passengers.

## Prerequisites
Ensure you have the following libraries installed before running the script:

```bash
pip install seaborn matplotlib pandas numpy
```

## Features and Visualizations
The script performs the following analyses:

### 1. Load and Display Data
- Loads the Titanic dataset using `sns.load_dataset("titanic")`.
- Displays the first five rows in a tabular format.

### 2. Correlation Matrix & Heatmap
- Computes correlations between selected numerical variables.
- Displays a heatmap of correlations using Seaborn’s `heatmap()`.

### 3. Distribution and Relationship Plots
- **Joint Plot:** Scatter plot of `fare` vs. `age`.
- **Distribution Plot:** Histogram of the `fare` variable.
- **Boxplot:** Distribution of `age` across passenger classes.
- **Swarmplot:** Age distribution by passenger class.
- **Count Plot:** Count of passengers by gender.
- **Pair Plot:** Relationships between `survived`, `age`, `fare`, and `sex`.

### 4. FacetGrid for Gender-wise Age Distribution
- Uses Seaborn’s `FacetGrid()` to visualize the age distribution for each gender.

## How to Run
Simply execute the script in a Python environment:

```bash
python titanic_analysis.py
```

## Output
Running the script will generate various plots that provide insights into the Titanic dataset, including:
- Data overview in tabular format.
- Correlation heatmap.
- Distribution, scatter, and categorical plots.
- <img width="361" alt="image" src="https://github.com/user-attachments/assets/ac4208eb-d12e-4b0e-9fc6-3de9db23c865" />
- <img width="335" alt="image" src="https://github.com/user-attachments/assets/763074a3-6326-42e9-8903-9fd6179676ab" />
- <img width="360" alt="image" src="https://github.com/user-attachments/assets/bf42a24a-25a1-41bb-b916-0655488bef6b" />
- <img width="359" alt="image" src="https://github.com/user-attachments/assets/2af557f9-833c-4383-b6c6-7150df2b16df" />
- <img width="358" alt="image" src="https://github.com/user-attachments/assets/3c077ff1-0162-44d4-9a31-df5d65b4f39c" />
- <img width="361" alt="image" src="https://github.com/user-attachments/assets/47799a97-8cf1-4f86-b05b-75ef00b9f772" />
- <img width="360" alt="image" src="https://github.com/user-attachments/assets/51b4e5db-128d-4eb1-9971-3b89e398156c" />
- <img width="361" alt="image" src="https://github.com/user-attachments/assets/3585e2a9-ea9c-46f3-b975-9467f2800b1e" />
- <img width="360" alt="image" src="https://github.com/user-attachments/assets/cbd6129c-885b-4dbe-96ed-b35fa1ba9b12" />




## Author
Developed by Jeremy Martinez-Quinones.

## License
This project is licensed under the MIT License - see LICENSE file for details.


