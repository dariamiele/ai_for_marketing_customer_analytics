AI for Marketing — Customer Analytics & Predictive Modeling
University project | AI for Communication and Marketing | BSc in Artificial Intelligence | 2025/2026

This project explores how customer data and machine learning can support marketing decisions. It brings together three analyses: customer segmentation, churn prediction, and customer lifetime value (CLTV) estimation. Each part includes a Jupyter notebook documenting the analysis and a short presentation translating the findings into proposed marketing actions.


Part 1 — Customer Segmentation & Communication Strategy
Analyzed a retail marketing dataset, including customer demographics, spending, campaign response, and purchasing channels. After auditing and preparing the data, I used RFM segmentation and K-Means clustering to identify customer groups and compare their behavior.
The presentation summarizes three K-Means customer archetypes and proposes differentiated communication approaches for loyal, at-risk, and less responsive customers.
Files: customer-segmentation/customer_segmentation.ipynb and customer-segmentation/presentation.pdf

Part 2 — Customer Churn Prediction & Retention Strategy
Built and evaluated churn classification models using Logistic Regression and Random Forest, with attention to class imbalance and recall. Explored factors associated with churn, including customer tenure and complaints, and examined feature importance and lift.
The presentation proposes a “First 180 Days” retention program focused on customers early in their lifecycle. The tuned Random Forest result reported in the presentation is 0.874 recall on the evaluated dataset; it is an experimental result, not evidence of campaign effectiveness.
Files: churn-prediction/churn_prediction.ipynb and churn-prediction/presentation.pdf

Part 3 — Customer Lifetime Value & Marketing Strategy
Analyzed the Olist e-commerce dataset to estimate future value within the existing customer base. Compared probabilistic BG/NBD + Gamma-Gamma modeling with XGBoost and Random Forest regression, and examined model evaluation, repeat-purchase patterns, and customer ranking.
The presentation proposes CLTV-based retention and win-back segments. An important interpretation caveat is that revenue from newly acquired customers in the holdout period is outside the prediction scope of models built for the existing customer base; total marketplace revenue is therefore not a like-for-like target for those predictions.
Files: customer-lifetime-value/customer_lifetime_value.ipynb and customer-lifetime-value/presentation.pdf


Tools and techniques
- Python: pandas, NumPy, scikit-learn, Matplotlib and related analysis libraries
- Segmentation: RFM, K-Means, exploratory data analysis
- Prediction: Logistic Regression, Random Forest, XGBoost
- CLTV: lifetimes (BG/NBD and Gamma-Gamma)
- Communication: visual analysis, presentation of findings, and marketing recommendations


Data and reproducibility
The notebooks reference source data files that are not included in the submitted project archive. Their existing data paths may need to be adjusted before running the notebooks in a new environment. See each notebook's data-loading section for the expected filenames and input structure. The Olist analysis uses the publicly known Olist e-commerce dataset; the other datasets should be checked for redistribution rights and accurate attribution before being uploaded.
The PDF presentations summarize the results of the analyses as submitted for the university lab exam. The recommended marketing actions are proposals based on the analyses, not deployed or A/B-tested campaigns.
The PDF presentations summarize the results of the analyses as submitted for the university lab exam. The recommended marketing actions are proposals based on the analyses, not deployed or A/B-tested campaigns.
Context
Academic lab examination for AI for Communication and Marketing, Bachelor's degree in Artificial Intelligence (academic year 2025/2026).
