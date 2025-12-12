# FedEx-Logistics-Optimization-using-SQL
This project analyzes FedEx’s global logistics data using SQL to identify delivery delays, inefficient routes, warehouse bottlenecks, and agent performance issues. The goal is to provide clear, data-driven insights that improve delivery speed, route planning, and operational efficiency.

Tech Stack

SQL Workbench / MySQL

Data Cleaning and ETL

CTEs, Window Functions, Ranking Functions

KPI Reporting and Performance Metrics

Project Objectives

Find patterns in delivery delays

Analyse route efficiency and transit time

Assess warehouse utilization and performance

Evaluate delivery agent performance

Build KPIs for operational decision-making

Tasks and Key Insights
1. Data Cleaning

Removed duplicate records

Replaced null delay values using route-wise averages

Standardized date formats

Validated foreign key relationships

2. Delivery Delay Analysis

Major delayed routes include Dubai–Shanghai and Singapore–Hong Kong

Some warehouses show extremely high delays (170–205 hours)

Express deliveries had higher delays than Standard

3. Route Efficiency

Calculated distance vs transit time efficiency

Singapore → Hong Kong identified as the least efficient route

Over 90% of shipments delayed on certain global routes

4. Warehouse Performance

Warehouses in Shanghai, London, and Amsterdam have the highest delays

On-time delivery rates are very low (2–10%)

Network delays show system-level operational issues

5. Agent Performance

No agent met the 85% on-time delivery standard

Top agents performed better despite less experience

Recommended training and workload adjustments

6. Shipment Tracking

89% of shipments delivered successfully

Highest undelivered shipments found on specific routes

Traffic, weather, and technical issues are the main delay reasons

7. KPI Reporting

Highest delay countries: UAE, Turkey, China, Singapore, UK

Overall on-time delivery is 9.21%

Worst delay routes: R002, R007, R020

Warehouse utilization is very low (3–11%)

Recommendations

Redesign congested routes

Improve warehouse workload distribution

Provide agent training and optimize assignments

Create automated delay alerts

Use predictive routing to avoid slow hubs

Conclusion

This SQL project provides a full analysis of FedEx’s logistics performance. It highlights major delay causes, route inefficiencies, warehouse issues, and agent performance gaps, and offers solutions to enhance operational efficiency and customer experience.
