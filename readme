Weight of Evidence & Information Value
The implementation of Weight of Evidence (WOE) encoding and Information Value (IV). Lots of implementation out there, yet this repo offers one using PySpark for data processing.

What you need
Python >= 3.7.0
PySpark >= 2.4.0
Install
Clone this repo
Go to the root directory of the local repo
Run python setup.py install
Quickstart
Please check the main module for the example.

A) Prepare the data
df = <spark_dataframe>
cols_to_woe = <list_of_categorical_columns_to_encode>
label_col = <label_column>
good_label = <good_label>
B) WOE Encoding
woe = WOE_IV(df, cols_to_woe, label_col, good_label)
woe.fit()

encoded_df = woe.transform(df)
C) Information Value
ivs = woe.compute_iv()
