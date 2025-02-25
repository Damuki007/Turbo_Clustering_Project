# Borrower Segmentation and Credit Risk Profiling Using Clustering Techniques



## Overview

This project leverages unsupervised clustering methods to segment borrowers based on their loan repayment behavior and overall credit profile. By grouping clients into distinct segments, the analysis uncovers inherent patterns in repayment performance, identifies key characteristics of each borrower class, and determines the most influential features driving creditworthiness. The insights derived from this analysis enable targeted risk management, tailored lending strategies, and enhanced decision-making for credit portfolio management.



## Objectives

- **Client Segmentation:** Group borrowers based on historical repayment data to reveal distinct risk profiles.

- **Segment Characterization:** Profile each cluster by identifying key financial and behavioral attributes.

- **Feature Importance Analysis:** Determine the critical variables (e.g., loan age, days interest calculated, revenue per loan) that drive borrower segmentation using techniques like PCA.

- **Actionable Insights:** Provide recommendations for mitigating credit risk and optimizing loan recovery strategies.



## Methodology

- **Data Wrangling and Preparation:** Cleaning and preprocessing the dataset to ensure data integrity and consistency.

- **Feature Engineering:** Creating new columns to capture temporal trends, repayment behavior, and risk profiles.

- **Clustering Analysis:** Utilizing K-Means clustering (with optimal cluster selection via the Elbow method) to segment borrowers.

- **Visualization:** Applying PCA for dimensionality reduction as well as using Random Forest for feature importance visualization.

- **Interpretation:** Profiling each borrower segment and deriving actionable insights to inform risk management strategies.



## Results & Insights

### Clustering Results

The clustering analysis identified four distinct borrower segments:

- **Cluster 0 (Low-Risk Borrowers):** Timely repayments, low outstanding fees, and high revenue per loan.

- **Cluster 1 (High-Risk Defaulters):** Prolonged non-repayment, high outstanding fees, and substantial loan balances.

- **Cluster 2 (Moderate-Risk Borrowers):** Partial repayments with moderate outstanding balances.

- **Cluster 3 (Extreme Defaulters):** Severe non-repayment with extremely high outstanding amounts.


### Feature Importance

Key features driving the segmentation include but are not limited to; loan age, days interest calculated, and revenue per loan, as revealed through Random Forest & PCA analysis.



## Repository Structure

├── data viz/ - Folder containing visualizations generated from the jupyter notebook

├── data/ - Folder containing the dataset required to run the jupyter notebook

  ├── Clustering_Notebook_pdf.pdf - PDF version of the jupyter notebook

  ├── README.md - Readme file for this repository

  ├── Turbo_Aug_23_24_Clustering.ipynb - Jupyter notebook containing detailed analysis and results

  ├── Turbo_Clustering_Presentation.pptx/ - Powerpoint presentation summarizing result findings

  ├── requirements.txt - List of required Python packages



## Author Contact Info:
For further information or questions regarding this project, please contact:

David Kirianja [Author]
dmkirianja@gmail.com
www.linkedin.com/in/david-mutugi-dmk007n

