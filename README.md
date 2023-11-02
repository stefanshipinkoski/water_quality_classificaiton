# Water Quality Classification Project:

This project employs machine learning techniques to classify the water quality in Europe using a dataset obtained from the European Environment Agency (EEA). The EEA dataset contains a vast amount of information on the quality and status of Europe's water resources, including rivers, lakes, groundwater bodies, transitional, coastal, and marine waters.


# Project Goal:

The goal of the project is to use the Water Quality Index (WQI) to classify the quality of Europe's water resources accurately. The project contains all the necessary code and documentation to replicate it.


# Data Preparation:

The dataset is quite large (16GB), so a subset of it will be utilized for the project. The data preparation process includes data cleaning and preprocessing steps, such as selecting relevant data, dealing with missing values, outliers, and scaling the data. The Water Quality Index (WQI) is calculated for each water resource to classify its quality., which includes:

- Selecting relevant data
- Creating custom datasets
- Dealing with missing values
- Dealing with outliers
- Calculating the Water Quality Index (WQI)
- Scaling the data


# Build Classificaiton Models:

After the data is processed we going to utilize 3 machine learning models to find the optimal results with the  hyperparameter tuning using the `RandomSearchCV` and `GridSearchCV`:

- Decision Tree Classifier
- Support Vector Machine (SVC)
- K-Nearest Neighbors (KNN) 


# Technologies Used:

- Python 3.x
- Scikit Learn
- Pandas
- NumPy
- Matplotlib


1. Clone this repository by running:
 ```bash
git clonehttps://github.com/stefanshipinkoski/water_quality_classificaiton.git

```

2. Navigate to the project directory:
```bash
cd water_quality_classificaiton
```

3. Create a conda environment and install the required dependencies:

```bash
conda env create -f enviorment.yml
```

4. Activate the conda environment:

```bash
conda activate water-quality-env
```





## Usage

1. Launch a Jupyter Notebook session within the conda environment: 
2. Run the `data_preprocessing.ipynb` notebook to clean and preprocess the dataset.
3. Run the `water_quality_classification.ipynb` notebook to classify the quality of water resources in Europe.


# Contributing:

Please feel free to contribute to this project by submitting pull requests or creating issues.
