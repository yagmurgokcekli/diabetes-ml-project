# Diabetes Health Indicators - Machine Learning Project

## Overview
This project applies machine learning techniques to analyze the **Diabetes Health Indicators** dataset. The dataset is preprocessed, split into training and testing sets, and classified using **Decision Tree, Random Forest, and k-Nearest Neighbors** models. Performance is evaluated using **accuracy scores, classification reports, and confusion matrices**.

## Dataset
- **Source**: [[Kaggle]](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset)
- **Features**:
  - **Diabetes_binary**: Indicates whether the individual has diabetes (target variable)
  - **HighBP**: High blood pressure (1 = Yes, 0 = No)
  - **HighChol**: High cholesterol (1 = Yes, 0 = No)
  - **CholCheck**: Cholesterol check in the last five years (1 = Yes, 0 = No)
  - **BMI**: Body Mass Index
  - **Smoker**: Have smoked at least 100 cigarettes in lifetime (1 = Yes, 0 = No)
  - **Stroke**: History of stroke (1 = Yes, 0 = No)
  - **HeartDiseaseorAttack**: History of heart disease or myocardial infarction (1 = Yes, 0 = No)
  - **PhysActivity**: Physical activity in the past 30 days (1 = Yes, 0 = No)
  - **Fruits**: Consumes fruit at least once a day (1 = Yes, 0 = No)
  - **Veggies**: Consumes vegetables at least once a day (1 = Yes, 0 = No)
  - **HvyAlcoholConsump**: Heavy alcohol consumption (1 = Yes, 0 = No)
  - **AnyHealthcare**: Has health coverage (1 = Yes, 0 = No)
  - **NoDocbcCost**: Could not see a doctor due to cost (1 = Yes, 0 = No)
  - **GenHlth**: General health (1 = Excellent, 5 = Poor)
  - **MentHlth**: Number of days of poor mental health in the last 30 days
  - **PhysHlth**: Number of days of poor physical health in the last 30 days
  - **DiffWalk**: Difficulty walking or climbing stairs (1 = Yes, 0 = No)
  - **Sex**: Gender (1 = Male, 0 = Female)
  - **Age**: Age category (13 levels: 1 = 18-24, 13 = 80+)
  - **Education**: Education level (1 = Never attended school, 6 = College graduate)
  - **Income**: Income category (1 = Less than $10,000, 8 = $75,000 or more)
- **Target Variable**: Diabetes_binary (indicates whether the individual has diabetes)


## Steps
1. **Data Preprocessing**: Handle missing values and standardize features.
2. **Train-Test Split**: Split the dataset into **80% training and 20% testing**.
3. **Model Training**: Apply three different classification algorithms:
   - Decision Tree
   - Random Forest
   - k-Nearest Neighbors
4. **Evaluation**: Compare accuracy and visualize confusion matrices.

## Requirements
Install the necessary dependencies before running the Jupyter Notebook:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Usage
Run the Jupyter Notebook to execute the machine learning pipeline:

1. Clone the repository and navigate to the project folder:

   ```bash
   git clone https://github.com/yagmurgokcekli/diabetes-ml-project.git
   cd diabetes-ml-project
   ```

2. Open the notebook in Jupyter or JupyterLab:

   - If using Jupyter Notebook:
     ```bash
     jupyter notebook diabetes_ml_project.ipynb
     ```
   - If using JupyterLab:
     ```bash
     jupyter lab diabetes_ml_project.ipynb
     ```

3. Execute the cells in the notebook to run the machine learning pipeline.

## Results
The classification models are evaluated based on accuracy scores and confusion matrices.
