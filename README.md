# iCOR Analytics Database

A relational database project designed to support iCOR Phase 1 analytics by storing and organising information about organisations, users, audits, compliance checks, tasks, and predictive model performance.

## Features
- **Organisation Management:** Stores organisation details.
- **User Management:** Records users, departments, roles, and tenure.
- **Audit Management:** Stores audit types, complexity, and dates.
- **Compliance Monitoring:** Records compliance results and identifies at-risk areas.
- **Task Management:** Tracks task assignments, priorities, deadlines, and completion.
- **Model Metrics:** Stores predictive model performance measurements.
- **Relational Design:** Connects related data using primary and foreign keys.

## Project Structure
- `/database/` — database tables and SQL schema.
- `/queries/` — SQL queries for retrieving and analysing information.
- `/reports/` — database reports and analytical outputs.
- `/forms/` — forms for entering and viewing data.
- `/tests/` — database testing and validation.

## Database
The database contains six main tables:
- `Organisations`
- `Users`
- `Audits`
- `Compliance_Checks`
- `Tasks`
- `Model_Metrics`

These tables are linked through relationships to reduce unnecessary duplication and support efficient data retrieval.

## How to Run
1. Open the database in Microsoft Access.
2. View or enter records using the tables.
3. Run SQL queries to retrieve and analyse information.
4. Use forms and reports to present the results.

## Purpose
This project demonstrates:
- Relational database design
- Primary and foreign keys
- Database relationships
- SQL querying
- Data validation
- Compliance and task analysis
- Audit tracking
- Predictive analytics data management
