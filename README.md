# 📈 CS Student Strength Analysis

This project explores the relationship between **academic performance** and **problem-solving ability** among Computer Science students. Using data visualizations and statistical insights, we break down how performance in core CS courses correlates with the number of coding problems solved — a key indicator of applied skill.

---

## 🧠 Objective

To analyze whether **higher academic performance (GPA)** in technical subjects such as **OOP, Algorithms, and AI** correlates with **problem-solving strength**, and to identify which subjects show the most variance or consistency among students.

---

## 📁 Dataset

- `CS Student Strength.csv`
- Includes GPA data from 20+ CS courses (theory and sessional)
- Also includes **"Total Problems Solved"**, indicating applied coding skill

---

## 📊 Visualizations

### 1. 📊 Average GPA Per Course

<img width="987" alt="Screenshot 2025-04-15 at 8 14 50 AM" src="https://github.com/user-attachments/assets/d1aef961-fc5b-47de-86e2-41a680bd701d" />


> Bar plot showing mean GPA across all subjects  
✅ **Conclusion**: Students performed best in `DBMS`, `Artificial Intelligence`, and `Discrete Math`. Subjects like `Machine Learning` and `Algorithm` showed lower average GPAs.

---

### 2. 🧪 Grade Distribution in Core CS Subjects

<img width="990" alt="Screenshot 2025-04-15 at 8 15 09 AM" src="https://github.com/user-attachments/assets/ca1bed71-0d70-4b3d-88d5-14793f6e43c0" />


> Box plot of GPA distribution in key subjects  
✅ **Conclusion**: Subjects like `Data Structure`, `Operating Systems`, and `OOP` had a **wider GPA range**, suggesting varying student comprehension. `Compiler Design` showed a tighter distribution.

---

### 3. 📈 Problem-Solving vs Course GPA

<img width="853" alt="Screenshot 2025-04-15 at 8 15 41 AM" src="https://github.com/user-attachments/assets/e0f7ac56-8cde-4bfc-becb-6f8afc7d4e38" />

<img width="990" alt="Screenshot 2025-04-15 at 8 16 36 AM" src="https://github.com/user-attachments/assets/b9206063-2e70-498f-b231-a40f3418e65a" />



> Scatter plots comparing "Total Problems Solved" with GPA in:
- `OOP`
- `Algorithm`
- `Artificial Intelligence`


✅ **Conclusion**: There appears to be a **positive correlation** — students with higher GPAs in these subjects tend to solve more problems. This supports the idea that academic performance and applied skill are linked, though not perfectly.

---

### 4. 🔥 Correlation Heatmap

<img width="1094" alt="Screenshot 2025-04-15 at 8 17 11 AM" src="https://github.com/user-attachments/assets/83cdfc1e-72cd-455d-8110-a885530790ae" />


> Heatmap of correlations between all subjects and total problems solved  
✅ **Conclusion**:
- Moderate correlation between `Artificial Intelligence`, `Algorithm`, and problem-solving.
- Some theory-heavy subjects (like `Theory of Computing`) showed weaker correlations, indicating that not all GPA scores predict practical ability.

---

## 📌 Key Insights

- Students who perform well in **AI, Algorithms, and OOP** tend to solve more coding problems.
- Some students excel at problem-solving even if they struggle in theory-heavy courses.
- There’s a strong need to **balance theoretical and applied learning** in CS education.

---

## 🧰 Built With

- Python 3  
- pandas, NumPy  
- matplotlib, seaborn  

---

## 🧠 What I Learned

- How to clean and analyze structured academic data
- How to visualize relationships between variables
- That **GPA is useful**, but not always the best predictor of **applied CS strength**

---
---

## 👨‍💻 Author

**Emdya Permuy-Llovio**  
---

