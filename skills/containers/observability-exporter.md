# `observability-exporter` OCR Repository

## Overview

`database/observability-exporter` is the Oracle Container Registry repository for Oracle Database Observability Exporter (Metrics, Logs, and Tracing). Oracle lists this repository in the OCR Database business area and publishes both a latest pull command and a tags table for selecting concrete image versions.

## Repository Snapshot

- **Registry path:** `container-registry.oracle.com/database/observability-exporter`
- **OCR short description:** Oracle Database Observability Exporter (Metrics, Logs, and Tracing)
- **Latest pull command shown on OCR:** `docker pull container-registry.oracle.com/database/observability-exporter:2.2.2`
- **License note on OCR:** OCR states that the software in this repository is licensed under the Universal Permissive License (UPL).

## What Oracle Documents Here

- The OCR detail page describes this image as the Unified Observability Exporter for Oracle Database.
- The page says it contains OpenTelemetry exporters for metrics, logs, and tracing.
- OCR also notes that the exporters are configurable for targets such as Prometheus, Promtail/Loki, Jaeger, and Grafana-based observability workflows.

## Oracle Version Notes (19c vs 26ai)

The OCR detail page presents this repository as a tool image with versioned exporter tags, not as a 19c-versus-26ai database image line. Use the OCR tags table to select the exporter release you need.

## Sources

- https://container-registry.oracle.com/ords/ocr/ba/database/observability-exporter
