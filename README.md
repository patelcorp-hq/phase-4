# Phase 3: Monitoring Basics

Prometheus metrics, Grafana dashboards, and structured logging.

## What's Here

- Prometheus metrics exporter
- Core metrics: swaps processed, slots processed, last slot, uptime
- Grafana dashboard configuration
- Structured logging with rotation
- Docker compose setup for monitoring stack

## Status

- Prometheus running and scraping metrics
- Grafana dashboard accessible at MSI_IP:3000
- Key panels: swaps per minute, last processed slot, process uptime
- Logging to both console and rotating files
- Progress logs every 10K slots
- All errors logged with full context
