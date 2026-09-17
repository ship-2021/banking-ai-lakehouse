# ADR-001: Banking Customer 360 Lakehouse Architecture

## Status

Accepted

## Context

The platform needs to process banking customer, account and
transaction data using both batch and real-time ingestion patterns.

The solution should support:

- scalable data processing
- analytical workloads
- historical data
- real-time transaction processing
- data quality
- governance
- future AI/GenAI workloads

## Decision

We will use a modern lakehouse architecture based on:

- Azure Data Lake Storage Gen2
- Azure Databricks
- PySpark
- Delta Lake
- Azure Data Factory
- Azure Event Hubs
- Unity Catalog
- Azure AI services for future GenAI capabilities

The data platform will follow a Bronze, Silver and Gold architecture.

## Expected Benefits

- separation of raw and curated data
- scalable transformation
- batch and streaming support
- data quality controls
- governed analytical datasets
- foundation for AI and GenAI applications
