# Drug_classification
Introduction
In this project, I have implemented a drug classification system using a dataset on the DevCloud platform. The dataset used for this project contains information about different drugs and their corresponding attributes. The goal is to classify drugs based on their properties and characteristics.

Dataset
The drug classification dataset consists of a collection of drug samples, each represented by several features such as molecular weight, chemical structure, solubility, and other relevant attributes. The dataset also includes the corresponding labels indicating the drug classes or categories.

The dataset provides a valuable resource for training and evaluating machine learning models to accurately classify drugs based on their properties. It enables the development of models that can assist in drug discovery, prediction of drug interactions, and other pharmaceutical applications.

oneAPI
To optimize the implementation of the drug classification system, I leveraged the power of oneAPI. oneAPI is an open, unified programming model that provides developers with a single programming model across different types of processors, including CPUs, GPUs, and FPGAs.

By utilizing oneAPI, I was able to harness the computational capabilities of various hardware accelerators and optimize the code for better performance and efficiency. This allowed for faster training and inference times, enabling real-time drug classification.

Models Used
For the drug classification task, I employed the Random Forest algorithm, a popular machine learning technique known for its robustness and ability to handle complex datasets. The Random Forest model creates an ensemble of decision trees and makes predictions based on the votes of multiple trees.

The Random Forest algorithm is well-suited for this task as it can handle a large number of features and effectively capture the relationships between drug attributes and their corresponding classes. The model was trained on the dataset using various tree-based techniques and optimized using feature selection and hyperparameter tuning.

Results and Discussion
After training the Random Forest model on the drug classification dataset, I achieved an impressive accuracy of approximately 96.6%. This indicates that the model can effectively classify drugs based on their attributes with a high level of accuracy.

The high accuracy achieved by the model demonstrates its potential utility in real-world scenarios such as pharmaceutical research, drug discovery, and personalized medicine. It can aid in the identification of drug candidates with specific properties or in predicting the efficacy of certain drugs based on their characteristics.

However, it is important to note that the performance of the model may vary depending on the specific dataset and its characteristics. Further evaluation and testing on diverse datasets are necessary to validate the model's generalizability and robustness.

In conclusion, the implementation of the drug classification system using the Random Forest model and optimization with oneAPI has yielded promising results. The high accuracy achieved indicates the potential of this approach in drug-related applications. Further improvements and refinements can be explored to enhance the model's performance and expand its capabilities in the field of pharmaceutical research and development.
