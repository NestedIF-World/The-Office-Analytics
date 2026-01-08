# 📎 The Office Analytics: Decoding the Cubicle 📊

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white)](https://www.kaggle.com/)

> *"Standardized testing, performance reviews, and capacity planning... basically, I'm doing the lord's work here."* — (Almost) Michael Scott.

👉 **[View My Analysis (HR_EDA.ipynb)](./HR_EDA.ipynb)**

## 🏢 Project Mission
Welcome to **The Office Analytics**. While I’m newly learning the ropes of Data Analysis, I decided to take a Kaggle HR dataset and treat it like a top-secret investigation into why people actually work here. 

Is it the money? The performance reviews? Or are they just looking for the exit? I used **Python** to find out.

---

## 🕵️‍♂️ Case Files (What I Analyzed)

### 1. The "I'm Outta Here" Analysis
I dug deep into termination reasons. It turns out "Finding another position" is the leading cause of the "World's Best Boss" mugs being left behind. 

### 2. The Paper Trail (Data Cleaning)
Before the fun stuff, I had to clean the mess. 
* Handled missing `ManagerID`s (probably hiding from meetings).
* Converted Date strings into `datetime` objects so I could track the passage of time.
* Managed 311 rows of employee secrets.

### 3. Salary vs. Happiness
Do higher salaries lead to better performance scores? I used **Seaborn** and **Matplotlib** to visualize the correlation between the paycheck and the "Engagement Survey."

---

## 💡 Learning Log: "Level 1 Data Wizard"
As a beginner, this project taught me:
* **Pandas GroupBy:** Like a filing cabinet, but actually useful.
* **Seaborn:** Because standard charts are boring.
* **Data Cleaning:** 80% of the job is just fixing typos.

---

## 🤝 The "Watercooler" (Discussion)
I am learning in public and I want **YOUR** feedback. 
* Did I miss a hidden trend in the absences?
* Got a better way to visualize the "Unhappy" employees?
* Should I have used a different chart for salary distribution?

**Drop a comment in the [Discussions] tab or open an [Issue]! Let’s grow this brain together. 🧠**

---

## 🚀 Deployment Instructions
1. `git clone https://github.com/NestedIF-World/The-Office-Analytics.git`
2. `pip install -r requirements.txt` (or just install pandas, seaborn, and matplotlib)
3. Open `HR_EDA.ipynb` and witness the corporate truth.

---
*Disclaimer: No Dunder Mifflin employees were harmed in the making of this analysis.*
