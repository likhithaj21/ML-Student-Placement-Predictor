## Machine Learning Approach

This project treats placement prediction as a **Binary Classification Problem**.

- 0 → Not Placed  
- 1 → Placed  

The following machine learning models were used:

- Logistic Regression  
- Random Forest  
- Gradient Boosting  

Model performance was evaluated using:

- F1 Score  
- Accuracy  
- ROC-AUC Score  
- Confusion Matrix  

Random Forest typically performed the best due to its ability to capture complex relationships between features.

---

## Key Insights

Feature importance analysis revealed that the most influential factors affecting placement are:

- Programming skills  
- Aptitude score  
- Degree CGPA  
- Internship experience  
- Project experience  

Earlier academic scores such as **10th and 12th marks** have comparatively lower impact.

---

## Placement Readiness Plan

The model uses placement probability scores instead of only binary predictions to assess student readiness.

Students are categorized into four zones based on placement probability:

- 🟢 **Green (>90%)** – Ready for placement interviews  
- 🟡 **Yellow (70–90%)** – Minor improvements needed  
- 🟠 **Orange (40–70%)** – Technical and aptitude training required  
- 🔴 **Red (<40%)** – Intensive preparation required  

### Improvement Suggestions

- Improve programming skills  
- Practice aptitude problems  
- Develop communication skills  
- Gain internship experience  
- Build more practical projects  

---

## Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Seaborn  
- Matplotlib  

---

## Conclusion

This project demonstrates how machine learning can be used to predict student placement outcomes and identify key factors influencing employability. By analyzing academic performance and skill-based attributes, institutions can provide targeted training and improve overall placement success rates.
