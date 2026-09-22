# Student Performance Analysis and Prediction using AI

**Student:** Manish  
**Internship:** AICTE | IBM SkillsBuild Data Analytics with AI Academic Internship Program

## Project Description
This project analyzes student demographic, social, family, study and academic information and applies machine learning to predict the final academic grade (G3).

The project demonstrates:
- Data collection from a public dataset
- Data cleaning and inspection
- Exploratory Data Analysis (EDA)
- Data visualization
- Correlation analysis
- Categorical encoding and numerical preprocessing
- Random Forest Regression
- Model evaluation using MAE, RMSE and R²
- An early-prediction experiment without G1 and G2

## Dataset
**UCI Student Performance Dataset:**  
https://archive.ics.uci.edu/dataset/320/student+performance

The UCI dataset contains student achievement information from two Portuguese schools and includes demographic, social, school-related and grade variables.

**Citation:** Cortez, P. (2008). Student Performance. UCI Machine Learning Repository. DOI: 10.24432/C5TG7T.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- UCI ML Repository / ucimlrepo

## Project Workflow
1. Load the public dataset.
2. Inspect dimensions, data types and missing values.
3. Perform descriptive analysis.
4. Visualize grade distribution, study time and absences.
5. Analyze correlations.
6. Preprocess numerical and categorical variables.
7. Train a Random Forest Regression model.
8. Evaluate using MAE, RMSE and R².
9. Train a second model without G1/G2 for early prediction.
10. Interpret limitations and conclusions.

## Setup and Run

### 1. Install Python
Use Python 3.9 or newer.

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Start Jupyter
```bash
jupyter notebook
```

### 4. Open
`Manish_StudentPerformance_AI.ipynb`

### 5. Run all cells
The notebook downloads the dataset through `ucimlrepo`, so an internet connection is required during dataset loading.

## Output
The notebook generates:
- Dataset summary
- Descriptive statistics
- Grade distribution chart
- Study-time analysis
- Absence vs grade visualization
- Correlation heatmap
- Actual vs predicted grade plot
- MAE, RMSE and R² scores
- Early-prediction model metrics

## Limitations
The dataset represents students from two Portuguese schools, so findings should not automatically be generalized to every educational institution. Correlation should not be interpreted as causation.

## Files
- `Manish_StudentPerformance_AI.ipynb` — complete project code
- `requirements.txt` — Python dependencies
- `Manish_ProjectReport.docx` — project report
- `README.md` — project documentation
