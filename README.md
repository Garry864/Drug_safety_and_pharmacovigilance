# 💊 Drug Safety and Pharmacovigilance

Welcome to the **Drug Safety and Pharmacovigilance** project repository! This analysis investigates the safety and monitoring of drugs using a comprehensive dataset to ensure effective pharmacovigilance practices. The project employs advanced data analysis techniques to uncover insights, identify trends, and ensure the safety of pharmaceutical products.

📄 **Profile Report**:  
[View the Detailed Analysis](https://garry864.github.io/Drug_safety_and_pharmacovigilance/)

---

## 📖 Project Overview

This project focuses on analyzing data related to drug safety and pharmacovigilance. By examining clinical trial records, we aim to understand trends, address data challenges, and support decision-making in the healthcare and pharmaceutical sectors.

Key areas of focus:
- **Clinical Trial Data**: Comprehensive analysis of records, including title, status, interventions, and sponsors.
- **Terminology Insights**: Definitions of common pharmacovigilance terms like *Clinical Study*, *Observational Trial*, *Principal Investigator*, *Sponsor*, *Intervention*, and *Enrollment*.
- **Exploratory Data Analysis (EDA)**: Leveraging univariate and bivariate analysis techniques to extract meaningful insights.
- **Missing Data Handling**: Identifying and addressing high percentages of missing values in features like "Acronym" and "Study Results."

---

## ✨ Key Findings

### 1️⃣ **Clinical Trial Landscape**
- Dataset contains **5,783 records** of drug safety and pharmacovigilance trials.
- **Top Statuses**: 
  - "Recruiting" status leads with **2,095 trials**.
  - "Not yet recruiting" follows with **1,224 trials**.
- **Trial Phases**:
  - "Recruiting" trials dominate across multiple phases, with the "Unknown" phase being the most common.

### 2️⃣ **Time Series Trends**
- A significant increase in trials after **2019**, reflecting intensified research efforts post-COVID-19 pandemic.

### 3️⃣ **Geographical Distribution**
- **Top Countries by Trial Count**:
  - United States: **1,287 trials**.
  - France: **647 trials**.
  - United Kingdom: **585 trials**.
- Countries with fewer trials tend to have higher missing data percentages in features like "Acronym."

### 4️⃣ **Missing Data Insights**
- High percentages of missing data in features such as "Acronym," "Study Documents," and "Results First Posted."
- Imputation techniques explored:
  - **Missing indicator** for categorical variables.
  - **Median imputation** for numerical features.

### 5️⃣ **Bivariate Analysis**
- Relationships between variables like study status and trial phase reveal:
  - **"Recruiting" trials** span multiple phases.
  - The "Unknown" phase is most common within recruiting trials.

---

## 🔍 Exploratory Data Analysis (EDA)

### **Univariate Analysis**
- Examines individual variables to understand distributions and frequencies.
- Highlights the prevalence of "Recruiting" trials.

### **Bivariate Analysis**
- Investigates relationships between features, e.g., study status vs. trial phase.

### **Time Series Analysis**
- Tracks trends in trial initiation over time, identifying spikes in research activities.

### **Location Analysis**
- Analyzes country-level data to map global research efforts and collaborations.

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/garry864/Drug_safety_and_pharmacovigilance.git
cd Drug_safety_and_pharmacovigilance
```

### 2️⃣ Install Dependencies
Ensure Python is installed and set up the required environment:
```bash
pip install -r requirements.txt
```

### 3️⃣ Explore the Data
- Open the **hosted report**: [Drug Safety and Pharmacovigilance Report](https://garry864.github.io/Drug_safety_and_pharmacovigilance/).
- Run the scripts in the `/src/` folder to reproduce or extend the analysis.

---

## 🌟 Future Exploration Opportunities

- **Adverse Event Analysis**: Study patterns and trends in reported adverse events for different drugs.
- **Regulatory Impact**: Examine the influence of regulatory changes on trial status and outcomes.
- **Global Collaborations**: Analyze partnerships between sponsors, collaborators, and principal investigators.
- **Risk Assessment**: Identify drugs with higher safety concerns for targeted monitoring.
- **AI/ML Integration**: Use predictive models to forecast trial outcomes or identify potential safety risks.

---

## 🤝 Contributions

Contributions are highly welcome! Whether it's improving the code, adding more visualizations, or providing new insights, feel free to fork the repository and submit a pull request.

---

## 📧 Contact

For inquiries or collaborations, reach out through the [GitHub profile](https://github.com/garry864).

---

🎉 **Thank you for exploring the project! Let's enhance drug safety and public health together!**
