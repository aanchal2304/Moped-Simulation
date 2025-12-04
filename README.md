# Moped Production & Demand Simulation

This project simulates daily moped production, demand variation, shortage penalties, and inventory cost using probability-based modeling. The goal is to calculate expected profit, analyze demand fluctuations, and identify optimal production decisions.

---

## 📌 Project Overview
- Developed a 30-day simulation using probabilistic demand distribution.
- Calculated daily revenue, production cost, shortage penalties, and inventory holding cost.
- Visualized demand and profit trends across the simulation period.
- Generated business insights to support production and planning decisions.

---

## 🛠️ Technologies Used
- Python  
- NumPy  
- Matplotlib  
- Jupyter Notebook  
- Probability & Simulation Concepts  

---

## 📂 Parameters Used
- **Production Capacity:** 50 units/day  
- **Selling Price:** ₹20,000 per unit  
- **Production Cost:** ₹12,000 per unit  
- **Shortage Penalty:** ₹5,000 per unit  
- **Inventory Holding Cost:** ₹2,000 per unit  
- **Simulation Period:** 30 days  

---

## 📊 Key Results
- **Total Profit:** ₹53,20,000  
- **Average Daily Profit:** ₹1,77,333  
- **Total Shortages:** 60 units  
- **Total Inventory Left:** 290 units  

---

## 📈 Visualizations
- Daily Demand Plot  
- Daily Profit Plot  

(Generated within the Jupyter Notebook.)

---

## 🧠 Business Insights
1. Strong profitability indicates that the current production strategy is financially stable.  
2. Shortage of 60 units across 30 days shows missed sales on high-demand days.  
3. Inventory left (290 units) highlights overproduction during low-demand days, increasing holding costs.  
4. Slightly increasing daily production capacity may reduce shortage penalties.  
5. Running simulations at different capacities (45, 50, 55, 60 units/day) can help determine the most profitable production level.

---

## ▶️ How to Run the Project

Install required libraries:
pip install numpy matplotlib

Run the notebook:

Open `moped_simulation.ipynb` and run all cells.

---



