# 🚛 Transport Optimization – Multi-Commodity Flow Modeling

This project models and compares two linear programming formulations of a multi-commodity transport problem using Python and GLPK. It was developed as part of the INFO-F310 “Algorithms and Operations Research” course .

We solve a cost-minimization problem involving the transportation of multiple distinct items across a network of nodes and arcs, considering supply/demand constraints and capacity limits. Two formulations are implemented:

- **TMANIA (Aggregated Model)**: Merges commodity flows into a single variable per arc.
- **TMANID (Disaggregated Model)**: Models one variable per item per arc, offering more control and complexity.


---

## 🎯 Objective

The goal is to determine the most cost-efficient routing of different items from a set of origin nodes to destination nodes through a network of intermediate nodes. Each item has specific source and destination requirements, and each arc has a capacity and transport cost.

**Constraints:**
- Flow conservation at each node per commodity
- Arc capacity limits
- Demand/supply balancing

**Objective:**
- Minimize the total transport cost

---

## 🧠 Methodology

Two modeling approaches were used:

### ✅ TMANIA – Aggregated Model
- One variable per arc: total flow of all items combined.
- Simpler and faster but may be infeasible when demands clash.

### ✅ TMANID – Disaggregated Model
- One variable per item per arc: models exact item routing.
- More flexible and accurate, but higher memory and time complexity.



---

## 🛠️ Tools 

- Python 3  
- GLPK (GNU Linear Programming Kit)   

---
## 📊 Results
The report includes:
- Memory and time comparisons
- Scalability analysis
- Trade-offs between model granularity and solver performance

---
## 📄 Authors
- Ali Bahja
- Quentin Lejeune
