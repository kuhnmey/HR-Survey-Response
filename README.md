# HR-Survey-Response

---
 
## Overview
 
This report provides an interactive view of HR survey data collected from employees across the organization. It highlights response completeness, departmental breakdowns, and key themes around workplace experience — including expectations, recognition, and team culture.
 
**Tool:** Microsoft Power BI 

**Data source:** Employee Survey — HR Survey Responses 
 
---
 
## Dataset
 
The underlying dataset is the **Employee Survey – HR Survey Responses** table, which contains the following fields:
 
| Field | Description |
|---|---|
| `Question` | Survey question asked of the employee |
| `Response` | Numeric response value |
| `Response Text` | Text label for the response (e.g., Agree, Disagree) |
| `Status` | Completion status of the survey (Complete / Incomplete) |
| `Department` | Employee's department |
| `Director Count` | Count of directors within the department |
| `Manager Count` | Count of managers within the department |
| `Supervisor Count` | Count of supervisors within the department |
 
---
 ## Dashboard
 <img width="973" height="551" alt="HR Survey Dashboard" src="https://github.com/user-attachments/assets/76cc824e-96e5-4290-94d1-00def18d0d3d" />


---

## Report Visuals
 
The single-page report includes the following visuals:
 
- **Pivot Table** — Cross-tabulates survey questions against response text options, with conditional color formatting to highlight response distributions
- **Donut Chart** — Breaks down survey completion status (Complete vs. Incomplete)
- **Table** — Shows department-level breakdown of Directors, Managers, and Supervisors
---
 
## Key Findings
 
- **Total survey responses:** ~14,725
- **Incomplete responses:** 135 employees did not complete the survey
- **Hierarchical structure:** The only department with Directors is *Exec Office & Directors*
- **Positive signals:** Employees generally feel they know what is expected of them at work, and feel that their superiors care about them
- **Areas for improvement:** Employees report insufficient recognition at work and difficulty forming genuine friendships with colleagues
---
 
## Recommendations
 
1. **Follow up on incomplete responses** — Schedule meetings or check-ins with the 135 employees who did not complete the survey to understand any barriers or concerns
2. **Strengthen team bonding** — Create more opportunities for employees to connect outside of work tasks, such as team activities, wellness events, or group travel
