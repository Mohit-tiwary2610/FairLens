# FairLens: Bias & Fairness Detection in Machine Learning

FairLens is a project that demonstrates how to detect and mitigate bias in machine learning models using the **Adult Income dataset**.  
It highlights fairness metrics such as **Demographic Parity Difference** and **Equalized Odds Difference**, visualizes selection rates across sensitive groups (sex and race), and includes model explainability via **SHAP** to show which features influence predictions.

---

## 🚀 Project Overview
- **Dataset**: Adult Income dataset (fetched directly from OpenML).
- **Baseline Model**: Logistic Regression.
- **Fairness Metrics**: Accuracy, Demographic Parity Difference (DP), Equalized Odds Difference (EO).
- **Mitigation Technique**: Exponentiated Gradient with Demographic Parity constraint.
- **Outputs**: Visual plots comparing baseline vs mitigated models and SHAP explainability.

---

## 📊 Results

### 1. Baseline vs Mitigated Metrics
Compares accuracy, DP difference, and EO difference before and after mitigation.

![Baseline vs Mitigated Metrics](results/baseline_vs_mitigated_metrics.png)

---

### 2. Selection Rate by Sex
Shows how often male vs female groups are predicted as positive (income > 50K).  
Mitigation reduces disparity between groups.

![Selection Rate by Sex](results/fairness_sex.png)

---

### 3. Selection Rate by Race
Shows selection rates across racial groups.  
Mitigation improves fairness across multiple sensitive categories.

![Selection Rate by Race](results/fairness_race.png)


---

### 4. SHAP Summary Plot (Model Explainability)
Reveals which features most influence the model’s predictions and how their values affect outcomes.

![SHAP Summary Plot](results/shap_summary.png)

---

## ✅ Key Takeaways
- **Baseline model** had noticeable disparities in predictions across sex and race.  
- **Mitigation** reduced both **Demographic Parity Difference** and **Equalized Odds Difference**, while maintaining similar accuracy.  
- **Transparency**: SHAP summary provides feature-level explainability to complement fairness metrics.  

---

## 📂 Project Structure

---

## ⚖️ Responsible AI
This project emphasizes **responsible AI practices**:
- Measuring fairness across sensitive groups.
- Applying mitigation techniques to reduce bias.
- Documenting trade‑offs between fairness and accuracy.
- Providing transparency with SHAP explainability.

---

## 👤 Author
**Mohit Tiwary**  
B.Tech in Computer Science & Engineering, Sikkim Manipal Institute of Technology  
Passionate about fairness, responsible AI, and recruiter‑ready data science projects.
