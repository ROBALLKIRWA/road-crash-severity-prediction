# Road Crash Severity Prediction

## Project Overview

This project explores road traffic crash data and develops
machine-learning models to predict the severity of a road crash based on
available crash-related information.

The aim is to identify patterns associated with crash severity and
evaluate how well machine-learning techniques can classify the severity
level of a crash. The results may support road-safety analysis and help
stakeholders understand factors associated with more serious crashes.

## Objectives
- Understand and explore the road crash dataset.
- Clean and prepare the data for analysis.
- Explore factors and patterns associated with crash severity.
- Build and compare suitable classification models.
- Evaluate model performance using appropriate classification metrics.
- Summarize findings and provide recommendations.
## Project Structure

road_crash_severity_prediction
The notebook contains the project workflow, including data preparation,
exploratory data analysis, model development, and evaluation.
## Tools and Technologies

The project may use the following Python tools:
- Python -- programming language
- Jupyter Notebook -- interactive development environment
- Pandas -- data loading and manipulation
- NumPy -- numerical operations
- Matplotlib / Seaborn -- data visualization
- Scikit-learn -- preprocessing, model training, and evaluation
Getting Started
1. Requirements
Install Python

3. Install the libraries
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
4. Open the project
Navigate to the project folder:
cd "road_crash_severity_prediction"
Start Jupyter Notebook:
jupyter notebook
Open road_crash_severity_prediction_project.ipynb and run the notebook
cells in order.

Alternatively, open the notebook in Visual Studio Code with the Python
and Jupyter extensions installed
4. Add the dataset
Place the dataset in the project folder or its data/ subfolder. Check
the data-loading cell in the notebook and update the file path if
necessary.

For example:
import pandas as pd

df = pd.read_csv(r"C:\Users\USER\Downloads\processed_crash_data.csv")
Use the actual filename and file format of your dataset. If the source
file is Excel, Stata, or another format, use the appropriate Pandas
reader.
Typical Project Workflow
1. Data loading: Import the dataset and inspect its structure.
2. Data understanding: Review columns, data types, summary
   statistics, and the target variable.
3. Data cleaning: Handle missing values, duplicates, inconsistent
   values, and unsuitable data types where necessary.
4. Exploratory data analysis (EDA): Use charts and summary
   statistics to investigate distributions and relationships.
5. Preprocessing: Prepare features, encode categorical variables,
   scale numerical variables where appropriate, and split the data into
   training and test sets.
6. Model development: Train suitable classification algorithms to
   predict crash severity.
7. Model evaluation: Compare models using metrics such as accuracy,
   precision, recall, F1-score, and a confusion matrix.
8. Conclusion: Interpret the results, discuss limitations, and
   recommend possible improvements.
The exact steps and algorithms should reflect what is implemented in the
notebook.
Target Variable
The target variable should represent the crash-severity category being
predicted.

Target column: [severity_index]

Severity classes:
[Fatal crash, non fatal crash]

Confirm the class labels from the dataset and notebook before
interpreting model results. If the severity classes are imbalanced,
consider class-specific precision, recall, F1-score, and a confusion
matrix rather than relying on accuracy alone.
Results
Record the final results from the notebook here.

  Model           Accuracy   Precision   Recall   F1-score
  
  [Model 1]        [ ]       [ ]    [ ]      [ ]
  
[Model 2]        [ ]       [ ]    [ ]      [ ]

[Model 3]        [ ]       [ ]    [ ]      [ ]

Key Findings

- Which crash characteristics appear most associated with severity?
- 
- Which severity class is most common?
- 
- Which model performed best, and according to which metric?
- 
- Which classes were most difficult for the model to distinguish?
- 
Only report findings supported by the analysis.

Limitations

Possible limitations to consider include:

- Missing or inaccurate crash records.
- Imbalanced severity categories.
- Features that are unavailable at the time a prediction would need to
  be made.
- Results that may not generalize to other locations or time periods.
- Classification performance that does not necessarily imply causal
  relationships.
Future Improvements
- Collect more complete and representative crash data.
- Address class imbalance where appropriate.
- Tune model hyperparameters and validate results using
  cross-validation.
- Compare additional classification algorithms.
- Use feature-importance or explainability methods to interpret
  predictions.
- Test the final model on new, unseen data.
Responsible Use
Predictions from this project should be treated as analytical estimates,
not definitive judgments about individual crashes. They should not
replace official crash investigations, professional road-safety
assessments, or emergency-response decisions.

Author
Name: [Shadrack kirwa]
Project: Road Crash Severity Prediction
Notebook:[ ]"road_crash_severity_prediction_project.ipynb"
