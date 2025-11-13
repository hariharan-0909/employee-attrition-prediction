# Employee Attrition Prediction Using Machine Learning
## Overview
This project predicts employee attrition using machine learning models trained on 1,470 e
## Problem Statement
Employee turnover costs organizations significantly:
- Each departure costs 50-200% of annual salary
- Loss of experience and productivity
- Team morale impact
- With 16% attrition rate, impact is substantial
## Solution
Developed machine learning models to:
- Predict which employees are at risk of leaving
- Identify key attrition drivers
- Enable proactive HR interventions
- Estimate potential cost savings
## Dataset
- **Source:** IBM HR Analytics Employee Attrition Dataset (Kaggle)
- **Size:** 1,470 employees, 35 features
- **Attrition Rate:** 16.1% (237 employees left)
- **Data Balance:** Imbalanced classification problem
## Models Developed
| Model | Accuracy | Recall | F1-Score | Best For |
|-------|----------|--------|----------|----------|
| Logistic Regression | 86.62% | 24.59% | 33.71% | ✅ **Best Overall** |
| Decision Tree | 84.81% | 21.31% | 27.96% | Interpretability |
| Random Forest | 86.39% | 9.84% | 16.67% | Feature Importance |
## Key Findings
### Top 5 Attrition Drivers:
1. **Overtime** - Employees with overtime have 3x higher attrition risk
2. **Monthly Income** - Lower salary = 47% higher attrition rate
3. **Age** - Younger employees (avg 33 yrs) leave more than older (avg 37 yrs)
4. **Total Working Years** - Experience reduces attrition
5. **Job Satisfaction** - Strong predictor of retention
### Business Impact:
- Potential cost savings: ₹32-50 Lakh annually (5% attrition reduction)
- Identifies 24.59% of actual leavers for proactive intervention
- Actionable insights for HR strategy
## Technical Stack
- **Language:** Python 3.10
- **Libraries:** pandas, scikit-learn, matplotlib, seaborn
- **Models:** Logistic Regression, Decision Tree, Random Forest
- **Evaluation:** Accuracy, Precision, Recall, F1-Score, Confusion Matrix
## Files
- `Employee_Attrition_Analysis.ipynb` - Complete analysis notebook
- `data/` - Dataset and processed data
- `figures/` - Visualization charts (7 high-quality PNG files)
- `results/` - Model performance reports
## Key Visualizations
- Attrition distribution (bar + pie chart)
- Age vs attrition patterns
- Income distribution by attrition status
- Overtime impact analysis
- Feature importance ranking
- Model confusion matrices
- Correlation analysis
## How to Use
1. Clone repository
2. Open `Employee_Attrition_Analysis.ipynb`
3. Run all cells (dependencies managed automatically)
4. View results, charts, and insights
## Insights for HR Teams
- **Immediate Actions:** Review overtime policies and salary competitiveness
- **Retention Strategy:** Focus on job satisfaction and career development
- **Early Warning:** Use model to identify at-risk employees monthly
- **Prevention:** Implement targeted retention programs
## Future Improvements
- Implement SMOTE for better handling of imbalanced data
- Add deployment pipeline (REST API)
- Create real-time prediction dashboard
- Incorporate additional HR metrics (performance ratings, engagement surveys)
- ## Author
- Hariharan 
- GitHub:https://github.com/hariharan-0909
- LinkedIn:www.linkedin.com/in/hariharan0909
## License
This project is open source and available under the MIT License.

