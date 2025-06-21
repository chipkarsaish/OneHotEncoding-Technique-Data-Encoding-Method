# OneHotEncoding-Technique-Data-Encoding-Method
Process of converting a categorical features values into meaningful numerical values. OneHotEncoding is a method to convert categorical data into a binary (0 or 1) format so that it can be used in machine learning models. Each unique category becomes a new column, and a row has 1 in the column of its category and 0s elsewhere.


eg. Consider a feature in a dataset have three values as red, Green and Blue.

#### Then we can write them as binary vector where each bit correspond to a unique category.

####   Red    Green   Blue
#####  1      0       0              <---Red
#####  0      1       0              <---Green
#####  0      0       1              <---Blue
