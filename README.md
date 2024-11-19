# IEEE-CIS Risk Stratification

This project focuses on utilizing the IEEE-CIS dataset to explore consequence modeling by predicting fraudulent transactions and analyzing their impact. The dataset provides rich transaction and identity data, making it ideal for advanced data science workflows, including machine learning modeling, strike-rate analysis, and consequence evaluation.

---

## Progress So Far

### Dataset Overview:
The project utilizes the IEEE-CIS dataset, which includes:
- **Transaction Data**: Features such as product codes, transaction amounts, and payment card details.
- **Identity Data**: Additional attributes like device type, device info, and anonymized IDs.

### Completed Steps:
1. **Data Cleaning & Merging**:
   - Combined transaction and identity datasets using `TransactionID`.
   - Addressed missing values using strategies like categorical imputation and numerical replacements.

2. **Memory Optimization**:
   - Reduced memory usage by 60% through data type downcasting and category conversions.

3. **Feature Engineering**:
   - Created aggregated features for cards, email domains, and addresses.
   - Extracted time-based features (e.g., transaction hour, day, day-of-week) for temporal analysis.

4. **Dimensionality Reduction**:
   - Applied techniques to reduce feature space while retaining critical information.
   - Focused on removing highly correlated or low-variance features to enhance computational efficiency and model performance.

5. **Exploratory Analysis**:
   - Assessed fraud distribution and identified class imbalance (27:1 non-fraud to fraud ratio).
   - Visualized key trends, including transaction amounts and device-specific activity.

6. **Environment Setup**:
   - Developed a `requirements.txt` file for pip installation to replicate the environment easily.


### Challenges Faced:
- High dimensionality and missing data required significant effort to preprocess.
- Achieving balance between performance and memory optimization was iterative and took 4 attempts over 6 days.

---

### Next Steps:
- **Machine Learning Models**: Develop classifiers to predict fraud and assess model accuracy.
- **Strike-Rate Analysis**: Evaluate real-world applicability of the predictions.
- **Consequence Modeling**: Quantify the financial impact of fraud using predictive insights.

Explore the `requirements.txt` file for easy environment setup and dive into the notebook for a closer look!
