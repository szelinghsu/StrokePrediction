![Tiles](header.jpg)
## Motivation and objectives
Stroke is the No. 5 cause of death and a leading cause of serious long-term disability in the United States. According to CDC, stroke kills nearly 150,000 of the 860,000 Americans who die of cardiovascular disease each year. Stroke causes brain tissue to die and in turn lead to brain damage, disability, and death. Every year, about 800,000 people in the United States have a stroke and about 25% of the cases are recurrent. People who had a stroke before have a higher risk of having a recurrent stroke.

There are many factors contribute to the risk of stroke. Some are beyond one’s control like gender and age. Others can be controlled like high blood pressure, diabetes, obesity and smoking habits. The objectives of this project are to analyze 10 factors in relation to stroke and to predict the likelihood of a patient having a stroke.

## Data source
This [dataset](https://www.kaggle.com/fedesoriano/stroke-prediction-dataset) is taken from Kaggle.com for this project.

## Project directories
- [dataset](https://github.com/szelinghsu/StrokePrediction/tree/master/dataset) contains 
  - [healthcare-dataset-stroke-data.csv](https://github.com/szelinghsu/StrokePrediction/blob/master/dataset/healthcare-dataset-stroke-data.csv) the original dataset
  - [healthcare-dataset-stroke-data-cleaned.csv](https://github.com/szelinghsu/StrokePrediction/blob/master/dataset/healthcare-dataset-stroke-data-cleaned.csv) the dataset after cleaning
- [notebook](https://github.com/szelinghsu/StrokePrediction/tree/master/notebook) contains
  - [StrokePrediction_Preprocessing.ipynb](https://github.com/szelinghsu/StrokePrediction/blob/master/notebook/StrokePrediction_Preprocessing.ipynb) for data cleaning and imputing missing values
  - [StrokePrediction_EDA.ipynb](https://github.com/szelinghsu/StrokePrediction/blob/master/notebook/StrokePrediction_EDA.ipynb) for exploratory data analysis
  - [StrokePrediction_Modeling.ipynb](https://github.com/szelinghsu/StrokePrediction/blob/master/notebook/StrokePrediction_Modeling.ipynb) for machine learning modeling
    - Used Threshold-moving method to handle imbalanced dataset problem
    - Used Recall, Diagnostic odds ratio, and ROC AUC score as metrics
    - Models implemented: Logistic Regression, K-Nearest Neighbors, Decision Tree, Random Forest, Gradident Boosting, XGBoost, Tuned Logistic Regression, Tuned Random Forest, and Tuned Gradient Boosting
- [report](https://github.com/szelinghsu/StrokePrediction/tree/master/report) contains 
  - [Stroke Prediction Final Report.pdf](https://github.com/szelinghsu/StrokePrediction/blob/master/report/Stroke%20Prediction%20Final%20Report.pdf) the final project report
  - [Stroke Prediction Presentation Slides.pdf](https://github.com/szelinghsu/StrokePrediction/blob/master/report/Stroke%20Prediction%20Presentation%20Slides.pdf) the project presentation slides
