# Employee Attrition Prediction Using Machine Learning

## Overview
Predicts employee attrition using Logistic Regression, Decision Tree, and Random Forest models on IBM HR Analytics dataset. **Logistic Regression achieved 86.62% accuracy with 24.59% recall - best for identifying at-risk employees.**

## Dataset
- 1,470 employee records
- 35 features (demographics, job factors, satisfaction scores)
- 16% attrition rate (imbalanced classification problem)
- Source: IBM HR Analytics (Kaggle)

## Key Findings
1. **Overtime** - #1 attrition driver (2.4x higher risk)
2. **Monthly Income** - Lower income = higher turnover
3. **Age** - Younger employees leave more (avg 33.6 vs 37.6 yrs)
4. **Job Satisfaction** - Poor satisfaction predicts attrition
5. **Years at Company** - Fewer years = higher risk

## Models Trained & Results

| Model | Accuracy | Recall | F1-Score | Best For |
|-------|----------|--------|----------|----------|
| Logistic Regression | 86.62% | 24.59% | 33.71% | **✅ BEST - Catches most at-risk** |
| Decision Tree | 84.81% | 21.31% | 27.96% | Interpretability |
| Random Forest | 86.39% | 9.84% | 16.67% | Feature importance |

**Why Logistic Regression?**
- Highest Recall: catches 24.59% of employees who leave
- Highest F1-Score: best balance for imbalanced data
- Better for HR: identifies employees likely to leave

## Technologies
- Python 3.10
- pandas, numpy, scikit-learn, matplotlib, seaborn
- Logistic Regression, Decision Tree, Random Forest

## Files
- `Employee_Attrition_Analysis.ipynb` - Complete analysis
- `data/cleaned_employee_attrition.csv` - Processed dataset
- `figures/` - 7 visualization charts
- `results/` - Performance metrics CSVs

## Business Impact
- Identifies 24.59% of at-risk employees
- Enables proactive retention strategies
- Potential savings: ₹32-50 lakh annually (5% attrition reduction)

## How to Use
1. Clone repository
2. Open `Employee_Attrition_Analysis.ipynb` in Jupyter
3. Run all cells to see analysis and models
4. View charts in `figures/` folder
5. Check metrics in `results/` folder

## Author
[Your Name]
LinkedIn: [Your LinkedIn]

