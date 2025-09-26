# A Mixed Integer Programming Approach for Risk-Aware Portfolio Selection  
### A Case Study on Vietnam’s Financial Sector Stocks

📌 Academic Project – Applied Optimization Course (Individual Work)  
This project develops a **Mixed Integer Programming (MIP) model** to optimize portfolio selection with a focus on **risk awareness**. The case study is conducted on **Vietnam’s financial sector stocks**.  

---

## 📂 Project Structure

portfolio-optimization/
│── main.py # Python code for optimization model
│── data/ # Datasets for different time periods
│ ├── 2012–2014_ Recovery - Trang tính1.csv
│ ├── 2015–2017_ Expansion - Trang tính1.csv
│ ├── 2018–2020_ Contraction - Trang tính1.csv
| └── 2021–2023_ Expansion → Recession → Recovery - Trang tính1.csv


---

## ⚡ Project Overview
- Formulated a **risk-aware portfolio optimization model** using Mixed Integer Programming.  
- Incorporated **binary decision variables** to model stock selection.  
- Applied **constraints**: diversification.  
- Conducted experiments across **three different market phases** using separate datasets.  

---

## 🛠 Tools & Libraries
- Python (pandas, numpy)  
- Optimization solver: CPLEX
- matplotlib (for visualization)  

---

## 📊 Results
- Optimized portfolios under different market scenarios.  
- Compared diversification strategies and their impact on portfolio performance.  
- Highlighted insights for Vietnam’s financial sector investment.  

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/NguyenBich21/portfolio-optimization.git
   cd portfolio-optimization
2. Ensure required libraries are installed:

pip install -r requirements.txt

3. Run the optimization code:

python main.py

📌 Notes

This is an individual academic project for the Applied Optimization course.

Dataset files (data_phase1.csv, data_phase2.csv, data_phase3.csv) represent different market stages for testing robustness of the model.
