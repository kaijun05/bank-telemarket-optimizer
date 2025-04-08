# **Optimizing Bank Telemarketing Campaigns through Data Mining: Predictive Modeling and Customer Segmentation 🏦**
CDS6314 Data Mining (Trimester October/November 2024 - Term 2430)

## **Overview**
<div align="justify">
<p>
This project focuses on the application of data mining techniques to optimize telemarketing strategies in the banking sector. 
The primary objective is to improve the success rates of bank telemarketing campaigns by analyzing customer data and predicting subscription outcomes. 
</p>
</div>

## **Dataset**
<div align="justify"> 
<p>
The dataset contains information from a Portuguese bank's direct marketing campaigns, sourced from 
<a href="https://www.kaggle.com/datasets/berkayalan/bank-marketing-data-set/data">Kaggle</a>. It includes:
</p>
<ul>
  <li>
    <strong>Customer demographics (age, job, marital status, education)</strong>
  </li>
  <li>
    <strong>Contact information (communication type, day, month)</strong>
  </li>
  <li>
    <strong>Previous campaign outcomes</strong>
  </li>
  <li>
    <strong>Socio-economic context attributes</strong>
  </li>
</ul>
</div>

## **Key Features**
<div align="justify"> 
<ul>
  <li>
    <strong>Comprehensive Data Preprocessing</strong>: Handling missing values, encoding categorical variables, and feature scaling.
  </li>
  <li>
    <strong>Exploratory Data Analysis</strong>: In-depth analysis of customer attributes and their relationship with subscription outcomes.
  </li>
  <li>
    <strong>Advanced Classification Models</strong>: Implementation of Logistic Regression, Decision Trees, Random Forest, and Gradient Boosting.
  </li>
  <li>
    <strong>Customer Segmentation</strong>: K-means clustering to identify distinct customer groups.
  </li>
  <li>
    <strong>Model Evaluation</strong>: Thorough assessment using accuracy, sensitivity, specificity, AUC-ROC, and F1-score.
  </li>
  <li>
    <strong>Performance Visualization</strong>: Confusion matrices and ROC curves to visualize model performance.
  </li>
</ul>
</div>

## **Results**
The project yielded the following key insights:
<div align="justify"> 
<ul>
  <li>
    <strong>Gradient Boosting</strong> and <strong>Random Forest</strong> models performed exceptionally well in predicting subscription outcomes.
  </li>
  <li>
    <strong>Gradient Boosting</strong> achieved the highest F1-Score (63.03% to 63.69%) overall, showing the best balance between precision and recall.
  </li>
  <li>
    <strong>Random Forest</strong> excelled in Specificity (94.72% to 95.91%), making it ideal for minimizing false positives.
  </li>
  <li>
    <strong>Logistic Regression</strong> demonstrated high sensitivity (91.49% to 91.81%), ensuring fewer missed opportunities.
  </li>
  <li>
    <strong>Customer Segmentation</strong> revealed four distinct clusters, with Cluster 3 (older, higher-educated individuals) showing the highest subscription rate (42.8%).
  </li>
</ul>
</div>
<div align="justify">
This suggests that targeted marketing strategies can significantly improve campaign effectiveness. 
Overall, this project demonstrates how data mining can enhance telemarketing campaigns, leading to improved customer acquisition and resource optimization. 
Future work could explore advanced algorithms and real-time data integration to further refine predictions and segmentation.
</div>

## **Installation & Requirements**
Before running the project, make sure you have installed the following:
* Python 3.13+
* pip (Python Package Manager)
* Virtual Environment
* Jupyter Notebook

1. In your terminal, clone the repository by typing
```bash
git clone https://github.com/kaijun05/bank-telemarket-optimizer.git
cd bank-telemarket-optimizer
```
2. Create a virtual environment (recommended)
```bash
# On macOS/Linux
python<version> -m venv <virtual-environment-name>
source <virtual-environment-name>/bin/activate  

# On Windows
python<version> -m venv <virtual-environment-name>
<virtual-environment-name>\Scripts\activate
```
3. Install Jupyter Notebook. Alternatively, you may install Jupyter Notebook through Anaconda (recommended) [here](https://docs.jupyter.org/en/latest/install/notebook-classic.html)
```bash
pip install jupyter
```
4. Install the required packages by typing:
```bash
pip install numpy
pip install pandas
pip install matplotlib
pip install seaborn
pip install statistics
pip install scikit-learn
pip install imbalanced-learn
```
5. If you use Conda environment, you can install dependencies using Conda as such:
```bash
conda create --name <env> --file requirements.txt
```

## **Running the Project**
1. Open the repository in your terminal and activate the virtual environment:
```bash
source env/bin/activate  # On macOS/Linux  
env\Scripts\activate  # On Windows
```
2. Start Jupyter Notebook
```bash
jupyter notebook
```
3. Open the notebook (`main.ipynb`) and **run all the cells**.
