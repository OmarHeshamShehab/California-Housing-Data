# Machine-Learning-in-2024-Beginner's-Course

The course begins with a **Machine Learning Roadmap for 2024**, emphasizing career paths and beginner-friendly theory. Then the course moves on to hands-on practical applications and a comprehensive end-to-end project using Python.

**Course Link**: [Machine Learning Roadmap](https://www.youtube.com/watch?v=bmmQA8A-yUA&t=193s)

## Table of Contents
- [Project Overview](#project-overview)
- [File and Folder Description](#file-and-folder-description)
  - [1- Stats_Models.ipynb](#1--stats_modelsipynb)
  - [2- Sklearn.ipynb](#2--sklearnipynb)
  - [housing.csv](#housingcsv)
- [Outlier Detection Using IQR](#outlier-detection-using-iqr)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)

## Project Overview

This repository is part of a beginner's course in machine learning for 2024. It introduces the fundamental concepts of machine learning, followed by practical applications using real-world datasets. The **California Housing Data** is used to explore various machine learning techniques, including statistical models and algorithms from `sklearn`.

## File and Folder Description

### 1- Stats_Models.ipynb
   - **Description**: This Jupyter notebook focuses on applying statistical models to the **California Housing Data**. It explores concepts such as linear regression, correlation analysis, and summary statistics, all aimed at providing insights into housing prices in California.

### 2- Sklearn.ipynb
   - **Description**: This notebook utilizes `sklearn` to implement machine learning algorithms on the **California Housing Data**. It includes models like linear regression, decision trees, and more, with a focus on predictive modeling and model evaluation.

### housing.csv
   - **Description**: This CSV file contains the California Housing dataset, which includes data on various attributes like median house value, median income, population, and more for different districts in California.

## Outlier Detection Using IQR

### InterQuantile Range (IQR)

Summary of Outlier Detection Using the IQR Method:

- **IQR (Interquartile Range)**: Measures the spread of the middle 50% of data. It's calculated as the difference between the third quartile (Q3) and the first quartile (Q1).

- **Outlier Detection**: Outliers are values that are significantly higher or lower than the rest of the data.

#### 1.5 IQR Rule:

The constant 1.5 is used to define the bounds for outliers:
- Lower Bound = Q1 - 1.5 × IQR
- Upper Bound = Q3 + 1.5 × IQR

Any values outside these bounds are considered outliers.

#### Why 1.5?

- It’s a standard choice in statistics, chosen to detect outliers while balancing sensitivity.
- It helps to catch values that are unusually far from the center of the data without being overly strict.
- This rule is widely used because it works well with many types of datasets, especially those that have a bell-shaped or normal distribution.

## Setup and Installation

### Prerequisites
To run the notebooks and code in this repository, you'll need:
- Python 3.x installed.
- Jupyter Notebook or JupyterLab installed (`pip install jupyterlab`).
- Necessary Python packages listed in `requirements.txt` (if provided).

### Installation Steps

1. Clone the repository:
    ```bash
    git clone https://github.com/username/California-Housing-Data.git
    ```

2. Navigate to the project directory:
    ```bash
    cd California-Housing-Data-main
    ```

3. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the Jupyter notebooks in your environment:
    ```bash
    jupyter lab
    ```

## Usage

1. Open the Jupyter notebooks `1- Stats_Models.ipynb` or `2- Sklearn.ipynb` to start exploring the California Housing data.

2. Explore statistical models in the `1- Stats_Models.ipynb` notebook and machine learning algorithms using `sklearn` in the `2- Sklearn.ipynb` notebook.

3. Analyze the output and modify the notebooks to experiment with different models and techniques.

## Contributing

Contributions are welcome! If you'd like to improve the code, add new notebooks, or suggest enhancements, please submit a pull request.

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature-branch
    ```
3. Make your changes and commit:
    ```bash
    git commit -m 'Add new feature'
    ```
4. Push your branch to GitHub:
    ```bash
    git push origin feature-branch
    ```
5. Open a pull request.


## Acknowledgements

Special thanks to the creators of this course and the open-source libraries used in this project, including `sklearn`, `pandas`, and `matplotlib`.
