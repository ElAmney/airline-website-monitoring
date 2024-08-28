# Airline Website Monitoring

## Overview
This project is dedicated to monitoring the performance and availability of major airline websites using **Prometheus** and **Grafana**. The goal is to gather, analyze, and visualize data to ensure that these websites are operating efficiently and to detect any potential issues that may arise.

## Technologies

- **Prometheus:** For scraping metrics from the airline websites and storing the data.
- **Grafana:** For visualizing the data collected by Prometheus.
- **Docker:** For containerizing the services.

## Background and Motivation

The primary motivation for this project is to validate and demonstrate my knowledge of Grafana and Prometheus. By applying these tools to real-world scenarios such as monitoring websites, I aim to showcase their capabilities in tracking and analyzing critical metrics like website availability, response times, and user activity patterns.

This project also seeks to provide valuable insights into the operational behavior of airline websites and attempt to identify any noticable patterns relating to dynamic pricing. For example, identifying peak usage hours and comparing the prices of a specific flight to understand the scale at which airline ticket pricing works.

## Goals

- **Knowledge Validation:** Demonstrate proficiency in setting up and configuring Prometheus and Grafana for real-time monitoring and data visualization.
- **Monitoring Key Metrics:** Track crucial metrics such as website availability, response times, and user activity on major airline websites.
- **Data Visualization:** Create an informative Grafana dashboard that presents real-time and historical data in an easily interpretable format.
- **Identifying Patterns:** Analyze the data collected to identify patterns such as peak usage hours, and understand how these patterns relate to real-life situations.

## Milestones
- **Phase 1: Initial Setup [COMPLETE]**
  - Set up a basic Prometheus server.
  - Configure Prometheus to scrape metrics from selected airline websites (see `prometheus.yaml`).
  - Verify that metrics are being collected and stored correctly.

- **Phase 2: Grafana Integration [IN PROGRESS]**
  - Set up Grafana and connect it to the Prometheus data source.
  - Create initial dashboards to visualize basic metrics like website uptime and response times.


## References
- [Prometheus Blackbox Exporter](https://github.com/prometheus/blackbox_exporter)
- [Understanding and using the multi-target exporter pattern](https://prometheus.io/docs/guides/multi-target-exporter/)