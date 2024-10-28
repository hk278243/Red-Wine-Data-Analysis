Red Wine Data

Data Set Information:

The two datasets are related to red and white variants of the Portuguese "Vinho Verde" wine.  Due to privacy and logistic issues, 
only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).

These datasets can be viewed as classification or regression tasks. The classes are ordered and not balanced (e.g. there are many more normal wines than excellent or poor ones). 
Outlier detection algorithms could be used to detect the few excellent or poor wines. Also, we are not sure if all input variables are relevant. 
So it could be interesting to test feature selection methods.


Attribute Information:

Input variables (based on physicochemical tests):
- 1 - fixed acidity
- 2 - volatile acidity
- 3 - citric acid
- 4 - residual sugar
- 5 - chlorides
- 6 - free sulfur dioxide
- 7 - total sulfur dioxide
- 8 - density
- 9 - pH
- 10 - sulphates
- 11 - alcohol

Output variable (based on sensory data):
- 12 - quality (score between 0 and 10)

Description :- 
The dataset you're working with is related to red and white variants of Portuguese "Vinho Verde" wine, containing physicochemical inputs such as acidity, residual sugar, chlorides, and alcohol, among others. 
The target variable is wine quality, rated on a scale from 0 to 10. The exploratory data analysis (EDA) focuses on understanding the distribution of wine quality and relationships between the input features. 
The dataset is imbalanced, making it suitable for classification or regression tasks, and SMOTE (Synthetic Minority Over-sampling Technique) is used to handle class imbalance by oversampling the minority classes. 
