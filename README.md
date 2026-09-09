# Summer Internship 2026

A collection of 13 practical data analysis and machine learning tasks completed during the Summer Internship program. The project progresses from exploratory data analysis and preprocessing to classification, regression, ensemble learning, clustering, and dimensionality reduction.

## Project Goals

- Build a foundation in Python-based data analysis.
- Practice data cleaning, encoding, scaling, and exploratory visualization.
- Train and evaluate common machine learning models.
- Understand model performance using appropriate metrics and visualizations.
- Apply unsupervised learning and dimensionality reduction techniques.

## Task Index

| Task | Topic | Dataset / Model |
| --- | --- | --- |
| [Task 1](Task-1/README.md) | Data understanding and exploration | Titanic and student datasets |
| [Task 2](Task-2/README.md) | Data cleaning and quality validation | Medical Appointment No Shows |
| [Task 3](Task-3/README.md) | Exploratory data analysis | Iris and Netflix datasets |
| [Task 4](Task-4/README.md) | Feature encoding and scaling | Adult Income dataset |
| [Task 5](Task-5/README.md) | Classification with Logistic Regression | UCI Heart Disease dataset |
| [Task 6](Task-6/README.md) | Regression with Linear Regression | California Housing dataset |
| [Task 7](Task-7/README.md) | Classification with Logistic Regression | Titanic dataset |
| [Task 8](Task-8/README.md) | Interpretable classification with Decision Trees | UCI Bank Marketing dataset |
| [Task 9](Task-9/README.md) | Ensemble learning and fraud detection | Synthetic credit card fraud dataset |
| [Task 10](Task-10/README.md) | Distance-based classification with KNN | Scikit-learn Digits dataset |
| [Task 11](Task-11/README.md) | Classification with SVM and hyperparameter tuning | Scikit-learn Breast Cancer dataset |
| [Task 12](Task-12/README.md) | Unsupervised customer segmentation | Mall Customers dataset with KMeans |
| [Task 13](Task-13/README.md) | Dimensionality reduction | Scikit-learn Digits dataset with PCA |

## Technologies Used

- Python 3.x
- Jupyter Notebook or Google Colab
- pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn
- joblib for model serialization where required

## Setup

Create and activate a virtual environment, then install the common dependencies:

```bash
python -m venv .venv
source .venv/bin/activate
pip install pandas numpy matplotlib seaborn scikit-learn jupyter joblib
```

On Windows, activate the environment with:

```powershell
.venv\Scripts\activate
```

## How to Run

1. Open the `Summer_Internship2026` folder in VS Code or JupyterLab.
2. Open the notebook for the task you want to run.
3. Select the Python environment containing the required dependencies.
4. Run the notebook cells in order.
5. Keep each notebook and its related datasets in the same task folder when using local file paths.

Some notebooks use datasets provided in their task folders, while others use datasets built into scikit-learn. Refer to the README inside each task folder for task-specific details and outputs.

## Repository Structure

```text
Summer_Internship2026/
├── README.md
├── Task-1/
├── Task-2/
├── Task-3/
├── Task-4/
├── Task-5/
├── Task-6/
├── Task-7/
├── Task-8/
├── Task-9/
├── Task-10/
├── Task-11/
├── Task-12/
└── Task-13/
```

Each task folder contains a task-specific README, notebook, and any required dataset files.

## Notes

- Run the notebooks in a clean, consistent Python environment to avoid dependency differences.
- Review the task-specific README files for model metrics, preprocessing decisions, and generated deliverables.
- Do not commit sensitive credentials, private datasets, or local environment folders such as `.venv/`.

## Author

Asim
