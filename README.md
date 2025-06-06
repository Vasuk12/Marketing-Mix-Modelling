# Marketing-Mix-Modelling

# Bayesian Marketing Mix Modeling (MMM)

This project estimates the Return on Investment (ROI) of various marketing channels using **Bayesian Linear Regression** with `PyMC`. It reflects key skills outlined in data science roles, particularly at organizations like **Bank of Ireland**, including statistical modeling, causal inference, and marketing analytics.

---

## Objective

To quantify the impact of media spend across different channels (TV, Digital, SEM, etc.) on total GMV (Gross Merchandise Value) and identify the most efficient channels using a probabilistic approach.

---

## Tools & Libraries

- Python 3.x
- `PyMC` – Bayesian inference
- `ArviZ` – Posterior analysis and visualizations
- `Pandas`, `NumPy` – Data manipulation
- `Matplotlib`, `Seaborn` – Visualization
- `scikit-learn` – Standardization

---

## Dataset Overview

The dataset includes:
- Monthly GMV and units sold per category
- Marketing channel investments (e.g., TV, Digital, SEM)
- Special events and **Net Promoter Score (NPS)**

---

## Methodology

1. **Feature Selection**: Marketing spend variables + NPS
2. **Standardization**: To prepare data for PyMC modeling
3. **Bayesian Regression**: Using prior/posterior distributions to model GMV
4. **ROI Estimation**: Based on contribution per €1 spent
5. **Posterior Analysis**: Interpretation of coefficients & credible intervals

---

## Key Results

### ROI Ranking (Top Channels)
- **ContentMarketing**: Highest ROI
- **Sponsorship**: Strong positive return
- **SEM & Digital**: Moderate ROI
- **Affiliates / OnlineMarketing**: Lower ROI

### NPS Insight
- Posterior mean: **-1.2**
- 94% HDI: **[-3.1, 0.7]**
- Suggests an inconclusive but potentially **negative** effect of NPS on GMV

---

## Business Recommendations

-  **Scale up** ContentMarketing and Sponsorship efforts
-  **Audit & optimize** underperforming channels like Affiliates
-  **Investigate NPS** further — inconclusive link may suggest confounding factors or data limitations
-  Consider time-lagged modeling for long-term media effects

---

## Next Steps 

- Add lag variables for time-series causal effects
- Integrate A/B testing or simulated experiments
- Extend with hierarchical or dynamic Bayesian models

---

## Skills Demonstrated

- Bayesian inference & causal analysis
- ROI interpretation with uncertainty
- PyMC modeling pipeline
- Data storytelling for marketing analytics

---
