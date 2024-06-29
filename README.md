# Iris Dataset Analysis with PySpark
This project implements K-means, Bisecting K-means, and Decision Tree algorithms in PySpark on the Iris dataset.

## Table of Contents

- [Introduction](#introduction)
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project demonstrates the use of PySpark to perform clustering and classification on the Iris dataset. The Iris dataset is a classic dataset in machine learning and statistics, containing measurements of various attributes of iris flowers and their corresponding species.

## Description

The project consists of three main components:
1. **K-means Clustering**: A traditional clustering algorithm that partitions data into k distinct clusters.
2. **Bisecting K-means Clustering**: A variation of K-means that recursively splits clusters to improve clustering quality.
3. **Decision Tree Classification**: A classification algorithm that uses a tree-like model to make decisions based on input features.

## Installation

To run this project, you need to have PySpark installed. You can install it using pip:

```bash
pip install pyspark
```
Additionally, you need to have Matplotlib and Seaborn for data visualization:

```bash
pip install matplotlib seaborn
```

## Usage
1. **Initialize Spark Session:** The Spark session is initialized with the name "IrisAnalysis".
2. **Load Data:** The Iris dataset is loaded from a CSV file.
3. **Prepare Features:** Features are prepared using VectorAssembler.
4. **K-means Clustering:** K-means algorithm is applied to the data, and results are visualized.
5. **Bisecting K-means Clustering:** Bisecting K-means algorithm is applied, and results are visualized.
6. **Decision Tree Classification:** A decision tree classifier is trained, evaluated, and results are visualized.

## Results
+ **K-means Silhouette Score:** The silhouette score for the K-means clustering model is **0.7482**.
+ **Bisecting K-means Silhouette Score:** The silhouette score for the Bisecting K-means clustering model is **0.6682**.
+ **Decision Tree Accuracy:** The accuracy of the Decision Tree classifier is **1.0**.
  
Visualizations for each clustering method and the decision tree classification are generated using Matplotlib and Seaborn.

## Technologies Used
+ **PySpark:** For data processing and machine learning.
+ **Matplotlib:** For data visualization.
+ **Seaborn:** For enhanced data visualization.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or additions.

## License 
This project is licensed under the MIT License.
