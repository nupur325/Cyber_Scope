# Cyber_Scope
Security Telemetry Health & Visibility Analytics

A security analytics platform for assessing telemetry health, identifying monitoring gaps, and detecting unusual patterns in security log data.

Project Status: Planning & Initial Development

1. About the Project

Security Telemetry Health & Visibility Analytics aims to help security teams assess the reliability and consistency of security telemetry collected from their systems.

Security telemetry includes authentication logs, system events, and network activity records. Missing logs, delayed data, inactive sources, and unusual changes in log volume can create gaps in security monitoring.

This project focuses on analyzing uploaded telemetry data, identifying potential issues, and presenting insights through an interactive dashboard.


2. Problem Statement
Organizations rely on security logs to monitor their IT environments. However, logging sources may become inactive, records may contain missing or invalid information, and unexpected delays or drops in log volume may go unnoticed.

These issues can reduce an organization's security visibility. The project aims to identify such telemetry-related problems and help security analysts understand potential monitoring gaps.


3. Project Objectives
1. Analyze uploaded security telemetry data.
2. Identify missing fields and invalid timestamps.
3. Detect delayed logs and inactive telemetry sources.
4. Identify unusual log-volume spikes and drops.
5. Highlight potential security visibility gaps.
6. Present findings through visualizations and reports.


4. Key Features
The project is organized into four core modules:

1. Authentication & Access Management
User registration and login.
Google authentication.
Secure access to application features.

2. Telemetry Data Ingestion & Quality Analysis
Upload CSV and JSON telemetry files.
Validate and parse uploaded data.
Identify missing fields and timestamp inconsistencies.
Detect delayed logs and inactive sources.

3. Anomaly Detection & Visibility Analysis
Analyze log-volume patterns.
Detect unusual spikes and drops.
Identify irregular telemetry behavior.
Highlight potential monitoring gaps.

4. Dashboard & Reporting
Display telemetry health summaries.
Visualize data quality issues and anomalies.
Filter analysis results.
Generate and export reports.

5. System Workflow
User authentication.
Upload security telemetry data.
Validate and parse uploaded files.
Perform data quality analysis.
Detect unusual telemetry patterns.
Identify potential visibility gaps.
Display results through the dashboard.
Generate and export reports.

6. Proposed Technology Stack

Frontend -      React.js, Vite

UI -            HTML5, CSS3

Backend -       Python (FastAPI / Flask – to be finalized)

Database -      PostgreSQL

ORM -           SQLAlchemy

Data Processing - Pandas, NumPy

Visualization-  Recharts

Machine Learning -Scikit-learn

The technology stack is subject to finalization during development.


7. Future Scope
1. Real-time security telemetry monitoring.
2. Integration with SIEM and log-management platforms.
3. Advanced time-series anomaly detection.
4. Asset inventory and criticality analysis.
5. Automated recommendations for resolving telemetry issues.
6. Investigation and alert management.


8. Scope & Limitations
The initial version focuses on file-based telemetry ingestion and analysis. The accuracy of findings depends on the quality, completeness, and time coverage of the uploaded data.

The system identifies potential telemetry and monitoring issues; it does not independently confirm cyberattacks or replace existing security monitoring platforms.

Live log streaming and direct SIEM integration are outside the initial implementation scope.


9. Contributors
Academic Group Project – Team of Two.

Nupur Khade - 2601098

Shivam Jaiswal - 2601081

Project: Security Telemetry Health & Visibility Analytics
Domain: Cybersecurity | Data Analytics | Machine Learning
