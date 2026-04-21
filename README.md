# Global-SaMD-Regulatory-Analysis
Comparative analysis of regulatory success factors for AI-SaMD (FDA, EMA, HSA) based on 2023 WHO data. Features statistical testing and data visualization in Python

###  Data Access
The dataset used in this analysis is included in the repository for reproducibility:
* **File:** `Regulatory_Validation_Data 2023`
* **Source:** Derived from [WHO Regulatory Validation Data 2023](https://www.kaggle.com/datasets/digrok/who-ai-regulatory-2023)

### How to Run
1. Clone this repository.
2. Ensure you have the required libraries installed (`pandas`, `scipy`, `seaborn`).
3. Open `SaMDAnalysis.ypnb` in Jupyter or Google Colab.
4. The notebook is configured to load the data directly from the local path.
   
### Project Objectives
* Analyze the **WHO Regulatory Validation Data 2023** dataset.
* Compare approval rates between North American (FDA) and European (EMA) markets.
* Identify correlations between safety scores and regulatory success.
* Provide a data-driven roadmap for global SaMD market entry.

### Technology Stack
 **Language:** Python
 **Key Libraries:**  `Pandas`: For complex data structure manipulation.
  * `Matplotlib` / `Seaborn`: Visualizing "Transatlantic Divides" and safety distributions.
  * `SciPy`: Implementing T-tests for statistical hypothesis validation.

### Analysis & Methodology
The analysis treats performance metrics as discrete **vectors**. Key steps include:
1. **Regulatory Divergence:** Investigating why high safety scores (optimized for the FDA) do not guarantee success in the EU, where qualitative filters are more stringent.
2. **Statistical Analysis:** Utilizing T-tests to confirm significant differences between safety requirements across various global markets.
3. **Data Visualization:** Generating bimodal distribution charts to highlight the impact of "Explainable AI" parameters.

### Key Findings
The study reveals that global market access requires a bimodal strategy. While the FDA prioritizes high technical safety thresholds, the EMA and Asian markets place significant weight on ethical frameworks and transparency.

---
**Author:** Matteo Lucchiari  
*Biomedical Engineering Student - University of Padua*
