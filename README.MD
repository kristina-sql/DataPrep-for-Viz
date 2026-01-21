
![Strava](assets/images/strava.png)

# Strava Analytics Platform

This repository contains an end-to-end data analytics project built on top of data extracted from the Strava API.

The main goal of this project is:
- **Personal performance analysis** of sports activities (initially focused on virtual cycling)
- **Showcasing data analytics and engineering skills**, including data ingestion, transformation, modeling, and visualization

While the current implementation focuses on **virtual cycling activities**, the project is intentionally designed to be scalable. In the future, it may include:
- Other cycling activity types
- Running and workouts
- Broader fitness and training analytics

---

## Project Vision

The long-term vision is to build a small but realistic analytics platform that follows modern data practices:
- API-based data ingestion
- Structured raw and analytics layers (stg,int,marts)
- Star-schema data modeling (dim and fact tables)
- Automated data pipelines ()
- Business-friendly visualization (Tableau, PowerBI, Looker, Streamlit)

This repository also serves as a space to **experiment, learn, and exchange ideas** around data developement approaches, tooling choices, and analytics best practices.

---

## Architecture (planned)

trava API
↓
Python (Ingestion)
↓
PostgreSQL (Raw & Analytics layers)
↓
dbt (Transformations & Modeling)
↓
Tableau (Visualization)

---

## Tech Stack

- Python (API ingestion)
- PostgreSQL
- dbt
- Tableau Public
- Git & GitHub

---

## Repository Structure

strava-analytics-platform/
├── ingestion/ # Strava API ingestion (Python)
├── transformations/ # dbt models (planned)
├── visualization/ # Tableau assets (planned)
└── README.md

---

## Project Status

🚧 **Work in progress**

Currently implemented:
- Initial Strava API ingestion logic
- Project and repository structure

Planned next steps:
- Load raw data into PostgreSQL
- Build staging and analytics models using dbt
- Implement star schema (fact & dimension tables)
- Create Tableau dashboards
- Add basic automation for data refresh