# K-Nearest Neighbors (KNN) Classifier Project  

This project demonstrates how to implement a **K-Nearest Neighbors (KNN)** classifier using Python and scikit-learn. The dataset used is classified data that has been normalized for optimal performance. We also use the **Elbow method** to determine the optimal value of K.

## Table of Contents  
- [Project Overview](#project-overview)  
- [Dataset](#dataset)  
- [Project Structure](#project-structure)  
- [Dependencies](#dependencies)  
- [How to Run](#how-to-run)  
- [Results](#results)  
- [License](#license)

---

## Project Overview  
K-Nearest Neighbors (KNN) is a simple yet powerful machine learning algorithm used for both classification and regression. In this project:
1. We preprocess the data using **StandardScaler** to normalize feature values.
2. We use **KNN** with various values of K and apply the **Elbow method** to determine the best K.
3. We evaluate the model using **confusion matrix** and **classification report** metrics.

---

## Dataset  
The dataset used is `Classified Data.csv`. It contains various features along with a target class column (`TARGET CLASS`) used for binary classification. The data is normalized to ensure that all features have the same scale, which is crucial for the KNN algorithm.

---

## Project Structure  
 │──KNN Project
 ├── KNN Project.ipynb # Jupyter Notebook containing the full code 
 ├── Classified Data.csv # Dataset used in the project 
 └── README.md # Project documentation

---

## Dependencies  
Ensure you have the following libraries installed before running the notebook:

```bash
pip install pandas numpy scikit-learn seaborn matplotlib
```

---

## How to Run
1.Clone the repository:
```bash
git clone https://github.com/ArezooAraste/knn-project.git
cd knn-project
```

2.Install dependencies:
```bash
pip install -r requirements.txt
```
Alternatively, you can manually install the libraries listed in the Dependencies section.

3.Run the Jupyter Notebook:
```bash
jupyter notebook KNN\ Project.ipynb
```

---

## Results
Confusion Matrix and Classification Report are used to evaluate the performance of the model.
The Elbow method helps find the optimal K value by plotting the error rate vs. K values.
The final model with the optimal K value achieves improved classification performance.
Example of the Elbow Plot:


Update the path to the image if necessary.

---

## License
This project is licensed under the MIT License - see the LICENSE file for details.


---
