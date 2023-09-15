# Heart disease prediction project using ML classification models
## Introduction to the project 
The rising incidence of heart disease is a major public health concern, underscoring the importance of early detection and intervention. Accurately and efficiently diagnosing heart disease is a challenging task, as it involves numerous risk factors, such as cholesterol levels, smoking habits, obesity, family history, blood pressure, and working conditions.

Thankfully, advances in machine learning algorithms have made it possible to develop predictive models that can help healthcare professionals identify individuals at risk of heart disease. By using regression models or the KNN method, machine learning algorithms can analyze large datasets of patient information and generate accurate predictions.

Developing these models can have a significant impact on public health, potentially saving tens of thousands of lives in the future. Being a part of such a critical endeavor is a humbling and inspiring experience, as it highlights the immense potential of machine learning to improve human health and well-being.
## How others should get started 
### Install

This project requires **Python** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://jupyter.org/install.html).

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](https://www.anaconda.com/download/) distribution of Python, which already has the above packages and more included. 

### Code

Template code is provided in the `HeartDiseacePrediction.ipynb` notebook file. You will also be required to use the included `HeartDiseacePrediction.ipynb` 
Jupyter Notebook  file and the `heart.csv` dataset file to complete your work.

### Run

In a terminal or command window, navigate to the top-level project directory `HeartDiseacePrediction/` (that contains this README) and run one of the following commands:
```bash
ipython notebook HeartDiseacePrediction.ipynb
```  
or
```bash
jupyter notebook HeartDiseacePrediction.ipynb
```
or open with Juoyter Lab
```bash
jupyter lab
```

This will open the Jupyter Notebook software and project file in your browser.

## About Dataset
This data set dates from 1988 and consists of four databases: Cleveland, Hungary, Switzerland, and Long Beach V. It contains 76 attributes, including the predicted attribute, but all published experiments refer to using a subset of 14 of them. The "target" field refers to the presence of heart disease in the patient. It is integer valued 0 = no disease and 1 = disease.
Attribute Information:
`age`
`sex`
`chest pain type (4 values)`
`resting blood pressure`
`serum cholestoral in mg/dl`
`fasting blood sugar > 120 mg/dl`
`resting electrocardiographic results (values 0,1,2)`
`maximum heart rate achieved`
`exercise induced angina`
`oldpeak `= ST depression induced by exercise relative to rest
`the slope of the peak exercise ST segment`
`number of major vessels (0-3) colored by flourosopy`
`thal`: 0 = normal; 1 = fixed defect; 2 = reversable defect`
The names and social security numbers of the patients were recently removed from the database, replaced with dummy values.

## All the output examples I have on each step you can see in  `HeartDiseasePrediction.ipynb` Jupyter notebook file.
# The results of model: accuracy and prediction for the given project
## Summary

