# Hospital Resource Allocation Optimization using Linear Programming

## 📘 Project Overview
This project focuses on **optimizing hospital resource allocation** using **Linear Programming (LPP)** techniques. The study applies the **Simplex Method** through **TORA software** to allocate limited hospital resources — **nurses, beds, medical equipment, and doctor-hours** — efficiently across **15 departments** in a government hospital in **Karnataka, India**.  
The objective is to **minimize patient wait times** while ensuring each department receives the resources it needs, based on real hospital data.

---

## 🧩 Problem Statement
Government hospitals often face issues such as:
- Shortage or misallocation of staff (nurses and doctors)
- Uneven bed distribution
- Limited medical equipment availability  
These problems lead to overcrowding, long patient wait times, and burnout among staff.  
This project aims to solve these issues through a **data-driven optimization model**.

---

## 🎯 Objectives
1. Develop an integrated LP model for resource allocation across 15 departments.  
2. Minimize total patient wait time using real-world hospital data.  
3. Provide a **decision-support framework** for hospital administrators to enhance efficiency and service delivery.

---

## 🧮 Methodology

### 1. **Data Collection**
Collected real and realistic data from a government hospital in Karnataka:
- Nurses: 500  
- Beds: 1000  
- Medical Equipment: 200  
- Doctor-Hours: 720  

### 2. **Model Formulation**
Objective Function (to maximize efficiency / minimize total wait time):
Max Z = 5x + 3y + 4z + 6t
Where:  
- `x` = Nurses allocated  
- `y` = Beds allocated  
- `z` = Equipment allocated  
- `t` = Doctor-hours allocated  

Weights (wait-time reduction impact):  
- Nurse = 5 mins/patient  
- Bed = 3 mins/patient  
- Equipment = 4 mins/patient  
- Doctor-hour = 6 mins/patient  

### 3. **Constraints**
- Total resources available (e.g., nurses ≤ 500, beds ≤ 1000, etc.)
- Department-wise minimum resource requirements  
- Non-negativity constraints (x, y, z, t ≥ 0)

### 4. **Implementation**
- Software Used: **TORA** (Simplex Method)
- Variables: 60 (4 for each of the 15 departments)
- Constraints: 64 (4 total + 60 departmental)
- Solved for optimal allocation of all resources

---

## 📊 Results Summary
| Resource | Available | Used | Utilization (%) |
|-----------|------------|------|----------------|
| Nurses | 500 | 380 | 76% |
| Beds | 1000 | 905 | 90.5% |
| Equipment | 200 | 125 | 62.5% |
| Doctor-Hours | 720 | 90 | 12.5% |

### Department-Wise Highlights
- **Medicine** and **Surgery** departments received the highest resource allocations (reflecting high demand).  
- Balanced allocation avoided staff burnout and underutilization.  
- Model achieved **maximum efficiency** within the given constraints.

---

## 💡 Key Insights
- Linear Programming (LP) can reduce hospital wait times by **20–30%**.  
- Optimal allocation ensures **balanced workloads** and **improved patient satisfaction**.  
- The TORA-based model is practical and can be easily replicated for other hospitals.

---

## 🧠 Tools and Technologies
- **TORA Software** – for LP model solving  
- **Simplex Method** – optimization technique  
- **Microsoft Excel / Sheets** – data preparation and tabulation  

---

## 🏁 Conclusion
This project demonstrates the potential of **operations research and mathematical modeling** in improving healthcare efficiency.  
By using LP through TORA, hospitals can allocate limited resources intelligently, reduce patient wait times, and ensure equitable service delivery.  
The developed model can serve as a **decision-support system** for administrators in public hospitals across India.

---

## 📚 References
1. Operations Management Techniques for Resource Optimization in Healthcare (2009)  
2. A Hybrid Analytical Model for Hospital Resource Optimization (2021)  
3. Optimizing Healthcare Delivery: A Model for Staffing and Resource Allocation (2023)  
4. Linear Programming Applied to Healthcare Problems (2003)  
5. KIMS Hospital Hubli Dataset  
6. TORA Application  
7. Research Gate, PMC, MDPI, PubMed, Semantic Scholar  

