<h1>Polycystic Ovary Syndrome (PCOS) Diagnosis</h1>

**Introduction**

Polycystic ovary syndrome (PCOS) is a common hormonal disorder in women of reproductive age. It is characterized by infrequent, irregular, or prolonged menstrual periods, as well as elevated levels of male hormones (androgens). Women with PCOS may also have multiple cysts on their ovaries.

This project aims to diagnose PCOS and infertility issues using physical and clinical parameters. The dataset includes data from ten different hospitals across Kerala, India, comprising 44 parameters.

Dataset Description
Data Collection: The dataset includes physical and clinical parameters used to diagnose PCOS and infertility issues. It is collected from ten hospitals across Kerala, India.

**Parameter Details:**

The unit used for height is feet, converted to centimeters (cm).
Blood pressure is entered as systolic and diastolic separately.
RBS stands for Random Blood Sugar test.
Beta-HCG cases are indicated as Case I and Case II.
Blood groups are indicated as follows: A+ = 11, A- = 12, B+ = 13, B- = 14, O+ = 15, O- = 16, AB+ = 17, AB- = 18.
Data Cleaning: The dataset contains an unnamed column that can be eliminated as it does not provide relevant information.

**Libraries Used**\
pandas: Data manipulation and analysis.\
numpy: Numerical operations.\
matplotlib and seaborn: Data visualization.\
scikit-learn: Machine learning modeling and evaluation.\

**Modeling Approach**\
Various machine learning models are employed for PCOS diagnosis, including:\
Logistic Regression\
Random Forest Classifier\
Decision Tree Classifier\
K-Nearest Neighbors Classifier\
XGBoost Classifier\
Gradient Boosting Classifier\
AdaBoost Classifier\

**Evaluation Metrics**
Evaluation of models is based on the following metrics:\
Accuracy Score
Classification Report
Precision, Recall, and F1-Score
Confusion Matrix
ROC-AUC Score

**Installation and Usage**\
Clone the repository:
```
git clone https://github.com/your_username/pcos-diagnosis.git
```
Install dependencies:
```
pip install -r requirements.txt
```
Run the script pcos_diagnosis.py to perform PCOS diagnosis and evaluate different models.

**File Descriptions**\
**pcos_diagnosis.ipynb:** Main script containing data preprocessing, modeling, and evaluation.\
**PCOS_dataset.csv:** Dataset containing physical and clinical parameters.\
**requirements.txt:** List of dependencies required to run the project.\

**Results**
The results of PCOS diagnosis and model evaluation are discussed, including insights gained from the analysis and performance metrics of the models.
