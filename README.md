# employee_portal
To design a Power BI Dashboard that provides management with insights into employee performance, attendance, salary, and leave trends, using data from the Employees Employee Portal.

🧩 Employee Portal Power BI Dashboard
📘 Project Overview
This Power BI project is based on the MSEDCL Employee Portal Domain, designed to provide management with actionable insights into employee performance, attendance, salary, and leave trends.
The dashboard integrates data from multiple modules within the Employee Portal to present a unified, interactive view of HR and administrative metrics.
________________________________________
🎯 Objective
To design and develop a Power BI Dashboard that helps management and HR teams monitor employee-related KPIs and make data-driven decisions efficiently.
________________________________________
🏗️ Project Architecture
🔹 Data Sources
Data was collected from SQL Server / Excel exports of various modules:
•	Employee_Master
•	Salary_Slip
•	Leave_Record
•	Allowance_Details
•	Mediclaim_Request
•	Transfer_Request
•	Seniority_List
________________________________________
🔧 Task 1: Data Connection and Transformation
Goal: Connect to the Employee Portal database and prepare data for reporting.
Steps:
•	Connected Power BI to SQL Server using DirectQuery or Import Mode.
•	Cleaned data using Power Query Editor:
o	Removed null and duplicate records.
o	Split employee full name into first/last name.
o	Changed date columns to proper data types.
o	Merged related tables (e.g., Salary with Employee_Master).
•	Created calculated columns:
•	Total_Salary = Basic + Allowance - Deductions
•	Leave_Balance = Total_Leaves - Leaves_Taken
✅ Result: A clean and consistent dataset representing each employee’s full record.
________________________________________
📊 Task 2: Dashboard Design with Meaningful KPIs and Visuals
Goal: Build an interactive and insightful HR & Admin dashboard.
KPIs
•	👩‍💼 Total Employees
•	💰 Total Salary Expense
•	🏖️ Average Leave Taken
•	💊 Total Mediclaim Amount
•	📱 Mobile Claims Processed
Visuals Used
Visual Type	Purpose
Bar Chart	Department-wise employee count
Pie Chart	Employee distribution by designation
Line Chart	Monthly salary trend
Card Visuals	KPI display
Matrix Table	Employee-wise salary and attendance
Slicers	Department, Designation, Year, Location
✅ Result: A one-page HR dashboard offering clear insights for management decisions.
________________________________________
🔐 Task 3: Row-Level Security (RLS)
Goal: Ensure data confidentiality by restricting visibility.
Implementation:
•	Created roles in Power BI Desktop:
o	HR_Manager: View all data.
o	Department_Head: Filtered by their department.
•	Tested roles using “View as Role”.
•	Assigned users to roles in Power BI Service.
✅ Result: Secure access based on user role.
________________________________________
🔄 Task 4: Data Refresh Automation
Goal: Automate data updates using the On-premises Data Gateway.
Steps:
•	Installed and configured the Power BI Gateway.
•	Linked dataset with gateway in Power BI Service.
•	Scheduled daily refresh at 7 AM.
✅ Result: Always up-to-date reports without manual effort.
________________________________________
☁️ Task 5: Publishing and Sharing
Goal: Deploy reports for management and HR.
Steps:
•	Published to Employee_Portal_Workspace.
•	Created dashboard by pinning key visuals.
•	Shared access via Power BI Service roles:
o	Admin: HR Head
o	Member: Department Heads
o	Viewer: Executives
•	Integrated dashboard with Microsoft Teams for easy access.
✅ Result: Seamless sharing and collaboration.
________________________________________
🗣️ Task 6: Presentation Script (2–3 Minutes)
“My Power BI project is based on the Employee Portal domain.
I connected Power BI to SQL Server tables like Employee Master, Salary Slip, and Leave Record.
After cleaning and merging the data, I created KPIs and visuals showing total employees, salary, and leave trends.
I implemented Row-Level Security for departmental data privacy and set up automated data refresh via gateway.
Finally, I published and shared the dashboard with HR and management through Power BI Service and Teams.
This project demonstrates end-to-end Power BI implementation — from data connection to deployment.”
________________________________________
👨‍💻 Developer
Ashish Sangeetrao Ingle
Power BI | Data Analytics | SQL | DAX
________________________________________
📫 Contact
•	Email: [ashishingletwo@gmail.com]
•	LinkedIn: [www.linkedin.com/in/ashish-ingle-554177397]
•	GitHub: [https://github.com/ashishingletwo-art]
