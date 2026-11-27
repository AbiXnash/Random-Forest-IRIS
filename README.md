# Random-Forest-IRIS

A Random Forest classifier on the classic [Iris dataset](https://archive.ics.uci.edu/dataset/53/iris), in one
Jupyter notebook.

## What the notebook does

1. Loads `iris.csv` and checks for nulls and column types.
2. Plots the relationships between the four measurements (sepal and petal length and width).
3. Encodes `Species` as numbers (Setosa 0, Versicolor 1, Virginica 2) and looks at correlations.
4. Splits the data, trains scikit-learn's `RandomForestClassifier`, and prints the accuracy and a classification
   report.

In the saved run, accuracy on the held-out set was **0.88**.

## Run it

```bash
pip install pandas scikit-learn matplotlib seaborn jupyter
jupyter notebook "IRIS Random Forest.ipynb"
```

## Licence

MIT, see [LICENSE](LICENSE).
