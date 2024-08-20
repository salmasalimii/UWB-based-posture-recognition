# Benchmarking ML Approaches to UWB based posture recognition for human robot interaction

## Introduction
This work introduces a UWB range dataset featuring five distinct individuals in nine different postures, representing nine separate classes. The dataset is designed for classification using KNN, SVM, and MLP models, aimed at advancing human-robot interaction.



## What is included in this repo?

Examples for UWB based posture recognition for human robot interaction

![main_diagram_page-0001](https://github.com/user-attachments/assets/f92bb1e3-9263-4499-88db-dc931aac6233)


## Installation

Clone this repo 
```
git clone git@github.com:salmasalimii/UWB-based-posture-recognition.git
```



## Machine Learning Models Used

### K-Nearest Neighbors (KNN)
```
from sklearn.neighbors import KNeighborsClassifier

knn = KNeighborsClassifier(n_neighbors=2)
knn.fit(x_train,y_train)
pred = knn.predict(x_test)
```

### Support Vector Machine (SVM)
```
from sklearn.svm import SVC

model = SVC()
model.fit(x_train, y_train)
predictions = model.predict(x_test)
```

### Multi-Layer Perceptron (MLP)
```
from sklearn.neural_network import MLPClassifier

mlp = MLPClassifier(hidden_layer_sizes=(100,), max_iter=1000, random_state=42)
mlp.fit(x_train, y_train)
predictions = mlp.predict(x_test)
```

The detailed code for implementing these models is available upon request.
