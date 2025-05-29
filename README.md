# 🚛 Transport Optimization – Multi-Commodity Flow Modeling

This project implements and compares two linear programming models—aggregated (TMANIA) and disaggregated (TMANID)—to solve a multi-commodity flow problem across a transport network. Developed as part of the INFO-F310 (Algorithms and Operations Research) course at ULB.

---

## 🎯 Objective

Minimize the total cost of transporting multiple items from several sources to several destinations through a network of intermediate nodes, subject to capacity and flow constraints.

---

## 🧠 Methodology

Two modeling approaches were used:

- **Aggregated Model (TMANIA):** One flow variable per arc, with item constraints merged.
- **Disaggregated Model (TMANID):** One flow variable per arc and per item, providing finer granularity.


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
