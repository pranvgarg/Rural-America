# RuralAmerica
 
Here's a detailed and engaging README file for your GitHub project, incorporating the provided files and the information you've shared:

---

# 🌟 **Predicting Household Income in Rural and Small-Town America** 🌟

Welcome to our Data Science Final Project! This project aims to predict the median household income across various counties in the United States using five years of historical data. We utilized the **Atlas of Rural and Small-Town America** dataset from the USDA, which includes comprehensive information on jobs, income, people, and veterans. 

![Income Prediction](https://link-to-your-banner-image.png)

---

## 📜 **Project Overview**

### **Main Question**
> How do 5 years of historical data (2017-2021) on various U.S. census features affect future median household income values?

### **Why is this Important?**
Understanding the factors that influence household income in rural areas can inform better policy-making and resource allocation, helping to uplift communities that often face unique economic challenges. Our analysis offers valuable insights for policymakers, non-profits, and community organizations.

### **Project Team**
- **Akash Barathan**  
- **Brinda Asuri**  
- **Haoyi Zhou**  
- **Mykyta Zavhorodko**  
- **Pranav Garg**  

---

## 🛠️ **Project Files**

1. **[County Classifications.csv](./County%20Classifications.csv)**  
   Data on county classifications used for feature engineering and analysis.

2. **[Jobs.csv](./Jobs.csv)**  
   Data on employment across various counties, crucial for understanding economic factors.

3. **[Income.csv](./Income.csv)**  
   Dataset focusing on income-related features, directly tied to our target variable.

4. **[People.csv](./People.csv)**  
   Contains demographic data essential for understanding the human factors influencing income.

5. **[Veterans.csv](./Veterans.csv)**  
   Information on veterans, providing insight into specific population segments.

6. **[RuralAtlasFinal.ipynb](./RuralAtlasFinal.ipynb)**  
   Jupyter notebook containing all code used for data processing, analysis, and modeling.

7. **[DS Final Project Presentation.pptx](./DS%20Final%20Project%20Presentation.pptx)**  
   Final presentation showcasing our findings, methodologies, and insights.

8. **[Project_Barathan_Asuri_Zhou_ Zavhorodko_Garg.docx](./Project_Barathan_Asuri_Zhou_%20Zavhorodko_Garg.docx)**  
   Detailed project report, including exploratory data analysis (EDA), feature engineering, and model evaluation.

---

## 🔍 **Data Insights and Analysis**

### **Exploratory Data Analysis (EDA)**
- **Initial Features**: 250 features across four datasets (jobs, income, people, veterans).
- **Post-Cleaning**: 98 features were retained after removing irrelevant and null data points.

### **Feature Engineering**
- Calculated ratios for better comparison across counties.
- Normalized variables to standardize data.
- Example Features:
  - **Ed1LessThanHS_perCapita**: Per capita individuals with less than a high school diploma.
  - **FemaleHHRatio**: Ratio of female-headed households to total households.

### **Modeling**
We implemented several models to predict median household income:
- **Random Forest**
- **XGBoost**
- **Ridge Regression**
- **Lasso Regression**
- **K-means Clustering**

#### **Best Performing Model: XGBoost**
- **RMSE**: 5056
- **Important Features**:
  - **PercentPoverty0to17**
  - **HomeOwnership_Education**
  - **Ed5CollegePlus_perCapita**

![Model Performance](https://link-to-model-performance-image.png)

---

## 📊 **Results**

- **Key Predictors**: 
  - **Education**: Higher education levels are strongly correlated with higher median household income.
  - **Poverty**: Counties with higher percentages of children living in poverty tend to have lower median incomes.

- **Final Thoughts**: Focusing on reducing poverty, particularly child poverty, and increasing access to higher education could significantly impact median household income across rural America.

---

## 🚀 **How to Use This Repository**

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/Income-Prediction.git
   ```

2. **Navigate to the Project Directory**
   ```bash
   cd Income-Prediction
   ```

3. **Explore the Jupyter Notebook**
   - Open `RuralAtlasFinal.ipynb` to review and run the analysis.

4. **Check Out the Presentation**
   - Open `DS Final Project Presentation.pptx` to view our findings.

5. **Read the Full Report**
   - Open `Project_Barathan_Asuri_Zhou_ Zavhorodko_Garg.docx` for a detailed project summary.

---

## 🤝 **Contributions**
We welcome contributions! Please fork the repository and submit a pull request with any improvements or suggestions.

---

## 📬 **Contact**
If you have any questions or need further information, feel free to reach out to any of the team members via GitHub.

---

### ⭐ **If you found this project helpful, please give us a star!** ⭐

---

This README file should give your project a professional and engaging presentation on GitHub, complete with emojis, links to files, and detailed sections.
