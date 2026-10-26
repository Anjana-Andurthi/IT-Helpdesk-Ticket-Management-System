# 🎫 IT Helpdesk Ticket Management System

## 📌 Project Overview

The **IT Helpdesk Ticket Management System** is a Python-based application designed to manage IT support requests within an organization. Employees can raise tickets for technical issues, while support agents can manage assignments, track progress, and resolve reported problems.

The system helps administrators monitor support operations through ticket dashboards and SQL-based analytical reports, including agent workload, department-wise ticket distribution, recurring issues, and Service Level Agreement (SLA) performance.

## 🎯 Objectives

- Simplify IT issue reporting and tracking.
- Organize ticket assignment and resolution workflows.
- Monitor ticket status, priority, and resolution progress.
- Analyze support team performance using SQL.
- Provide administrators with meaningful reports for decision-making.

## 🚀 Key Features

### 1. Ticket Management
- Create and manage IT support tickets.
- Track ticket status through the resolution lifecycle.
- Maintain ticket details, priority, and issue descriptions.

### 2. Ticket Assignment and Resolution
- Assign tickets to support agents.
- Track ticket progress and resolution.
- Support ticket lifecycle stages such as Open, Assigned, In Progress, Resolved, and Closed.

### 3. Agent and Department Management
- Organize support agents and departments.
- Monitor ticket distribution across agents.
- Analyze support requests by department.

### 4. SQL Analytics and Business Intelligence
- Analyze agent workload and ticket assignments.
- Generate department-wise ticket reports.
- Identify recurring technical issues.
- Analyze SLA performance and ticket resolution metrics.
- Use SQL queries to summarize ticket data.

### 5. Dashboard and Reporting
- Display relevant ticket statistics and reports.
- Support administrators in monitoring helpdesk operations.
- Present analytical insights for operational decision-making.

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Python | Application logic and backend processing |
| Streamlit | Interactive web interface |
| MySQL | Relational database |
| SQL | Data retrieval, analysis, and reporting |
| Git | Version control |
| GitHub | Source code hosting and team collaboration |

## 🧩 Project Modules

1. **Authentication Module:** Handles user authentication and access workflows, where implemented.
2. **Ticket Management Module:** Supports ticket creation, assignment, status updates, and resolution.
3. **Agent Management Module:** Supports agent-related operations.
4. **Dashboard Module:** Displays relevant ticket information and statistics.
5. **SQL Analytics and Business Intelligence Module:** Analyzes ticket data, agent workloads, department trends, recurring issues, and SLA metrics.

## 👩‍💻 My Contribution — Member 3

### SQL Analytics and Business Intelligence

My role in this project was **Member 3**, responsible for the SQL Analytics and Business Intelligence module.

I worked on analyzing helpdesk ticket data stored in MySQL and developing SQL-based reports to help administrators understand support operations.

### Responsibilities

- **Agent Workload Analysis:** Analyzed ticket assignments and workload distribution across support agents.
- **Department Analysis:** Worked on department-wise ticket statistics and reporting.
- **Recurring Issue Analysis:** Analyzed ticket data to identify frequently reported technical problems.
- **SLA Analysis:** Worked on SQL analytics related to ticket resolution and SLA performance.
- **SQL Query Development:** Worked with analytical queries to retrieve, group, filter, and summarize ticket data.
- **Analytics Integration:** Contributed to integrating analytical reports with the project's dashboard and reporting modules.
- **Team Collaboration:** Used Git and GitHub branches to collaborate with teammates and integrate project changes.

### Skills Gained

- SQL query writing and data analysis.
- Joins, aggregate functions, grouping, filtering, and analytical queries.
- Relational database concepts.
- Business intelligence and operational reporting.
- Git and GitHub collaboration.
- Understanding of ticket management workflows and SLA monitoring.

## ⚙️ Installation and Setup

### Prerequisites

- Python installed on your system.
- MySQL Server installed and running.
- Git installed.
- A code editor such as VS Code.

### Step 1: Clone the Repository

```bash
git clone https://github.com/Anjana-Andurthi/IT-Helpdesk-Ticket-Management-System.git
```

### Step 2: Navigate to the Project Folder

```bash
cd IT-Helpdesk-Ticket-Management-System
```

### Step 3: Create a Virtual Environment

```bash
python -m venv venv
```

Activate the environment on Windows PowerShell:

```powershell
.\venv\Scripts\Activate.ps1
```

### Step 4: Install Dependencies

If the repository contains a `requirements.txt` file, run:

```bash
python -m pip install -r requirements.txt
```

### Step 5: Configure the Database

1. Start MySQL Server.
2. Create the database required by the application.
3. Configure the database connection using the project's existing configuration.
4. Run any required schema or initialization scripts provided in the repository.

Keep database passwords and other sensitive credentials out of the repository.

### Step 6: Run the Application

For a Streamlit entry point named `app.py`, run:

```bash
streamlit run app.py
```

Use the actual entry-point filename if it differs.

## 📈 Expected Benefits

- Centralized management of IT support tickets.
- Better visibility into ticket assignments and resolution progress.
- Improved monitoring of recurring issues and support workloads.
- Easier analysis of SLA-related performance.
- More informed administrative decisions using ticket data.

## 🔮 Future Enhancements

- Email notifications for ticket assignments and status changes.
- Automated ticket categorization and priority suggestions.
- AI-assisted resolution recommendations.
- Advanced dashboard visualizations.
- Enhanced access controls and audit logging.
- Automated testing and cloud deployment.

## 📂 Repository

GitHub: https://github.com/Anjana-Andurthi/IT-Helpdesk-Ticket-Management-System

## 🤝 Team Project

This application was developed collaboratively. Different team members contributed to different modules, including ticket operations, database functionality, dashboards, and analytics.

My contribution focused on **SQL Analytics and Business Intelligence (Member 3)**.

---

*This project demonstrates practical application of Python, MySQL, SQL analytics, dashboard development, and collaborative software development.*
