# FULL ML Pipeline: EDA| Preprocessing| Modelling| Evaluation|
## Before doing anything, answer these questions:
- What is the exact question I am trying to answer?
- Is this a classification or regression problem (supervised).
- What is the target variable (y) (column you are trying to predict).
- What are the features the model is to use (X) (Columns in X).
- How will I measure success (metrics to use)?

## EDA Checklist.
1. Load and inspect.
```python
    df.head()
    df.shape
    df.dtypes
    df.info()
```
- Number of rows/cols, data types, obvious issues.

2. Summary statistics
```python
    df.describe()
```
- Range, means, extremes

3. Missing values
    ```python 
    df.isnull().sum() 
    ```
- Which columns, how much, pattern or random?

4. Target distribution.
```python
    df[target].value_counts()
```
- Shows class imbalance, whether one has a skewed dist etc.
- If the target has an imbalance greater than 80/20, needs special handling.

5. Feature distribution.
```python
    df.hist() or sns.boxplot()
```
- Normal, skewed or whether one has outliers.

6. Correlations
    df.corr() + heatmap
- Highly correlated features

7. Feature vs target
- Scatter plots, boxplots per class.
