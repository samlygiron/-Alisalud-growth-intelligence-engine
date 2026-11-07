# -Alisalud-growth-intelligence-engine

A Data Engineering Proof of Concept (POC)

About

This project explores how data from Moodle and commercial records can be integrated to generate useful insights for ALISALUD.org.

The goal is to build a data pipeline using Python, Snowflake, and dbt to analyze BPM certificate purchases and identify new customers every day.

Business Objective

Understand who purchases BPM certificates and identify opportunities to attract new customers.

Main KPI: New Customers

A new customer is a person making their first BPM certificate

Data Sources

MariaDB: Moodle database.

Sales records: certificate Issued

Proposed Architecture

Moodle / MariaDB => Python => Snowflake => dbt / SQL => Analytical Models => New Customers
A working and documented proof of concept demonstrating how academic and commercial data can be transformed into useful business insights.
