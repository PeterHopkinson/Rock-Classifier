# Rock-Classifier
Computer vision project that uses a neural network to classify rock types

https://github.com/ph3g16/Drill-Core-Image-Analysis

Rock features were selected by hand and saved with an alpha channel denoting areas which are not suitable for training.
The algorthm iterates over each feature to generate a large number of labelled training images.
The network is trained, tested via cross validation, and used to create a map of predicted rock types.
The maps can be used to estimate mineral densities and pick out features which may be of further interest. An equivalent mapping would take a team of experts months of effort.

Example output:
![Rock mapping example](Images/Rock_Mapping_Example_1.jpg)