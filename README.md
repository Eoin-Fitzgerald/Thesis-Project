# Thesis-Project
# AI in the International Political Economy  
## A Machine Learning Approach to FDI Risk Analysis

### Summary
This capstone project explores how machine learning can support Foreign Direct Investment (FDI) decisions by analyzing economic data to assess investment risk. Focusing on EU countries, I developed an initial **Stability Index** combining GDP growth and volatility, enabling classification into **low**, **medium**, and **high-risk** categories. This data-driven approach aims to improve the accuracy and strategic value of investment risk assessments.

---

### Objectives
- Gather and prepare reliable economic data on EU member states.
- Engineer features like volatility and a Stability Index.
- Use decision trees and clustering to classify countries by investment risk.
- Offer actionable recommendations for FDI strategies.

---

### Problem Statement
FDI plays a crucial role in global economic development, but geopolitical and economic volatility makes investment decisions increasingly complex. Traditional methods often fail to fully account for historical patterns and macroeconomic stability. This project proposes a machine learning-based solution that enables a clearer assessment of long-term investment risk.
---

### Methodology

This project follows the **CRISP-DM** (Cross-Industry Standard Process for Data Mining) methodology:

1. **Business Understanding**  
   - Define economic stability as a key factor for FDI.
   - Develop a classification framework based on economic resilience.

2. **Data Understanding**  
   - Historical GDP growth (1960–2023) from the [World Bank](https://data.worldbank.org).

3. **Data Preparation**  
   - Clean and reshape the dataset for time-series analysis.
   - Engineer volatility and compute a Stability Index.

4. **Modeling (Planned Phase)**  
   - Use Decision Trees for classification and K-Means Clustering to group similar countries.

---

### Tools & Technologies
- **Python**  
  - Data Handling: `pandas`, `numpy`  
  - Modeling: `scikit-learn`  
  - Visualization: `matplotlib`, `seaborn`
- **Jupyter Notebook**
- **CRISP-DM Framework**

---

### Initial Findings
- **Low-Risk Countries**: Poland, Malta, Belgium — consistent GDP growth and low volatility.
- **Medium-Risk Countries**: Germany, Spain, Finland — relatively stable, but with periodic shocks.
- **High-Risk Countries**: Latvia, Lithuania, Croatia — more vulnerable to economic disruptions.

Global events like the 2008 financial crisis and the COVID-19 pandemic had measurable effects across the region. Countries with higher Stability Index values demonstrated faster recoveries.

---

### Future Work
- Integrate additional macroeconomic indicators (e.g., inflation, unemployment).
- Expand analysis to political risk indicators.
- Apply Natural Language Processing (NLP) to news data for sentiment analysis.
- Implement additional machine learning techniques to validate and expand clustering and risk groups.
- Create a presentation that showcases methods used, overall findings and actionable insights.

---

### Ethical Considerations
All data used is publicly available. However, models like this can influence real-world decision-making with far-reaching consequences. It is essential that such tools are used transparently and responsibly, acknowledging potential limitations and biases.
