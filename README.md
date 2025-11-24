# starlight-optimizer

# 🌟 Starlight Meal Optimizer  
*A linear optimization model for planning weekly school meals under cost, nutrition, and operational constraints.*

---

## 📌 Overview

The **Starlight Meal Optimizer** is a linear programming model that determines the most cost-efficient weekly meal plan for a school while satisfying all nutritional and operational rules.

It mirrors real planning challenges found in operations, inventory allocation, and retail assortment optimization—requiring trade-offs between budgets, capacity, variety, and requirements.

This repository includes:

- Python implementation of the optimization model  
- Input data structure (meal costs & nutrition attributes)  
- Scenario analysis options  
- Output meal plans and cost breakdowns  

---

## 🎯 Business Problem

A school must design a weekly menu that:

- Meets **nutrition guidelines**
- Stays within a **budget**
- Ensures **menu variety**
- Adheres to **kitchen capacity limits**
- Minimizes **total cost**

Manual planning is slow, inconsistent, and difficult to scale.  
The goal: **automate the decision process** using linear optimization.

---

## 🧠 Approach

1. **Decision Variables**  
   - Number of servings of each meal per day.

2. **Constraints**  
   - Budget limits  
   - Calorie, protein, fat requirements  
   - Daily maximum servings  
   - Variety requirements  
   - Production capacity  

3. **Objective Function**  
   - Minimize total weekly cost.

4. **Solver**  
   - Implemented using **Gurobi** or **OR-Tools**.

5. **Scenario Analysis**  
   - Budget changes  
   - Nutrition requirement changes  
   - Menu substitutions  

---

## 📊 Results

The optimizer produces weekly meal plans that:

- Meet all required nutrition rules  
- Stay within budget  
- Include adequate variety  
- Respect kitchen operational limits  
- Minimize total cost  

This framework can be adapted for:

- Retail assortment optimization  
- Inventory planning  
- Workforce scheduling  
- Supply allocation problems  

---

## 🛠️ Tech Stack

- **Python 3**
- **Gurobi** or **OR-Tools** (linear optimization)
- **Pandas**
- **NumPy**
- **Matplotlib** (optional)

---

## 🗂️ Repository Structure
