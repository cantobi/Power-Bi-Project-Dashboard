# Power-Bi-Project-Dashboard
Roadmap to Safety: NYC Traffic Collision Analytics Dashboard

-- Description

An interactive, enterprise-grade Power BI dashboard that transforms 75,000 raw city incident logs into a cohesive data story. This project analyzes New York City's 2020 traffic collision data to uncover geographic bottlenecks, behavioral triggers, and time-based risk patterns. It features a fully custom SaaS-style user interface designed to help urban planners and logistics managers drive data-backed safety initiatives.

-- Tech Stack & Power BI Architecture

Power Query (ETL): Conducted extensive data cleaning, handled missing values, filtered out data anomalies (ensuring clean data hygiene for NYC's 5 core boroughs), and optimized data types for performance.

Data Modeling: Established a robust Star Schema model, decoupling fact tables from dimension tables (Calendar, Geography, and Vehicle Types) to ensure lightning-fast report interactivity.

DAX (Data Analysis Expressions): Formulated custom measures for advanced KPI tracking, including dynamic daily averages, injury-to-fatality ratios, and time-based rolling metrics.

UI/UX Design: Implemented a modern, corporate Slate palette (#1E293B) with a persistent left navigation panel, dynamic page bookmarks, conditional formatting, and custom tooltips.

Custom Visuals: Integrated advanced visual components like an interactive timeline slicer to seamlessly filter multi-month trends.

-- Project Goals

Bridge Data and Action: Translate overwhelming municipal accident logs into clear, executive-level insights that can influence public safety policy.

Optimize Visual Hierarchy: Demonstrate elite dashboard design principles—balancing clean data-to-ink ratios with intuitive, accessible layout structures.

Isolate High-Risk Vulnerabilities: Drill down past surface-level metrics to pinpoint exactly who is at risk, where they are at risk, and why.

-- Business Questions Answered by This Dashboard

How did the 2020 pandemic affect traffic safety?

The dashboard features a time-series analysis with a historical marker tracking the immediate, drastic drop in daily accidents the moment the COVID-19 lockdown officially began.

When are the most dangerous windows for drivers and pedestrians?

Using a matrix heatmap, the report isolates the exact hour-of-day and day-of-week combinations, proving that Friday afternoons between 16:00 and 18:00 experience the highest density of accidents.

Which boroughs and road users require the most immediate infrastructure support?

The project breaks down total incidents by the 5 official NYC boroughs and segments the victims into motorists, cyclists, and pedestrians to highlight localized risk factors.

What are the primary behavioral drivers behind severe accidents?

The analysis categorizes the contributing human factors, revealing that "Driver Inattention" dominates total collisions, while "Unsafe Speed" is the leading cause of fatal incidents.



demo
https://github.com/cantobi/Power-Bi-Project-Dashboard/blob/main/Overview%20of%20NYC%20crash.png
