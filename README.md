# EDUNET

Course practice materials for Python, data analysis, machine learning, and deep learning. The notebooks use example datasets to explore student behavior, energy consumption, environmental factors, and sustainability.

## Contents

### Notebooks

| Notebook | Topics |
| --- | --- |
| `EdunetDay1.ipynb` | Python fundamentals: data types, collections, conditionals, loops, functions, and introductory pandas |
| `EdunetDay2.ipynb` | List operations and comprehensions, pandas DataFrames, data inspection, missing values, and basic charts |
| `EdunetDay3.ipynb` | Regression with scikit-learn: preparing data, training a linear regression model, predictions, and evaluation |
| `EdunetDay4.1.ipynb` | Classification and model evaluation, including logistic regression, random forests, confusion matrices, and classification reports; also includes clustering practice |
| `EdunetDay4.2.ipynb` | Deep-learning regression with a Keras sequential neural network |

### Datasets

| File | Description |
| --- | --- |
| `Student_Behaviour.csv` | Student academic, lifestyle, and preference data |
| `appliance_energy.csv` | Temperature and appliance energy consumption data used for a regression exercise |
| `agricultural sustainability.csv` | Soil, crop, water, carbon, and fertilizer measurements with a sustainability label |
| `green_tech_data.csv` | Green-technology measurements with a sustainability label |
| `environmental factors.csv` | Environmental measurements including temperature, humidity, wind speed, emissions, solar irradiance, and pollution |

### Saved model files

The `.pkl` files are serialized model artifacts saved during the exercises:

- `Simple Linear Regression Model.pkl`
- `Linear Regression Classification.pkl`
- `Random Forest Algorithms Classification.pkl`

The filenames are retained as created in the course materials. In particular, the “Linear Regression Classification” name is not a reliable indication of the model's algorithm; check the corresponding notebook before loading or using an artifact. Only load pickle files from sources you trust, and use compatible Python and scikit-learn versions.

## Getting started

1. Clone or download this repository.
2. Install Jupyter Notebook or JupyterLab and the libraries used by the notebooks:

   ```bash
   pip install jupyter pandas numpy matplotlib seaborn scikit-learn joblib tensorflow
   ```

3. Start Jupyter from the project directory:

   ```bash
   jupyter notebook
   ```

4. Open a notebook and run its cells in order.

Most notebook data files are referenced by filename, so run Jupyter from the project directory. `EdunetDay4.2.ipynb` currently refers to `/content/predict_energy_consumption.xls`, which is not included here; update that path and provide the expected data file before running that notebook.

## Notes

- These are learning exercises and sample datasets, not a packaged or deployed application.
- `.ipynb_checkpoints/` contains Jupyter's automatically generated notebook checkpoints.
