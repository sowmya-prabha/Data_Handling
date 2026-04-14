Since age and city has null values, they are filled with median and mode respectively.
Dropped duplicate values using drop_duplicates().
Applied One-Hot Encoding to city and LabelEncoding to gender.
MinMax scaling and StandardScaler to both age and annual_income.


StandardScaler → use when data is roughly normal and may have outliers; it centers data around 0 with unit variance.
MinMaxScaler → use when you need values in a fixed range (0–1), especially for neural networks and when there are no strong outliers.
