# QA & UAT Test Automation Analytics

This project demonstrates a mock QA and UAT test case automation and reporting workflow, using simulated data to showcase analysis, visualization, and insights. It highlights how test execution, status, priority, module performance, and tester activity can be tracked and analyzed for effective QA and UAT management.
## **Folder Structure**
QA_Test_Automation_Analytics

-data/ → Mock CSV/Excel datasets
-notebooks/ → Jupyter notebooks (.ipynb)
-scripts/ → Reusable Python scripts (.py)
-visualizations/ → PNG/JPG/HTML charts
-README.md → Project description
## **Dataset**
- 120 mock test cases with fields:
  - `TestCaseID`, `Name`, `Module`, `Status`, `Priority`, `ExecutedBy`, `ExecutionDate`
- Stored in `/data/mock_test_cases.csv`
- Covers both **QA test execution** and **UAT-like module validation**
## **Key Analysis & Visualizations**
1. **Test Case Status Distribution**  
   - Bar chart showing counts of Pass, Fail, Blocked, and Skipped test cases  
   - Table shows exact counts  
   - **UAT Relevance:** Shows how well each module meets acceptance criteria
2. **Test Case Priority Distribution**  
   - Bar chart of High, Medium, Low priority test cases  
   - Table shows counts per priority  
   - **UAT Relevance:** Highlights high-priority user workflows that may require attention
3. **Module-wise Status Analysis**  
   - Status breakdown for each module (Dashboard, Login, Payment, Reporting, User Management)  
   - **UAT Relevance:** Simulates acceptance testing per business module
4. **Tester-wise Execution Count**  
   - Bar chart showing number of test cases executed by each tester  
   - Table shows counts per tester  
   - **UAT Relevance:** Tracks user/tester coverage for UAT cycles
5. **Execution Trend Over Time**  
   - Line chart showing number of test cases executed per day  
   - Table shows daily counts  
   - **UAT Relevance:** Provides trend of UAT test execution and progress
6. **Advanced Visualizations**
   - Priority vs Status (Stacked Bar): Identifies critical failing workflows  
   - Pass Rate per Module: Measures module acceptance quality  
   - Failures by Priority: Pinpoints high-priority issues needing remediation
## **Overall Summary**
**Data Analysis Key Findings**  
- Status overview highlights QA health and module acceptance.  
- Priority breakdown identifies high-risk workflows in UAT context.  
- Module-wise analysis identifies modules with higher failure or blocked rates.  
- Tester performance reveals coverage and workload distribution.  
- Execution trend shows testing patterns and completion rate over time.  
- Advanced visuals provide deeper insights into QA and UAT quality metrics.

**Insights & Next Steps**  
- Focus on high-risk modules and high-priority workflows.  
- Optimize tester workload for efficient UAT coverage.  
- Use execution trends to plan UAT cycles and track progress.  
- Include module pass rates and failure breakdowns in dashboards for management.  
- Track QA and UAT metrics across cycles to monitor improvements and persistent issues.
## **Tools Used**
- Python (Pandas, Matplotlib, Seaborn)  
- Jupyter Notebook  
- CSV for mock datasets  
- PNG/JPG for visualizations
## **Disclaimer**

This project uses **simulated data only**. No real customer or sensitive information is included. It is intended for educational and portfolio purposes.

---
