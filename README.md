# Crime-Prediction-Of-Atlanta-Using-Machine-Learning

## Project Overview
This project classifies crime zones in Atlanta as either high-crime or low-crime zones using machine learning. The analysis is conducted in a Jupyter Notebook (`crime-sona-v1.ipynb`) and involves:
- **Neural Networks** for complex pattern recognition.
- **XGBoost** for efficient classification.
- **Geospatial Analysis** using geopy to incorporate geographic insights.

The dataset is cleaned, processed, and analyzed to extract meaningful insights and evaluate the models' performance. This project demonstrates how machine learning can assist in urban safety planning and resource allocation.

## Included Files
1. **CrimeDataofAtlanta.csv** - The dataset containing historical crime data.
2. **CrimePredictionofAtlantaProject.ipynb** - The Jupyter Notebook file with all steps, including:
   - Data cleaning and preprocessing.
   - Feature engineering.
   - Model building (Neural Network and XGBoost).
   - Evaluation and visualizations.
3. **README.md** - This file with complete setup instructions.
4. **requirements.txt** - Text file listing all Python dependencies for the project.

## Setup Instructions

### 1. Verify Files
Ensure the following files are in the same directory:
- `CrimePredictionofAtlantaProject.ipynb`
- `CrimeDataofAtlanta.csv`
- `requirements.txt`
- `README.md`

### 2. Install Required Libraries
You can install the required Python libraries using either of the following methods:

#### Option 1: Install Libraries via Jupyter Notebook
The first cell in the notebook includes the following command to automatically install all required libraries:

```python
# Install necessary libraries
!pip install pandas numpy matplotlib seaborn scikit-learn tensorflow xgboost geopy
```

#### Option 2: Install Libraries via Command Line
Alternatively, you can install the libraries manually by running the following command:

```bash
pip install -r requirements.txt
```

### 3. Execution Instructions

#### 1. Open the Notebook
Launch Jupyter Notebook or JupyterLab:

```bash
jupyter notebook
```

Open the file `CrimePredictionofAtlantaProject.ipynb`.

#### 2. Run the Notebook
1. Execute the first cell to install the necessary libraries (if not already installed).
2. Run the subsequent cells sequentially. The notebook will:
    - Load and preprocess the dataset.
    - Perform feature engineering.
    - Train and evaluate machine learning models (Neural Network and XGBoost).
    - Generate visualizations and results.

### 4. Expected Outputs
1. **Visualizations**:
    - Correlation heatmaps.
    - Crime distribution charts.
    - Model performance metrics and crime prediction based on entered data.

2. **Insights**:
    - Identification of high-crime zones (e.g., Old Fourth Ward, Vine City).
    - Seasonal crime trends (e.g., higher crime rates during summer months).
    - Geospatial patterns in crime distribution.

### 5. Folder Structure
Ensure your project folder is structured as follows:

```
Project_Folder/
├── CrimeDataofAtlanta.csv       # Dataset
├── CrimePredictionofAtlantaProject.ipynb         # Jupyter Notebook file
├── README.md                    # Instructions
├── requirements.txt             # Dependencies
```

### 6. Dependencies
The Python libraries required for this project are listed in the `requirements.txt` file. Here's the list of dependencies:

```
pandas==1.3.3
numpy==1.21.2
matplotlib==3.4.3
seaborn==0.11.2
scikit-learn==1.0.2
tensorflow==2.5.0
xgboost==1.5.0
geopy==2.2.0
```

To manually install these, use:

```bash
pip install -r requirements.txt
```

### Troubleshooting

- **Missing Libraries**: Ensure all dependencies are installed. If you encounter missing libraries, install them manually using pip.
  ```bash
  pip install notebook
  ```

