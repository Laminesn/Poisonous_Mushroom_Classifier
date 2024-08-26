### **Mushroom Classification**

1. **Data Preprocessing and Initial Classification**
   - **Dataset Preparation:**
     - Loaded the mushroom dataset and performed initial preprocessing, including handling categorical features.
     - Applied one-hot encoding to convert categorical variables into a format suitable for model training.
     - Split the dataset into training and testing sets, ensuring an unbiased evaluation.
   - **Decision Tree Classifier:**
     - Trained a Decision Tree classifier on the processed data to predict whether mushrooms are poisonous or edible.
     - Evaluated the model's accuracy on the test set and visualized the results using a confusion matrix.
   - **Results:**
     - Achieved 100% accuracy in classifying poisonous mushrooms, indicating the model's effectiveness in this context.
   
2. **Advanced Model Tuning and Feature Importance**
   - **XGBoost Classifier Training and Tuning:**
     - Chose XGBoost for its robustness in handling structured data and tuned hyperparameters using GridSearchCV.
     - Evaluated the model's performance on the test set and compared it with the Random Forest classifier.
     - Visualized feature importances using permutation importance, identifying key predictors like odor and color.
   - **Cost-Complexity Pruning and Final Model Evaluation:**
     - Applied cost-complexity pruning to the Decision Tree to simplify the model without losing predictive power.
     - Plotted the pruned decision tree and discussed the intuitive aspects of its structure.
     - Compared post-pruning accuracy with the initial model to validate the pruning approach.
   - **Results:**
     - XGBoost achieved high accuracy but was slightly outperformed by Random Forest, which handled the high-dimensional data effectively.
     - Key features like odor and color were consistently identified as critical in determining mushroom edibility, validating their importance across different models.
