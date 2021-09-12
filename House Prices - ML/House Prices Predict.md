# House Prices Predict
Competition link : https://www.kaggle.com/c/house-prices-advanced-regression-techniques

A task from kaggle which we should predict output as regression task.
It has 81 fetures.
## After checking realized  these tasks for data prepration:
- Handling missing values.
- Encoding string data type.
- Deleting columns which have many nan-values (outliers) .

## Solutions

- Using [KNNImputer](https://scikit-learn.org/stable/modules/generated/sklearn.impute.KNNImputer.html) for filling nan-values with 'k=10'.
- Using [Label Encoding](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.LabelEncoder.html) which handle string data type and convert them to numbers.
- Using a simple for-loop and search columns that have nan-values more than 1100 for deleting the columns.

After data prepration out data is ready to processing.
By searching a lot of time figured out, the most efficient algorithms is [Random Forest](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html).
## These are the algorithms that I already have tested :
- [Linear regression ](http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html)
- [Linear regression lasso](http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Lasso.html)
- [linear regression ridge](http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Ridge.html)
- [Polynomial regression](https://scikit-learn.org/stable/auto_examples/linear_model/plot_polynomial_interpolation.html)
- [Bagging](http://scikit-learn.org/stable/modules/generated/sklearn.ensemble.BaggingRegressor.html)
- [Boosting](http://scikit-learn.org/stable/modules/generated/sklearn.ensemble.BaggingRegressor.html)

## Libraries

The libraries that I've used:

| Libraries | Links |
| ------ | ------ |
| Scikit-learn| https://scikit-learn.org |
| Numpy | https://numpy.org |
| Pandas | https://pandas.pydata.org |
| Matplotlib | https://matplotlib.org |



