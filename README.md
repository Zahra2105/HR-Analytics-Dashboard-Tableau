# 🧠 HR Analytics Dashboard | Tableau

### Overview  
Business Intelligence & Data Visualization project focused on **HR metrics and employee performance analysis** using **Tableau**.  
The dataset was **synthetically generated with Python (Faker Library)** and enhanced with realistic attributes through **ChatGPT**.

---

### 📊 Project Objectives
- Analyze **employee demographics, salary distributions, and performance ratings**
- Identify **departmental hiring and termination trends**
- Correlate **education level, age, and income**
- Enable **interactive filtering** by gender, location, status, and role in Tableau

---

### 🧩 Dataset Description
- **Rows:** ~9,000 employees (synthetic data)
- **Columns:**
  - `Employee_ID` | `FirstName` | `LastName` | `Gender` | `Location` | `Education_Level`
  - `Department` | `Job_Title` | `Salary` | `Performance_Rating` | `HireDate` | `TermDate`

Data was created using a Python script (`hr_data_generation.py`) with `Faker` and fine-tuned via ChatGPT for realistic HR distributions.

---

### 🧠 Tools & Technologies
- Tableau – Dashboard design, data model integration, calculated fields  
- Python (Faker, Pandas) – Synthetic data generation  
- CSV – Clean relational dataset for import to Tableau

---

### 📈 Dashboard Highlights
**Main KPIs:**
- Active Employees: 7,984  
- Hired vs. Terminated (YoY trend)  
- Top-performing departments based on total hires and salary range  

**Interactive Views:**
1. **Overview Dashboard:** Company-wide HR trends  
2. **Detail Dashboard:** Employee-level granularity (filters by demographics & role)

---

### 🧰 Files Included
| Folder | Description |
|--------|--------------|

| `/dashboard` | Tableau dashboard screenshots (Overview + Details) |
| `README.md` | Documentation & insights |
| `LICENSE` | Optional open‑source license |

---

### 💡 Insights
- **IT and Finance** show highest average salary levels.  
- **Employees aged 35‑44** demonstrate top performance ratings.  
- **Gender salary gap** observed among mid-level positions, narrowing at executive levels.

---

### 🔗 Author
**Zahra Kazemi**  
BI & Data Analyst | Proficient in Tableau, Power BI, SQL, Python  
📧 nedakazemiiii.1372@gmail.com  

---

> _Synthetic dataset built for visualization and analytical demonstration purposes only._
