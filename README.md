# Anemia Classification: A Comparative Study of SVM and Random Forest Algorithms

## Project Overview
Anemia affects millions of people worldwide, causing reduced oxygen-carrying capacity due to a deficiency in red blood cells or hemoglobin. Accurate and timely diagnosis is essential for effective treatment and management. This project leverages machine learning algorithms, specifically Support Vector Machines (SVM) and Random Forest, to classify anemia cases. 

The objective is to develop a robust model that can assist healthcare professionals in identifying anemia accurately and reliably.

---

## Dataset
### Description
- **Dataset Size**: 113 training data points and 57 testing data points.
- Features include essential health indicators used to identify anemia.

### Preprocessing Steps
1. **Data Encoding**: Reformatted categorical data into numerical format.
2. **Handling Missing Values**: Imputed missing values with the mean.
3. **Handling Outliers**: Replaced outliers with the median.
4. **Normalization**: Scaled features to ensure uniformity and reduce bias.
5. **Transformation**: Applied logarithmic transformation to reduce skewness and minimize the impact of outliers.
6. **Feature Selection**: Dropped highly correlated features to improve model performance.

---

## Data Visualization
Key insights from visualization include:
- The dataset is imbalanced, with peaks in specific regions.
- Distributions reveal potential challenges due to clustering in the data.

---

## Models and Training
### Algorithms Used
1. **Random Forest**
   - Initial model.
   - Improved through hyperparameter tuning.
2. **Support Vector Machines (SVM)**
   - Initial model.
   - Improved through hyperparameter tuning.
3. **Decision Tree** (for comparative analysis)
   - Included to highlight differences in performance.

### Evaluation
- **Metrics**: Accuracy (number of correct classifications).
- **Performance**:
  - SVM: 48 correct classifications (best performance).
  - Random Forest: 47 correct classifications.
  - Decision Tree: 45 correct classifications.

---

## Results and Discussion
### Key Findings
- **SVM performed the best** with 48 correct predictions and only 8 misclassifications.
- **Random Forest** followed closely with 47 correct predictions.
- **Decision Tree** was the least accurate with 45 correct predictions.

### Conclusion
SVM is the most suitable model for anemia classification in this study due to its higher accuracy compared to Random Forest and Decision Tree.

---

## Repository Contents
- `Anemia_Classification.ipynb`: Jupyter Notebook containing the full implementation of data preprocessing, visualization, and model training.
- `Presentation.pdf`: Slides summarizing the project.
- `Anemia-ML-Train.xlsx`: Train Dataset
- `Anemia-ML-Test.xlsx`: Test Dataset
---


## Acknowledgments
- **Dataset**: Thanks to the contributors of the dataset.
- **Tools Used**: Python, Jupyter Notebook, and Google Colab for implementation.

---

## References
Google Colab Link: [Colab Notebook](https://colab.research.google.com/drive/10NUQ49y5SwIUdgUUk-wvDgUEu1u4JhpZ#scrollTo=FKLHbdC_GvjX)
