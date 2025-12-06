📊 Titanic Survival Analysis – EDA Project

Syntecxhub Data Science Internship – Task 3

📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to understand the factors that influenced passenger survival.
The analysis focuses on gender, passenger class, and age groups, supported by visualizations using Python's Matplotlib.

🧰 Tools & Technologies Used
   - Python
   - Pandas
   - Matplotlib
   - Jupyter Notebook


📁 Dataset Information
   - Raw Dataset: Titanic-Dataset.csv
   - Cleaned Dataset: Titanic_Cleaned.csv (saved in outputs/ folder)
   - Total Records: 891
   - Key Fields Used:
      - Survived
      - Sex
      - class
      - age
      - Embarked


🛠 Data Cleaning Performed
   - Filled missing Age values using median
   - Filled missing Embarked values using mode
   - Dropped Cabin due to excessive missing values
   - Created an Age_Group feature:
      - Child (0–12)
      - Teen (13–18)
      - Adult (19–50)
      - Senior (50+)


Cleaned data was exported to:
   - 📄 outputs/Titanic_Cleaned.csv
   - 📈 Visualizations Created
      - 1️⃣ Survival Rate by Sex (Bar Chart)
          - Shows strong survival preference for female passengers.
      - 2️⃣ Survival Rate by Passenger Class (Bar Chart)
          - Reveals higher survival rates for 1st Class passengers.
      - 3️⃣ Survival Rate by Age Group (Bar Chart)
          - Children had the highest survival probability.
      - 4️⃣ Age Distribution by Survival (Boxplot)
          - Highlights younger median age among survivors.
      - 5️⃣ Age vs Survival (Violin Plot)
          - Shows how different age ranges were distributed for survivors and non-survivors.


📌 Final Insights Summary (3–5 Key Findings)

Female passengers had significantly higher survival rates than males, reflecting the “women and children first” evacuation rule.

1st Class passengers survived at much higher rates than those in 2nd and 3rd class, highlighting socio-economic impact on survival.

Children showed the highest survival probability, while adults and seniors had much lower chances.

Younger passengers were more likely to survive, as seen in the boxplot and violin plots.

Gender, passenger class, and age were the strongest predictors of survival based on the dataset.


🚀 How to Run This Project
   - Clone this repository
   - Open the notebook:
      - Syntecxhub_Task3_Titanic_EDA.ipynb
   - Run all cells in Jupyter Notebook
   - View exported charts inside the outputs/ folder

🧑‍💻 Author
   Arpan Birendra Chourasia
   Data Science Intern @Syntecxhub
  📍 India

⭐ If you find this project helpful, consider starring the repository!
