## Genetic Programming in Python

### Symbolic Regressor 
This example showcases using the SymbolicRegressor to fit a symbolic relationship to synthetic data and compares it with other non-linear models.

The process involves:

1. Creating synthetic data based on a specific mathematical relationship.
2. Training the SymbolicRegressor using genetic programming.
3. Comparing the results with DecisionTreeRegressor and RandomForestRegressor.

### Symbolic Transformer
This example demonstrates using the SymbolicTransformer to generate new non-linear features automatically and improve linear regression performance.

The steps include:

1. Loading the Diabetes housing dataset and shuffling it.
2. Training the transformer on a subset of the data.
3. Applying the trained transformer to the entire dataset and combining the new features.
4. Training a Ridge regressor and comparing the performance.

### Symbolic Classifier
Continuing the scikit-learn classifier comparison example, this demonstration includes the SymbolicClassifier and showcases decision boundaries found using genetic programming.

The process includes:

1. Comparing decision boundaries found by SymbolicClassifier with other classifiers.


