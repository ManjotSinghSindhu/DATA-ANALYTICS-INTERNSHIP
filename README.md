# DATA-ANALYTICS-INTERNSHIP

**Performing Analysis of Meteorological Data**

Let us understand what is Meteorology :
"Meteorology is a branch of the atmospheric sciences which includes atmospheric chemistry and atmospheric physics, with a major focus on weather forecasting. For more knowledge refer https://en.wikipedia.org/wiki/Meteorology ".
You can find the data-set on Kaggle (Source URL: https://www.kaggle.com/muthuj7/weather-dataset). We are going to use numpy, pandas, matplotlib and Datetime libraries of Python to import , extract, clean, transform and plot.

**Hypothesis of the Analysis :**
"Has the Apparent temperature and humidity compared monthly across 10 years of the data indicate an increase due to Global warming."

**Step 1 : Let's start by importing libraries :**
To make use of the functions in a module, you'll need to import the module with an import statement. An import statement is made up of the import keyword along with the name of the module.
Example : import numpy

**Step 2 : Reading data-set using pandas library :**
A data-set is a collection of data. In the case of tabular data, a data set corresponds to one or more database tables, where every column of a table represents a particular variable, and each row corresponds to a given record of the data set in question. In this scenario we are going to read weather History data.

**Step 3 : Cleaning dataset :**
Data cleaning is the process of fixing or removing incorrect, corrupted, incorrectly formatted, duplicate, or incomplete data within a dataset . Dropping unwanted data and converting it according to our requirement.
**NOTE :** We need to analysis data yearly. We need to convert Formatted Date into datetime format. We will do it by using pandas method to_datetime() . Also, we will set Formatted Date as the index to the data-set and resample our data .

**Step 4 : Plotting of Data :**
The purpose of plotting data is to visualize variation or show relationships between variables. We will now plot the line graph to display Humidity and Apparent Temperature(C) over 10 years(2006–2016).We will plot the graph to display average temperature and humidity for all 12 months over the 10 year period . Lets start from First month of the year



**Recognizing Handwritten Digits with scikit-learn**

Recognizing handwritten text is a problem that can be traced back to the first automatic machines that needed to recognize individual characters in handwritten documents. Classifying handwritten text or numbers is important for many real-world scenarios. For example, a postal service can scan postal codes on envelopes to automate the grouping of envelopes which has to be sent to the same place. This article presents recognizing the handwritten digits (0 to 9) using the famous digits data set from Scikit-Learn.

Scikit-Learn is a library for Python that contains numerous useful algorithms that can easily be implemented and altered for the purpose of classification and other machine learning tasks.

We will build a model using Scikit-Learn, train the model, make predictions with it, and finding the accuracy of our prediction(which in our case is 100%).
