# UserInsights
# 📊 Customer Segmentation for Amazon E-commerce Behaviour

## Project Overview
This project applies dimensionality reduction and clustering techniques to segment Amazon customers based on purchasing behaviours and satisfaction levels.  
The goal is to generate actionable insights for targeted marketing, personalisation strategies, and customer retention.

---

## 🛠️ Tools & Techniques
- Python (pandas, numpy, matplotlib, scikit-learn)
- StandardScaler for feature scaling
- Principal Component Analysis (PCA) for dimensionality reduction
- K-Means Clustering for customer segmentation
- Elbow Method and Silhouette Score for cluster validation

---

## 🚀 Workflow
1. **Data Cleaning**:  
   - Dropped non-numeric and datetime columns.
   - Handled invalid or missing values.

2. **Preprocessing**:  
   - Standardised features to ensure unbiased clustering.

3. **Dimensionality Reduction**:  
   - Applied PCA to reduce feature space to 2 components while retaining maximum variance.

4. **Clustering**:  
   - Used K-Means to segment customers.
   - Determined optimal `k` using both Elbow and Silhouette methods.

5. **Cluster Analysis**:  
   - Generated three customer personas based on engagement and satisfaction metrics.
   - Provided targeted business recommendations for each cluster.

---

## 📈 Key Results
- Identified **three customer segments**:
  - **Cluster 0**: Low-engagement, younger customers (age ~27).
  - **Cluster 1**: Moderately engaged, older demographic (age ~44).
  - **Cluster 2**: Highly engaged, highly satisfied younger shoppers (age ~27).
  
- Suggested marketing strategies tailored to each persona.

---


---

## 📋 Business Impact
- Provides a framework for targeted customer engagement strategies.
- Improves marketing ROI by tailoring offers to each segment.
- Forms the basis for building predictive models for customer lifetime value.

---

## 🛤️ Future Improvements
- Explore alternative clustering algorithms (DBSCAN, Hierarchical).
- Incorporate additional customer behaviour features (e.g., spend categories, purchase frequency).
- Build automated pipelines for real-time customer segmentation.

---

