A detailed exploratory data analysis (EDA) of insurance claims data, inspired by Sergey Litvinenko’s Kaggle dataset.

Overview
This project explores a rich insurance claims dataset to understand patterns in claim denials and approvals. The primary focus is exploratory data analysis, highlighting trends across vehicle and customer features that influence claim outcomes.

Data Source
Dataset: Decoding Insurance Claims Dynamics with Data

Author: Sergey Litvinenko (Kaggle)

License/Usage: The dataset is publicly available on Kaggle and remains under the terms specified by the original author.

Project Structure
text
insurance-claims-analysis/
├── data/
│   └── cleaned_claims_data.csv
├── notebooks/
│   └── insurance_claims_analysis.ipynb
├── images/
├── README.md
├── requirements.txt
└── LICENSE
Methods & Highlights
Data Cleaning: Checked for and confirmed no missing or duplicate values; standardized all feature naming.

Target Distribution: 93.5% approved vs 6.5% denied claims (significant class imbalance).

Feature Exploration: Analysis by segment, fuel_type, vehicle_age, and customer_age to identify risk factors for denials.

Visualization: Created bar plots, boxplots, and crosstabs to visualize major patterns in the data.

Insights: Summarized findings with actionable implications for risk analysis and next steps.

Key Insights
Imbalanced Outcomes: Only 6.5% of claims were denied—important to consider for modeling.

Higher Denials in Segment 'B2' and Petrol Vehicles: Certain vehicle segments and fuel types face higher denial rates.

Vehicle & Customer Age: Older vehicles and higher customer age groups are more likely to be denied.

Correlations: No single numeric feature strongly predicts denial; more advanced modeling will be beneficial.

Next Steps: Apply feature engineering, predictive modeling, and deeper subgroup analysis (by provider, region, policy, etc.).

How to Reproduce
Clone the repository.

Download the dataset from Kaggle and place it in the data/ folder.

Run the notebook notebooks/insurance_claims_analysis.ipynb in Jupyter or Google Colab.

Author
Analysis by Navya Kilaru

Credit: Original dataset by Sergey Litvinenko on Kaggle.
