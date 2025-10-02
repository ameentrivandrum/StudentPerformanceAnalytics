# 🎓 Student Performance Analytics

A collection of **Python-based data analysis and reporting projects** built during my academic career as an Assistant Professor.  
These projects showcase data cleaning, Excel automation, PDF reporting, and visualization using **Pandas, OpenPyXL, and Matplotlib**.  

---

## 📂 Projects

### 1. Result Percentage Analysis (`resultpercentage.ipynb`)
- Cleans raw student result data from Excel (multi-line rows combined).  
- Parses subject codes & grades, computes **student-wise summaries** (pass/fail/withheld, pass %).  
- Generates **subject-wise pass percentage** analysis.  
- Outputs structured Excel reports:  
  - `parsed_student_results.xlsx`  
  - `subjectwise_pass_percentage.xlsx`  
  - `student_summary.xlsx`  

---

### 2. Student Progress Reports (PDF) (`S2PythonProgressPDF.ipynb`)
- Reads internal marks (series & assignments) from Excel.  
- Calculates averages (series, assignments, internal).  
- Generates **individual PDF reports** for each student with:  
  - Tabular summary of marks.  
  - **Performance graphs** (bar charts of series & assignment scores).  
- Saves reports in `Student_Reports/` directory.  

---

### 3. Track Record Analysis (`Trackrecord.ipynb`)
- Processes Excel files with **multi-row headers** (semester results).  
- Tracks **back papers** (arrears) per student across semesters.  
- Creates **per-student bar charts** (PNG) showing progress over semesters.  
- Highlights **total back papers** for easy academic monitoring.  
- Saves reports in `track_record/` directory.  

---

### 4. Academic Results (Openpyxl) (`AcadamicProjects.ipynb`)
- Uses **OpenPyXL** + Pandas for Excel automation.  
- Computes **result percentages** and generates structured output files.  
- Demonstrates programmatic Excel handling & reporting for academic data.  

---

## ⚙️ Tech Stack
- **Python**  
- **Libraries**: Pandas, OpenPyXL, Matplotlib, NumPy  
- **Outputs**: Excel reports, PDF reports, PNG charts  

---

## 🚀 How to Run
1. Clone this repository:  
   ```bash
   git clone https://github.com/ameentrivandrum/StudentPerformanceAnalytics.git
   cd StudentPerformanceAnalytics
# 2. Install required packages
pip install pandas openpyxl matplotlib numpy

# 3. Open the notebooks
# Open the `.ipynb` files in Jupyter Notebook or VS Code and run the cells

# 4. Place input Excel files
# All input Excel files should be in the same directory as the notebooks

# 5. Check outputs
# The generated outputs (Excel, PDF, PNG) will be saved automatically in their respective folders
