# ICMI-PAPER
MACHINE ELEARNING ENHANCED OAXACA BLINDER DECOMPOSITION
# Machine Learning-Enhanced Oaxaca-Blinder Decomposition for Analyzing Healthcare Test Price Variations Across Indian Cities

## 📘 Overview

This repository contains the complete research paper and supplementary materials for:

**Title**:  
**Machine Learning-Enhanced Oaxaca-Blinder Decomposition for Analyzing Healthcare Test Price Variations Across Indian Cities**

**Authors**:  
- Anshuman Parida – b23es1008@iitj.ac.in  
- Pranav Pant – pant.4@iitj.ac.in  
- Tarun Raj Singh – singh.188@iitj.ac.in  
- Department of Computer Science & Engineering,  
  Indian Institute of Technology Jodhpur, India

---

## 📄 Abstract

This study investigates the variations in healthcare test prices across Indian cities using an extended Oaxaca-Blinder decomposition method enhanced with machine learning techniques.

We introduce a novel dataset — **HEALTH-PRICE** — combining city-level demographics, economics, and healthcare infrastructure data. Using traditional regression and neural models, we decompose the observed price disparities into **explained** (e.g., city population, per capita income, number of labs) and **unexplained** (e.g., market inefficiencies, provider behavior) components.

Our analysis reveals:
- Significant structural inefficiencies in diagnostic pricing
- Potential policy pathways to improve affordability
- Actionable insights for making diagnostic services more equitable

---

## 🧠 Key Contributions

- Developed an extended multi-group Oaxaca-Blinder decomposition framework.
- Integrated machine learning (MLP neural networks + SHAP) for non-linear counterfactual modeling.
- Built and released the **HEALTH-PRICE** dataset with over 126,000 entries across 101 Indian cities.
- Proposed targeted policy strategies based on empirical decomposition.

---

## 📊 Dataset Description

The **HEALTH-PRICE** dataset includes:
- 101 Indian cities
- 1393 diagnostic test types
- 163 diseases
- City-level predictors: population, income, lab density, city type, and zone
- Test prices collected using Selenium + BeautifulSoup scraping from Lal PathLabs

*Note: The dataset and scraping scripts are not included here but are referenced in the paper and hosted externally.*

---

## 🧮 Methodology

We employ both:
- **OLS-based Oaxaca-Blinder decomposition**
- **Neural Oaxaca-Blinder decomposition** using feedforward neural networks and SHAP interpretability

The study quantifies:
- **Explained component**: Impact of observable variables
- **Unexplained component**: Structural and unobservable effects

---

## 🧪 Technologies Used

- Python
- pandas, scikit-learn, statsmodels
- Selenium & BeautifulSoup (for scraping)
- PyTorch (for neural decomposition)
- SHAP (Shapley values for NN interpretability)
- Matplotlib & Seaborn (visualizations)

---

## 📚 Citation

Please cite this work if you use or refer to it in any academic or public context:

### APA:
Parida, A., Pant, P., & Singh, T. R. (2025). *Machine Learning-Enhanced Oaxaca-Blinder Decomposition for Analyzing Healthcare Test Price Variations Across Indian Cities*. Indian Institute of Technology Jodhpur.

### BibTeX:
```bibtex
@article{parida2025healthprice,
  title={Machine Learning-Enhanced Oaxaca-Blinder Decomposition for Analyzing Healthcare Test Price Variations Across Indian Cities},
  author={Parida, Anshuman and Pant, Pranav and Singh, Tarun Raj},
  journal={Indian Institute of Technology Jodhpur},
  year={2025}
}
