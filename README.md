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

- **Validating my knowledge:** Demonstrate proficiency in setting up and configuring Prometheus and Grafana for real-time monitoring and data visualization.
- **Monitoring key metrics:** Track crucial metrics such as website availability, response times, and user activity on major airline websites.
- **Visualizing data:** Create an informative Grafana dashboard that presents real-time and historical data in an easily interpretable format.
- **Identifying Patterns: (Optional)** Analyze the data collected to identify patterns such as peak usage hours, and understand how these patterns relate to real-life situations.

## Milestones
- **Phase 1: Initial setup [COMPLETE]**
  - Set up a basic Prometheus server + configure Prometheus to scrape metrics from selected airline websites (see `prometheus.yaml`).
  - Verify that metrics are being collected and stored correctly.

- **Phase 2: Grafana integration [COMPLETE]**
  - Set up Grafana and manually connect it to the Prometheus data source.
  - Create initial dashboards to visualize basic metrics.

- **Phase 3: Automate Grafana dashboard provisioning + fine-tune dashboards [IN PROGRESS]**
  - Configure Grafana provisioning of Prometheus data source and dashboards.
  - Update dashboards to display key metrics.


## References
- [Prometheus Blackbox Exporter](https://github.com/prometheus/blackbox_exporter)
- [Understanding and using the multi-target exporter pattern](https://prometheus.io/docs/guides/multi-target-exporter/)
- [Provision Grafana](https://grafana.com/docs/grafana/latest/administration/provisioning/)