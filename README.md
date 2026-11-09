# -Alisalud-growth-intelligence-engine

Business Context: 
ALISALUD.org offers BPM training courses and certificates. One of these courses is offered at a subsidized social price because its mission is to make food safety best practices accessible to people and businesses throughout Peru.

The initiative aims to promote food safety awareness nationwide, contributing to Sustainable Development Goal 3 (SDG 3): Good Health and Well-being.


The Business Challenge:

How can ALISALUD.org understand its customer acquisition process, identify conversion bottlenecks, and make data-driven decisions to scale its educational services?

The goal is to build a data pipeline using Python, Snowflake, and dbt to analyze BPM certificate purchases and identify new customers every day.

My Responsibility:

My responsibility was to design and implement an end-to-end data solution to provide business visibility into customer acquisition and certificate sales.

The solution needed to:

Identify new customers and track BPM certificate purchases daily.

Measure customer acquisition and conversion performance.

Provide reliable, structured data to support business decisions.

The main objective was to transform operational data into actionable business insights while building a scalable and maintainable data pipeline.


Proposed Architecture

Moodle / MariaDB => Python => Snowflake => dbt / SQL => Analytical Models => New Customers
An experience of how data can be transformed into useful business insights.

Phase 1: Ingestion (Python to Snowflake Raw)
The source database in hosted in a shared enviroment (cpanel) and we successfully resolved the access issue: 
   ***Secure Connection  SSH Tunnel***.- To avoid exposing the Database to the internet we estabilished and SSH tunnel using Python scripts.
   ***Enviroment Restrictions*** The cPanel terminal was disabled, so we used Cron Jobs to install dependencies and excute on-time commands and redirecting the output to log files for auditing purposes.

Expected Results

The main KPI is New Customers.

The Growth Intelligence Engine is currently under development. The expected outcome is to establish a reliable data pipeline that enables ALISALUD.org to identify new customers daily and monitor customer acquisition performance.

This will provide a data-driven foundation to identify growth opportunities and support business decisions.

Current Status: Development in progress.
   


