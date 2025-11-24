# starlight-optimizer

🌟 Starlight Meal Optimizer

A linear optimization model for planning weekly school meals under cost, nutrition, and operational constraints.

⸻

📌 Overview

The Starlight Meal Optimizer is a linear programming model that determines the most cost-efficient weekly meal plan for a school while meeting all nutrition requirements and operational rules.

The project replicates real-world planning challenges — balancing budgets, constraints, and trade-offs — and mirrors the type of decision problems seen in retail planning, assortment optimization, and supply chain management.

This repository includes:
	•	Python implementation of the optimization model
	•	Input data structure (meals, costs, nutrition attributes)
	•	Scenario analysis framework
	•	Outputs demonstrating feasible meal plans under different constraints

⸻

🎯 Business Problem

A school needs to design a weekly menu that:
	•	Meets nutrition guidelines
	•	Stays within a budget
	•	Ensures variety across the week
	•	Respects kitchen production limits
	•	Minimizes total cost

Manual planning is slow, subjective, and hard to scale.
The goal: automate the planning process using optimization.

⸻

🧠 Approach
	1.	Define decision variables
	•	How many servings of each meal to include across the week.
	2.	Build constraints
	•	Budget constraints
	•	Minimum calorie/protein/fat requirements
	•	Maximum daily servings
	•	Variety/minimum number of distinct meals
	•	Kitchen capacity limits
	3.	Objective function
	•	Minimize total cost while satisfying all constraints.
	4.	Solve with a linear optimizer
	•	Gurobi or OR-Tools
	•	Return meal plan + cost breakdown
	5.	Scenario analysis
	•	What happens if budget increases/decreases?
	•	What if nutrition requirements tighten?
	•	What if a certain meal is removed or constrained?

⸻

📊 Results

The optimizer produces weekly meal plans that:
	•	Meet 100% of nutritional requirements
	•	Stay below the weekly budget constraint
	•	Maintain sufficient menu variety
	•	Respect all operational limits
	•	Provide insight into cost trade-offs

This structure can be adapted for:
	•	Retail assortment optimization
	•	Inventory planning under constraints
	•	Workforce scheduling
	•	Supply allocation problems

⸻

🛠️ Tech Stack
	•	Python
	•	Gurobi or OR-Tools (linear optimization)
	•	Pandas
	•	NumPy
	•	Matplotlib (optional for visuals)

⸻

🗂️ Repository Structure
starlight-meal-optimizer/
│
├── data/
│   └── meals.csv               # meal attributes & costs (sample data)
│
├── starlight_optimizer.py      # main optimization script
├── starlight_optimizer.ipynb   # notebook version with explanations
│
└── README.md                   # this file

⸻

🚀 How to Run the Model
1. Clone the repo
git clone https://github.com/YOUR-USERNAME/starlight-meal-optimizer.git
cd starlight-meal-optimizer
2. Install dependencies
pip install pandas numpy Gurobi
3. Run
python starlight_optimizer.py
4. View Results

Outputs include:
	•	Optimal weekly meal plan
	•	Total cost
	•	Constraint satisfaction report
	•	Scenario comparisons (if enabled)

⸻

🌱 Why This Project Matters

This model demonstrates:
	•	Constraint-based thinking
	•	Trade-off evaluation
	•	Analytical structuring of ambiguous problems
	•	Real-world use of optimization in planning

It represents the exact mindset required in:
	•	Retail planning & allocation
	•	Supply chain operations
	•	Inventory optimization
	•	Forecasting & scenario modeling
