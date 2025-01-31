# EnergiX : Energy Consumption Model

This model predicts energy consumption using a dataset that includes factors such as site name, department, electric utility, building type, address, year, current solar usage, peak electric demand, building area, natural gas usage, latitude, longitude, and electricity usage.

**Steps Involved:**
1. **Data Preprocessing:**
   - Imported necessary libraries: pandas, matplotlib, numpy.
   - Loaded the dataset and selected relevant columns.
   - Handled missing values by dropping rows with null values.
   - Split the data into features (X) and target variable (y).

2. **Encoding:**
   - Applied label encoding to transform categorical features into numerical values for better model performance.

3. **Splitting the Data:**
   - Split the dataset into training and test sets using an 80-20 split.

4. **Training the Model:**
   - Used a Random Forest Regressor with 1007 estimators and a random state of 17.
   - Trained the model on the training data.

5. **Model Evaluation:**
   - Predicted the energy consumption on the test set.
   - Calculated the R² score, achieving an accuracy of approximately 77.92%.

The model demonstrates a strong understanding of the relationship between various factors and energy consumption, providing valuable insights for energy management and optimization.
