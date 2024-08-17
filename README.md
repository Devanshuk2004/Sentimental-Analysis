# Public Sentiment Analysis on Putin-Carlson Interview

## Overview

This project analyzes public sentiments expressed in comments on a significant interview between Vladimir Putin and Tucker Carlson. The discussion touches on key global economic issues and Putin's actions in Ukraine. With over 100,000 comments, this dataset provides a rich source of global perspectives, capturing the world's reactions to the topics discussed.

## Dataset

- **Source**: Comments from the Putin-Carlson interview.
- **Size**: 100,000+ comments.
- **Content**: Textual comments reflecting global opinions on international issues discussed in the interview.

## Data Preprocessing

- **Data Mining**: 
  - Removed unnecessary emojis.
  - Cleansed URLs from the comments to maintain focus on textual content.

## Exploratory Data Analysis (EDA)

- **Reply Counts & Likes**:
  - Analyzed the distribution of reply counts and likes.
  - Applied thresholds to detect and flag potential cyberbullying instances.

- **Visualizations**:
  - **Word Cloud**: Generated to visualize the most common words used in the comments.
  - **Bar Chart**: Created to display the distribution of likes and reply counts.
  - **Scatter Plot**: Plotted to show the relationship between various features.
  - **Network Diagram**: Developed to explore connections between users or comments.
  - **Tree Diagram**: Constructed to represent hierarchical relationships.
  - **Violin Plot & Boxplot**: Used to visualize the distribution of data across different features.
  - **Correlation Matrix**: Analyzed to identify relationships between different variables.

## Machine Learning Models

### 1. **Linear Regression**
   - **Metrics Evaluated**:
     - Mean Squared Error (MSE)
     - Mean Absolute Error (MAE)
     - R-squared
   - **Training & Testing**: Assessed model performance on both training and testing sets.
   - **Confusion Matrix**: Created to evaluate classification performance.

### 2. **K-Nearest Neighbors (KNN)**
   - **Accuracy**: Measured to evaluate model performance.
   - **Classification Report**: Generated to assess precision, recall, and F1-score.
   - **Overfitting/Underfitting Check**: Analyzed using testing and training data.
   - **Confusion Matrix**: Created for classification evaluation.

### 3. **Decision Tree**
   - **Accuracy**: Evaluated to compare with other models.
   - **Classification Report**: Generated for detailed performance analysis.
   - **Confusion Matrix**: Created for performance evaluation.
   - **Overfitting/Underfitting Check**: Analyzed using testing and training data.

### 4. **Support Vector Classifier (SVC)**
   - **Accuracy & Classification Report**: Generated to evaluate performance.
   - **Classification Report**: Generated for detailed performance analysis.
   - **Confusion Matrix**: Created for performance evaluation.
   - **Overfitting/Underfitting Check**: Analyzed using testing and training data.

### 5. **Gaussian Naive Bayes (GaussianNB)**
   - **Accuracy & Classification Report**: Generated for performance evaluation.
   - **Classification Report**: Generated for detailed performance analysis.
   - **Confusion Matrix**: Created for evaluation.
   - **Overfitting/Underfitting Check**: Analyzed using testing and training data.

## Results

- **Model Selection**: Linear Regression provided the best accuracy among the models tested.
- **Predictions**: Used selected models to predict outcomes on new data samples.

## Conclusion

This project successfully analyzed public sentiment on the Putin-Carlson interview, providing insights through both exploratory analysis and predictive modeling. Linear Regression emerged as the most effective model, offering the highest accuracy in sentiment prediction.

## Future Work

- Explore additional feature engineering techniques to enhance model performance.
- Experiment with advanced machine learning models such as ensemble methods.
- Extend the analysis to include temporal changes in sentiment over time.

## Repository Structure

```plaintext
├── data/
│   ├── raw/                 # Raw data files
│   ├── processed/           # Processed data files
├── notebooks/               # Jupyter notebooks for analysis
├── src/                     # Source code for data processing and modeling
├── reports/                 # Generated analysis and model performance reports
└── README.md                # Project overview and instructions
