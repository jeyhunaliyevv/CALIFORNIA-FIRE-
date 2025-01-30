# CALIFORNIA-FIRE-# Project Name: **Fire Damage Detection and Analysis Model**

## Project Description

This project aims to detect and analyze the geographical and structural characteristics of buildings damaged by fires. The objective is to model the damage status of structures exposed to fires using data cleaning, visualization, and machine learning techniques.

## Directory Structure

- **notebooks/**: Folder containing notebook files.
- **data/**: Folder containing data files.
- **requirements.txt**: File listing the required libraries.
- **README.md**: Basic information about the project.

## Dataset

The dataset used contains geographical and structural features related to fire damage (X and Y coordinates, building type, damage status, etc.).

## Technologies and Libraries Used

- **Python 3.x**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Scikit-Learn**

## Installation

1. Clone the repository:
   ```bash
   git clone <REPO_URL>
   cd <REPO_NAME>
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook file:
   ```bash
   jupyter notebook
   ```

## Project Steps

### 1. Data Reading

The dataset was read in CSV format and its basic features were examined.

### 2. Data Cleaning

Missing values and data types were analyzed and necessary corrections were made.

### 3. Data Visualization

Graphs were used to visualize building types and damage statuses.

### 4. Data Encoding

Categorical variables were encoded to prepare for machine learning algorithms.

### 5. Modeling

A Random Forest algorithm was used to build and evaluate a damage prediction model.

## Results

- The damage prediction accuracy was %X.
- Visualization provided insights into damage and building type distributions.

## Contributions

To contribute, please create a **pull request** or open an issue.

## License

This project is licensed under the [MIT License](LICENSE).

