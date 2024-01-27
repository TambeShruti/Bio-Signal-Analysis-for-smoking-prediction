# Bio-Signal-Analysis-for-smoking-prediction

This project focuses on predicting an individual's smoking status using biometric features through bio signal analysis. Leveraging Python and Google Colab, we employ machine learning techniques, data visualization, and extensive exploratory data analysis (EDA) to uncover insights and build an accurate prediction model.

## Key Components
- **Programming Language:** Python
- **Platform:** Google Colab
- **Libraries:** Scikit-Learn, matplotlib, seaborn, Pandas, NumPy
- **Methods:** Grid Search, Hyperparameter Tuning, Feature Engineering, Data Visualization (EDA)

## Dataset
- **Size:** 55k rows, 26 features
- **Biometric Features:** Includes age, gender, weight, height, hemoglobin levels, etc.
- **EDA Insights:**
  - Smokers have significantly elevated hemoglobin levels.
  - Smoking is more prevalent among younger individuals.
  - The male population has a higher representation among smokers compared to females.

## Methodology
### Feature Engineering
- Encoding categorical features
- Creating new features
- Feature Importance Analysis
- Scaling the dataset

### Model Selection and Development
1. **Baseline Models:** Logistic Regression, SVM, Random Forest Classifier
2. **Grid Search and Cross Validation:** Models fitted with these techniques
3. **Random Forest Classifier (RFC):** Initially achieved an accuracy rate of 83%
4. **Hyperparameter Tuning:** Increased RFC accuracy to 84% over the baseline model

## Conclusion
- **Accuracy:** Achieved 84% accuracy in predicting an individual's smoking status based on bio signals.
- **Future Work:** Proposed future work involves tracking changes in smoking behaviors and health indicators over time.

Feel free to explore the code and adapt the methodology for similar analyses or further improvements. Your feedback is appreciated!
