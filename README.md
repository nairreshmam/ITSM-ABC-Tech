# ITSM-ABC-Tech
Python, Machine learning, Numpy, Pandas, Matplotlib, Seaborn , Scikit learn, Jupyter Notebook

**Overview:**

This project explores how machine learning (ML) can enhance IT Service Management (ITSM) processes at ABC Tech, a mid-sized organization with mature ITIL practices. Despite their advanced ITSM processes, customer feedback has revealed shortcomings in incident management. By leveraging ML, this project aims to address critical areas such as predicting high-priority tickets, forecasting incident volumes, auto-tagging tickets, and predicting ITSM asset misconfigurations.

**PROBLEM STATEMENT:**

- **Predicting High Priority Tickets:** To predict priority 1 & 2 tickets, so that they can take preventive measures or fix the problem before it surfaces.
- **Forecast the incident volume** in different fields , quarterly and annual. So that they can be better prepared with resources and technology planning.
- **Auto tag the tickets** with right priorities and right departments so that reassigning and related delay can be reduced.
- **Predict RFC** (Request for change) and possible failure / misconfiguration of ITSM assets.

**Features:**
- Data extraction from a MySQL database containing over 46,000 records (2012–2014).
- Comprehensive exploratory data analysis (EDA).
- Development of predictive models for incident management improvements.
- Visualizations and dashboards for actionable insights.

**Dataset:**
**Details:**
- **Source:** ABC Tech's internal MySQL database.
- **Records:** 46,000 records spanning three years (2012–2014).
- **Key Fields:**
  - Incident details (ID, status, impact, urgency, priority).
  - Configuration item data (CI_Name, CI_Cat, CI_Subcat).
  - Timing information (Open_Time, Resolved_Time, Close_Time).
  - Interaction data (number of reassignments, related interactions/incidents/changes).
  - Closure codes and handling time.
 
**Project Workflow:**
**1. Data Collection:**
  - Establish connection to the MySQL database.
  - Extract and load data into Pandas DataFrames.
**2. Data Preprocessing:**
  - Handle missing values.
  - Encode categorical variables.
  - Normalize numerical fields.
**3. Exploratory Data Analysis (EDA):**
 - Analyze key trends (incident priority, handling time, reassignments).
 - Visualize distributions and relationships using plots.
**4. Model Training:**
  - Develop ML models for ticket classification and incident forecasting.
  - Evaluate models using accuracy, precision, recall, and F1 score.

**Comparsion of ROC AUC Score and F1 Score for Predicting High Priority Ticket:**

![image](https://github.com/user-attachments/assets/33b55d95-0a45-4890-afbd-5fafc8c6c341)

**Forecast the incident volume and Auto Tag Tickets:**

![image](https://github.com/user-attachments/assets/6a656405-a06c-48d3-a2f6-4eb67a157909)

**Comparsion of ROC AUC Score and F1 Score for Predict RFC:**

![image](https://github.com/user-attachments/assets/423de214-400d-40cd-b8f6-d1331f608665)

**Conclusion:**

- **Predictive Insights:** Predicting high-priority tickets allows the organization to take preventive measures, improving incident response and reducing downtime.
- **Resource Optimization:** Forecasting incident volumes quarterly and annually helps in better resource and capacity planning, ensuring readiness for future demands.
- **Automation Benefits:** Auto-tagging tickets with correct priorities and departments minimizes delays, streamlines ticket handling, and enhances overall process          
  efficiency.
- **Risk Mitigation:** Predicting RFC failures reduces misconfigurations and ensures smoother IT changes, safeguarding the reliability of IT systems.
- Impact These enhancements lead to improved operational efficiency, faster resolution times, and reduced risks, making ABC Tech more agile and better equipped to handle IT   challenges.
- The ITSM project for ABC Tech successfully demonstrates how machine learning can enhance IT operations by predicting high-priority tickets, forecasting incident volumes,    automating ticket tagging, and mitigating risks in RFCs.

**These improvements streamline processes, optimize resources, and reduce downtime, making the organization more efficient and proactive in managing IT challenges.**



