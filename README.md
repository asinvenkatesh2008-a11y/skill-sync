# 🔄 Skill Sync

### AI-Powered Workforce Decision & Resource Allocation System

Skill Sync is an intelligent workforce management system designed to help managers make better resource allocation decisions. It analyzes employee skills, experience, availability, workload, and project requirements to recommend suitable employees for projects while identifying potential workforce and project risks.

The system brings workforce information, project intelligence, allocation recommendations, risk monitoring, and analytics together in a single interactive dashboard.

---

## 🚀 Key Features

### 🏠 Command Center
Provides a centralized overview of the organization’s workforce and projects.

- Total employee count
- Active project count
- Workforce utilization
- Projects at risk
- Priority alerts
- JARVIS recommendations
- Workforce command interface

### 👥 Workforce Intelligence
Provides detailed employee information required for effective resource planning.

- Employee ID and name
- Skills
- Experience
- Availability
- Current workload
- Employee capacity overview

### 📁 Project Intelligence
Displays important project requirements and current project status.

- Project name
- Required skills
- Project priority
- Deadline
- Progress percentage
- Required number of employees

### 🧠 AI Resource Allocation
Helps managers identify suitable employees for a selected project.

The system considers:

- Required project skills
- Employee skill matching
- Employee availability
- Current workload
- Number of employees required

It also provides a clear explanation of the generated recommendation.

### ⚠️ Risk & Alerts
Monitors workforce and project conditions to highlight potential risks.

It identifies:

- Highly utilized employees
- Approaching project deadlines
- Projects with low progress
- High-priority projects requiring attention
- Potential resource shortages

### 📊 Workforce Visualization
Provides interactive visual analysis of workforce and project data.

Available visualizations include:

- Bar charts
- Line charts
- Pie charts
- Scatter charts

The module can visualize employee workload, project progress, employee availability, and project priorities.

### 📄 Reports
Provides a summarized workforce report containing:

- Workforce statistics
- Project status
- Employee status
- Overload information
- Project risk information
- JARVIS management recommendations

---

## 🏗️ System Architecture

```text
                 ┌───────────────────────┐
                 │       Manager         │
                 └───────────┬───────────┘
                             │
                             ▼
                 ┌───────────────────────┐
                 │   Skill Sync UI       │
                 │     Streamlit         │
                 └───────────┬───────────┘
                             │
             ┌───────────────┼────────────────┐
             ▼               ▼                ▼
      ┌─────────────┐ ┌──────────────┐ ┌──────────────┐
      │ Workforce   │ │   Projects   │ │   Commands   │
      │    Data     │ │     Data     │ │  from User   │
      └──────┬──────┘ └──────┬───────┘ └──────┬───────┘
             │               │                │
             └───────────────┼────────────────┘
                             ▼
                 ┌───────────────────────┐
                 │  Decision & Allocation │
                 │       Engine           │
                 └───────────┬───────────┘
                             │
             ┌───────────────┼────────────────┐
             ▼               ▼                ▼
      ┌─────────────┐ ┌──────────────┐ ┌──────────────┐
      │    Skill    │ │  Workload &  │ │ Project Risk │
      │   Matching  │ │ Availability │ │   Analysis   │
      └─────────────┘ └──────────────┘ └──────────────┘
                             │
                             ▼
                 ┌───────────────────────┐
                 │ Recommendations &     │
                 │ Decision Insights     │
                 └───────────────────────┘
