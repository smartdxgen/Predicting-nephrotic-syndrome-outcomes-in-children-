# Predicting-nephrotic-syndrome-outcomes-in-children
# Cite this article
Mohebbi, H., Dehghani, T., Kheirdoust, A. et al. Predicting nephrotic syndrome outcomes in children using machine learning: insights from a cross-sectional study. BMC Nephrol 27, 26 (2026). https://doi.org/10.1186/s12882-025-04631-0

# Predicting nephrotic syndrome outcomes in children using machine learning: insights from a cross-sectional study
Abstract
Introduction
Nephrotic Syndrome (NS) is a kidney condition commonly seen in children, characterized by symptoms such as protein in the urine, low blood protein levels, and swelling. If not appropriately treated, NS can result in serious complications, including infections and kidney damage. Differentiating between steroid-sensitive and steroid-resistant NS is essential for guiding treatment. Traditionally, kidney biopsies are used for diagnosis; however, they are invasive and carry some risk. This study examines the promising potential of utilizing machine learning (ML) models to predict NS subtypes, treatment responses, and biopsy outcomes, to reduce reliance on biopsies and enhance the field of pediatric nephrology.

Methods
This retrospective study analyzed 243 pediatric patients across three hospitals in Iran in 2022. Patient records provided clinical and laboratory features data, including age, sex, comorbidities, family history, and lab results. Twelve clinical features were used to train ML models, including Random Forest (RF), Gradient Boosting Classifier (GBC), and Extra Trees (ET).

Results
The RF and GBC models achieved an impressive 90% accuracy in predicting whether NS was steroid-sensitive or steroid-resistant, providing a high confidence level. The RF model slightly outperformed the GBC, with an F1-score of 0.89 and an AUC-ROC of 0.936, demonstrating solid predictive power. RF and ET models also demonstrated high accuracy (80%) and AUC values (0.94–0.95) in predicting treatment responses, such as steroid resistance or frequent relapses. While the RF model performed well in predicting biopsy results, including Focal Segmental Glomerulosclerosis (FSGS) and Minimal Change Disease (MCD), with an AUC-ROC of 0.626, it encountered challenges due to imbalanced data. However, the RF model demonstrated superior precision and recall over the ET model.

Conclusion
ML models, particularly Random Forest, show significant promise in predicting NS subtypes, treatment outcomes, and biopsy results, potentially reducing the need for invasive kidney biopsies. These models can assist clinicians in making more informed treatment decisions. Important predictive factors identified included hemoglobin levels, complement factors, and patient age, emphasizing the benefit of integrating clinical and laboratory data into ML-based diagnostic tools.

Lay Summary
Nephrotic Syndrome (NS) is a kidney disease primarily affecting children, characterized by symptoms such as swelling and protein in the urine. In 2022, we conducted a study at three hospitals in Iran to find better ways to diagnose NS without using invasive kidney biopsies. We utilized advanced machine learning (ML) techniques to analyze patient records and developed models that accurately predicted whether NS was steroid-sensitive or resistant, achieving an accuracy rate of over 90%. We discovered that important factors, such as hemoglobin levels and patient age, play a crucial role in these predictions. Our research is significant because it shows how machine learning can improve diagnosis and treatment in pediatric nephrology. This could lead to fewer invasive procedures and better outcomes for young patients.
