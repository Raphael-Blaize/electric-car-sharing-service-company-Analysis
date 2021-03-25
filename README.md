# electric-car-sharing-service-company-Analysis
Python Project for an electric-car-sharing -company. Cleaning and Analyzing the datasets in-order to provide insights to electric car usage over time 

#### -- Project Status: [Completed]

## Project Intro/Objective
The purpose of this project is to analyze the electric car usage over time by the consumers over various fields

### Partner
* [Moringa School]
* https://moringaschool.com/

### Methods Used
* Descriptive Statistics
* Data Visualization
* Data Analysis

### Technologies
* Python
* Pandas,Numpy,Gooogle Colab

```python
import pandas as pd # python library that import datasets into a working env and does so much more such as helping in cleaning datasets etc
import numpy as np # offers comprehensive mathematical functions etc
```

## Project Description
 * Data Soruces used
    * Autolib-Dataset - http://bit.ly/autolib_dataset
    * Autlib dataset description - https://drive.google.com/a/moringaschool.com/file/d/13DXF2CFWQLeYxxHFekng8HJnH_jtbfpN/view?usp=sharing
    * 
  * Data Cleaning Methods used
    *  Histogram to check the skewness of the data
    *  IQR to get rid of outliers in the data
    *  No null/missing values in the dataset 
    *  No duplicates in the dataset
    *  Concatinating of columns in the dataset
    *  Dropping of unnecessary columns in the dataset
    
  * Questions to be able to solve the challenge 
     *  1. Identify the most popular hour of the day for picking up a shared electric car (Bluecar) in the city of Paris over the month of April 2018.
     *  2. What is the most popular hour for returning cars?
     *  3. What station is the most popular?
     *  4. What postal code is the most popular for picking up Blue cars? Does the most popular station belong to that postal code?
     *  5. Do the results change if you consider Utilib and Utilib 1.4 instead of Blue cars? 

## Needs of this project
- data exploration/descriptive statistics
- data processing/cleaning - involves taking care of missing data, outliers and duplicates before after merging the datasets
- Data Repoort 

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate

## License
[GPL](https://www.gnu.org/licenses/gpl-3.0.en.html)
