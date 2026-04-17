# rivya singla 
# 25070123091 
## Aim

To perform data preprocessing using Python by applying normalization techniques such as Min Max normalization Z score normalization and Decimal scaling and also applying categorical data encoding methods like Label Encoding One Hot Encoding and Dummy Encoding in order to prepare the dataset for machine learning models

## Theory

Data preprocessing is an important step in data analysis and machine learning It involves transforming raw data into a clean structured and usable format The main tasks in preprocessing include normalization of numerical data and encoding of categorical data

Normalization is used to scale numerical values so that they fall within a specific range or follow a standard distribution Encoding is used to convert categorical data into numerical form so that machine learning algorithms can understand and process it

Min Max normalization scales the data into a fixed range usually between zero and one It is calculated by subtracting the minimum value from each data point and dividing by the range of the data This method preserves the relationships between values

Z score normalization also known as standardization transforms data based on mean and standard deviation It centers the data around zero and scales it so that the standard deviation becomes one This method is useful when data contains outliers

Decimal scaling normalizes data by dividing each value by a power of ten This method is simple and is used when the data range is large

Label encoding is used to convert categorical values into numerical labels For example male can be converted to one and female to zero This method is simple but may introduce an unwanted order among categories

One hot encoding creates separate columns for each category and assigns binary values This method avoids any ordinal relationship between categories and is widely used for nominal data

Dummy encoding is similar to one hot encoding but it removes one column to avoid redundancy and multicollinearity It is mainly used in regression models

## Explanation of Commands

The pandas library is used for data manipulation and analysis while numpy is used for numerical operations

The DataFrame function is used to create a table from a dictionary structure where data is organized into rows and columns

Min Max normalization is performed by subtracting the minimum value of a column and dividing by the difference between maximum and minimum values

Multiple columns can be normalized at once by selecting the required columns and applying the same formula

Z score normalization is performed by subtracting the mean of the column and dividing by its standard deviation

Decimal scaling is done by dividing the values of a column by a suitable power of ten to reduce their magnitude

Label encoding is implemented using LabelEncoder from sklearn preprocessing which converts categorical text data into numerical form

One hot encoding is performed using get dummies function in pandas which creates new columns for each category in a column

Multiple columns can be encoded at once by passing a list of column names to the get dummies function

Dummy encoding is achieved by using get dummies with drop first set to true which removes one category to avoid redundancy

## Conclusion

In this experiment data preprocessing techniques were successfully applied Numerical data was normalized using Min Max Z score and Decimal scaling methods to bring consistency in data values Categorical data was converted into numerical form using Label Encoding One Hot Encoding and Dummy Encoding These techniques help improve the performance of machine learning models by making the dataset clean structured and suitable for analysis
