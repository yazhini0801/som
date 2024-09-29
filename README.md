# som

THIS IS YAZHINI-22mis1055 I HAVE IMPLEMENTED SOM FOR TITANIC DATASET

In this project, we loaded the Titanic dataset from a GitHub repository using the `pandas` library, then preprocessed the data by handling missing values, dropping irrelevant columns, and converting categorical variables into numerical format through one-hot encoding. To prepare the data for analysis, we normalized the feature values using `MinMaxScaler`, scaling them to a range of [0, 1]. We implemented a Self-Organizing Map (SOM) using the `MiniSom` library, initializing a 10x10 grid and training it on the scaled dataset for 1000 iterations to assign each data point to a cluster based on the winning neuron. Subsequently, we analyzed the distribution of instances in each cluster using `pandas` to count the occurrences. For visualization, we employed `matplotlib` and `seaborn` to create a pie chart that illustrated the cluster distribution, enhanced with spacing, explode effects, and shadows for clarity. Additionally, we designed a detailed bar graph showing the count of instances per cluster, featuring value annotations, grid lines, and distinct colors for improved interpretation. Overall, this project provided practical experience in data manipulation, clustering analysis, and effective visualization techniques, helping to deepen understanding of the Self-Organizing Map method and its application in data analysis.
