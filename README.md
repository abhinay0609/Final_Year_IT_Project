**# Final_Year_IT_Project**
AI for Sustainability — Greenhouse Gas Emission Prediction using Sustainable ML Practices

**🌱 AI for Sustainability — Exploring Sustainable Predictive Models for Greenhouse Gas Emission Prediction**

**📌 Project Overview**

Artificial Intelligence is widely used to fight climate change, especially through Machine Learning (ML)–based emission prediction. However, ML models themselves consume energy during development and deployment, which contributes to CO₂ emissions.

This project addresses both sides of the climate equation:

**Using ML for sustainability** → Predicting Greenhouse Gas (GHG) emissions from industrial data

**Making ML sustainable** → Measuring energy consumption and carbon footprint of each ML model

**🎯 Problem Statement**

GHG emissions are a major driver of global warming, and predictive analytics can help industries plan better sustainability decisions.
But every ML model consumes electricity during computation, indirectly contributing to CO₂ emissions — a major research gap identified in sustainable AI.

- 🔹 Most projects focus only on prediction accuracy
- 🔹 Very few analyse how much carbon the ML model itself emits

**🌍 Project Objective**

**Primary Goal**
- Predict greenhouse gas emissions using ML	

**Secondary Goal**
- Evaluate which ML model is most energy-efficient and eco-friendly

**🛠️ Proposed Solution**

 - We trained multiple machine learning models on a GHG dataset and then:
 - Evaluated R² Score & RMSE (Prediction performance)
 - Measured energy consumption & CO₂ emissions using CodeCarbon
 - Compared all models to identify the most sustainable model for deployment

**📌 Sustainability Trade-off Studied:**

Which model gives the best balance between accuracy and environmental impact?

**🧰 Tech Stack**

| Category                  | Tools Used                  |
| ------------------------- | --------------------------- |
| Language                  | Python                      |
| ML Libraries              | Pandas, NumPy, Scikit-Learn |
| Sustainability Monitoring | CodeCarbon                  |
| Deployment                | Streamlit                   |
| Development               | Jupyter / Google Colab      |


**🔬 Methodology (Steps Followed)**

 - Dataset selection & preprocessing
 - Feature engineering and correlation analysis
 - Model training - Linear Regression - Random Forest - Hyperparameter-tuned Random Forest (GridSearchCV)
 - Evaluation using performance metrics - R² Score - RMSE
 - Sustainability evaluation using CodeCarbon
 - Energy consumed during training
 - CO₂ emissions generated
 - Model comparison and selection of most sustainable model
 - Deployment using Streamlit to provide real-time predictions

**📊 Results Summary**

| Model                              | R² Score | RMSE   | CO₂ Emissions (kg) | Sustainability Verdict               |
| ---------------------------------- | -------- | ------ | ------------------ | ------------------------------------ |
| Linear Regression                  | High     | Low    | **7.00 × 10⁻⁸**    | ⭐ Most Sustainable (best trade-off)  |
| Random Forest                      | Higher   | Lower  | **5.22 × 10⁻⁶**    | ⚠️ Good accuracy but high emissions  |
| Tuned Random Forest (GridSearchCV) | Highest  | Lowest | **0.0001686**      | ❌ Accuracy ↑ but carbon footprint ↑↑ |


**🔎 Conclusion:**

 - Linear Regression gives the best balance of accuracy + energy efficiency, and is chosen for deployment.

**📌 Research Contribution**

 - This project partially fulfils the research gap highlighted in “AI and Climate Protection: Research Gaps and Needs to Align Machine Learning with Greenhouse Gas Reductions (2024)” by:

 - ✔ Predicting GHG emissions using ML
 - ✔ Measuring energy usage & carbon footprint during model training

**🔮 Future Scope**

This project can be enhanced further through:

- Optimization techniques to reduce training emissions
- Use of green computing resources and energy-aware scheduling
- Edge deployment to reduce cloud footprint
- Monitoring emissions during inference as well as training
- Extending to Deep Learning & LLM sustainability
