### Project Development for the Hackathon

#### Exploratory Data Analysis Notebook (EDA):

1. **Data Cleaning:**
   - Initiated the project with thorough data cleaning to optimize models.

2. **One-Hot Encoding:**
   - Applied one-hot encoding to all categorical columns to preserve crucial information for the model.

3. **Data Aggregation:**
   - Combined numerical and one-hot encoded data into a single DataFrame for collaborative work.

4. **Quick Imputation:**
   - Utilized SimpleImputer for quick imputation using the mean.

5. **Data Standardization:**
   - Passed through a StandardScaler to optimize numbers for models benefiting from it.

6. **Principal Component Analysis (PCA):**
   - Applied PCA with 10 components to reduce dimensionality while retaining essential variability.

7. **Feature Selection:**
   - Applied a variance threshold to eliminate features with low variability.

8. **Correlation Analysis:**
   - Rapid correlation analysis with the target, seeking potential features with moderate relationships.

9. **Object Saving:**
   - Storage of important objects such as the feature list, PCA results, and training data.

#### Modeling Notebook (Stack):

1. **Data Loading:**
   - Loaded previously cleaned training data from the EDA notebook and separated it for training and testing.

2. **Hyperparameter Optimization:**
   - Implemented individual models with optimized hyperparameters using RandomizedSearchCV.

3. **Stacked Ensemble Model:**
   - Ensemble of different models to compensate for strengths and weaknesses, using the Stacking method with a final Linear Regression estimator.

4. **Model Evaluation:**
   - Recorded best hyperparameters and training/test results for each individual model and the ensemble model.

5. **Model Comparison:**
   - Visualization and comparison of results between each model to assess their relative performance.

6. **Model Saving:**
   - Storage of models used for predicting checkpoints.

#### Testing Notebook:

1. **Dataset Selection for Prediction:**
   - Inclusion of code lines to select the dataset to predict.

2. **Data Cleaning for Prediction:**
   - Incorporation of code for data cleaning, including the addition of necessary columns for the model.

3. **Application of Pretrained Model:**
   - Use of the previously applied Scaler and PCA to training data and application of pretrained models for predictions.

4. **Result Saving:**
   - Storage of results in a parquet file for further analysis.

This structured approach ensures efficient data cleaning, in-depth exploration, and the implementation of a robust ensemble model for the hackathon. Additionally, the ability to predict new datasets demonstrates the versatility and applicability of the developed solution.