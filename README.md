# Sleep Health and Lifestyle Analysis  

## 📌 Project Overview  
This project explores the **Sleep Health and Lifestyle dataset** to analyze factors affecting sleep quality, stress levels, and sleep disorders.  
It includes **data cleaning, exploratory data analysis (EDA), visualization, and feature engineering** for better insights.  

---

## 📂 Dataset Information  
- **Rows:** 155  
- **Columns:** 16  

### Features:
- `Person ID` – Unique identifier  
- `Gender` – Male (0), Female (1)  
- `Age` – Age of participant  
- `Occupation` – Profession  
- `Sleep Duration` – Average daily sleep hours  
- `Quality of Sleep` – Self-reported (scale 1–10)  
- `Physical Activity Level` – Weekly activity minutes  
- `Stress Level` – Stress score (1–10)  
- `BMI Category` – Underweight / Normal / Overweight / Obese  
- `Blood Pressure` – Systolic/Diastolic  
- `Heart Rate` – Resting heart rate  
- `Daily Steps` – Average steps per day  
- `Sleep Disorder` – None / Insomnia / Sleep Apnea  

### Engineered Features:
- `Sleep Efficiency` = Quality of Sleep ÷ Sleep Duration  
- `Stress Category` = Binned into **Low, Medium, High**  
- `Age Group` = Categorized into **Young, Middle, Senior**  

---

## 🛠️ Steps Performed  

### 1. **Data Cleaning**
- Removed missing values  
- Checked duplicates → **0 duplicates found**  
- Converted categorical variables (e.g., Gender mapping Male=0, Female=1)  

### 2. **Exploratory Data Analysis (EDA)**  
📊 Below are some key plots generated during the analysis:  

#### 🔹 Age Distribution  
![Age Distribution]

#### 🔹 Sleep Duration Distribution  
![Sleep Duration Distribution] 

#### 🔹 Distribution of Sleep Disorders  
![Distribution of Sleep Disorders]  

#### 🔹 Stress Level across Sleep Disorders  
![Stress Level across Sleep Disorders] 

#### 🔹 Gender vs Sleep Disorder  
![Gender vs Sleep Disorder] 

#### 🔹 BMI Category vs Sleep Disorder  
![BMI Category vs Sleep Disorder] 

#### 🔹 Stress Category vs Age Group  
![Stress Category vs Age Group] 

---

## 📊 Sample Output Data  

### 🔹 Dataset Preview (after cleaning & feature engineering)  

| Person ID | Gender | Age | Occupation           | Sleep Duration | Quality of Sleep | Stress Level | BMI Category | Sleep Disorder | Sleep Efficiency | Stress Category | Age Group |
|-----------|--------|-----|----------------------|----------------|------------------|--------------|--------------|----------------|------------------|----------------|-----------|
| 4         | 0      | 28  | Sales Representative | 5.9            | 4                | 8            | Obese        | Sleep Apnea    | 0.67             | High           | Young     |
| 5         | 0      | 28  | Sales Representative | 5.9            | 4                | 8            | Obese        | Sleep Apnea    | 0.67             | High           | Young     |
| 6         | 0      | 28  | Software Engineer    | 5.9            | 4                | 8            | Obese        | Insomnia       | 0.67             | High           | Young     |
| 7         | 0      | 29  | Teacher              | 6.3            | 6                | 7            | Obese        | Insomnia       | 0.95             | High           | Young     |
| 17        | 1      | 29  | Nurse                | 6.5            | 5                | 7            | Normal Weight| Sleep Apnea    | 0.77             | High           | Young     |

---

## 🔧 Tech Stack  
- **Python**  
- **Pandas** – Data processing  
- **NumPy** – Numerical analysis  
- **Matplotlib & Seaborn** – Visualization  

---
