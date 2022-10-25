# Uc Berkeley Extension Data Science Bootcamp

## Module 17 - Supervised Machine Learning & Credit Risk

### Overview of Machine Learning

- Machine learning can be divided into 3 learning categories.
  - Supervised learning
  - Unsupervised learning
  - Deep learning
- Supervised machine learning
  - Deals with labeled data (ex: predict, based on data from previous patients, whether a new patient has diabetes)
  - This learns with examples
  - In the data, there are both inputs (features) ‘x’ and output (labels) ‘y’.
  - Features are the variables used to make a prediction. Target is the predicted outcome.
  - Two types of supervised learning
    - Regression - It predicts a number out of infinitely many possible numbers; used to predict continuous variables(ex: height, exercise patterns).
    - Classification - it predicts finite number of categories or classes – used to predict discrete variables
- Unsupervised machine learning
  - It divides the data into regions based on unlabeled data properties/structure.
  - Used to predict descreate variables(ex: age, sex)
  - In data, there are no output labels, data only contains inputs.
  - Three types of unsupervised learning
    - Clustering – group similar data points together
    - Anomaly detection – find unusual data points
    - Dimensionality reduction – compress data using fewer numbers

### Linear Regression model creation

- Dataset reshaping - this reformats the specified data to the form that Scikit-learn's specifications follows. The command uses here is below,

> X = df.YearsExperience.values.reshape(-1,1)
