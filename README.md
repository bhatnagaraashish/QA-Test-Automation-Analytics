# QA-Test-Automation-Analytics
This project demonstrates a mock QA test case automation and reporting workflow, using simulated data to showcase analysis, visualization, and insights. It highlights how test execution, status, priority, module, and tester performance can be tracked and analyzed for effective QA management.

## **Folder Structure**
QA-Test-Automation-Analytics
-data/ → Mock CSV/Excel datasets
-notebooks/ → Jupyter notebooks (.ipynb)
-scripts/ → Reusable Python scripts (.py)
-visualizations/ → PNG/JPG/HTML charts
-README.md → Project description
## **Dataset**
- 120 mock test cases with fields:
  - `TestCaseID`, `Name`, `Module`, `Status`, `Priority`, `ExecutedBy`, `ExecutionDate`
- Stored in `/data/mock_test_cases.csv`
---
## **Key Analysis & Visualizations**

1. **Test Case Status Distribution**
   - Bar chart showing counts of Pass, Fail, Blocked, and Skipped test cases
   - Table shows exact counts
2. **Test Case Priority Distribution**
   - Bar chart of High, Medium, Low priority test cases
   - Table shows counts per priority
3. **Tester-wise Execution Count**
   - Bar chart showing number of test cases executed by each tester
   - Table shows exact counts
4. **Execution Trend Over Time**
   - Line chart showing number of test cases executed per day
   - Table shows daily counts
5. **Priority vs Status (Stacked Bar)**
   - Shows which priority test cases fail most frequently
6. **Pass Rate per Module**
   - Bar chart measuring quality per module

7. **Failures by Priority**
   - Highlights high-priority failing test cases
---
## **Overall Summary**
**Data Analysis Key Findings**  
- Status overview highlights overall QA health.  
- Priority breakdown identifies high-risk areas.  
- Module-wise analysis reveals modules with higher failure or blocked rates.  
- Tester performance identifies workload distribution and potential bottlenecks.  
- Execution trend shows testing patterns and spikes over time.  
- Advanced visuals (Priority vs Status, Pass Rate per Module, Failures by Priority) provide deeper insights into QA quality.

**Insights & Next Steps**  
- Prioritize modules and test cases with high failure or blocked rates.  
- Balance tester workload to improve efficiency.  
- Use execution trends to optimize test scheduling.  
- Include advanced metrics in dashboards for management decision-making.  
- Track metrics over multiple cycles to monitor improvements and persistent issues.
---
## **Tools Used**
- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- CSV for mock datasets
- PNG/JPG for visualizations
---
## **Disclaimer**
This project uses **simulated data only**. No real customer or sensitive information is included. It is intended for educational and portfolio purposes.
