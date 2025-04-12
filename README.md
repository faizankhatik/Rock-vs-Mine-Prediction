# Rock vs Mine Prediction

This project is focused on building a machine learning model to classify sonar signals as either "Rock" or "Mine". The model is trained using the Sonar dataset which consists of 60 features representing sonar returns.

## Dataset

The dataset consists of sonar signals bounced off a metal cylinder (mine) and rocks at various angles. Each instance contains 60 numeric features (sonar readings) and a label (R for Rock, M for Mine).

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- Numpy
- Scikit-learn (sklearn)
- Matplotlib / Seaborn (for visualization)

## Workflow

1. **Data Loading**: Load the dataset using pandas.
2. **Data Preprocessing**:
   - Check for null values.
   - Encode labels.
   - Train-test split.
3. **Model Training**:
   - Logistic Regression is used for classification.
4. **Evaluation**:
   - Accuracy Score
   - Confusion Matrix
   - Classification Report

## Usage

To run the project:

1. Clone this repository.
2. Install dependencies using `pip install -r requirements.txt`.
3. Run the notebook `Rock_vs_Mine_Prediction.ipynb` in Jupyter Notebook or JupyterLab.

## Results

The trained logistic regression model is able to effectively distinguish between rocks and mines based on sonar signal data.

## Author

Developed as part of a learning project.
