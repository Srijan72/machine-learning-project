# Heart Disease Prediction Using Machine Learning

## Overview
This project explores heart disease data and uses machine learning to predict whether a patient may have heart disease based on medical attributes. It includes data analysis notebooks and model experiments using Logistic Regression and Random Forest, with an additional notebook exploring Support Vector Machines.

> **Disclaimer:** This is an educational machine-learning project, not a medical diagnostic tool. Do not use its predictions to make healthcare decisions. Consult a qualified healthcare professional for medical advice.

## Project Contents

- `heart.csv` — dataset used by the prediction notebook.
- `Heart_Disease_Prediction.ipynb` — data preparation, train/test split, and Logistic Regression workflow.
- `Heart_Disease_Analysis_RF-checkpoint.ipynb` — exploratory data analysis and Random Forest-related analysis.
- `Untitled.ipynb` — additional experiments with Random Forest and Support Vector Machine models.
- `heart_dataset_description.docx` — description of the dataset attributes.
- `Hheart diease prediction.pdf` — project/report PDF.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn

## Setup and Run

1. Install Python (Python 3.10 or newer is recommended).
2. Download or clone this repository and open a terminal in the project folder.
3. Create and activate a virtual environment (optional but recommended):

   **Windows**
   ```bash
   python -m venv .venv
   .venv\Scripts\activate
   ```

   **macOS/Linux**
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

4. Install the required packages:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

5. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

6. Open `Heart_Disease_Prediction.ipynb` and run the notebook cells in order.

## Important Dataset Note

The prediction notebook loads `heart.csv`. Some other notebooks use `Heart.csv`. File names are case-sensitive on some systems, so make sure the name in each notebook matches the actual dataset filename (`heart.csv`), or update the notebook path accordingly.

## Typical Workflow

1. Load and inspect the dataset.
2. Check data quality and explore the feature distributions.
3. Separate the input features from the `target` column.
4. Split the data into training and testing sets.
5. Train a classification model.
6. Evaluate predictions using suitable metrics, such as accuracy.

In the prediction notebook, the target is interpreted as `1` for the presence of heart disease and `0` for no heart disease, according to the notebook's comments. Verify the dataset documentation before interpreting the labels.

## Possible Improvements

- Add a `requirements.txt` file for reproducible setup.
- Compare Logistic Regression, Random Forest, and SVM using the same train/test split.
- Report precision, recall, F1-score, and a confusion matrix in addition to accuracy.
- Add cross-validation and check for data leakage.
- Build a simple user interface with Streamlit or an API with FastAPI, clearly showing that results are for educational purposes only.

## Author

**Srijan Akuthota**
