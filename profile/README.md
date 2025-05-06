<a href="https://glassflow.dev">
  <img alt="GlassFlow Logo" src="https://raw.githubusercontent.com/glassflow/clickhouse-etl/main/docs/assets/glassfow-banner.jpg">
</a>
<p align="center">
<a href="https://hub.docker.com/u/glassflow" target="_blank">
<img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white">
</a>
<a href="https://github.com/glassflow/clickhouse-etl" target="_blank">
<img alt="GitHub" src="https://img.shields.io/badge/glassflow/clickhouse--etl-181717?logo=github&logoColor=white">
</a>
<a href="https://www.linkedin.com/company/glassflow-dev" target="_blank">
<img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white">
</a>
<a href="https://twitter.com/glassflowdev" target="_blank">
<img alt="Twitter" src="https://img.shields.io/badge/Twitter-1DA1F2?logo=twitter&logoColor=white">
</a>


# GlassFlow Overview
GlassFlow for ClickHouse Streaming ETL is a real-time stream processor designed to simplify data pipeline creation and management between Kafka and ClickHouse. It provides a powerful, user-friendly interface for building and managing real-time data pipelines with built-in support for deduplication and temporal joins.

Built specifically for data engineers, GlassFlow handles late-arriving events, ensures exactly-once correctness, and scales with high-throughput data. It delivers accurate, low-latency results from streaming data without compromising simplicity or performance. The tool's intuitive web interface makes it easy to configure and monitor pipelines, while its robust architecture ensures reliable data processing.


## Key Features

- **Streaming Deduplication**: 
  - Real-time deduplication of Kafka streams before ingestion into ClickHouse
  - Configurable time windows up to 7 days for deduplication
  - Simple configuration of deduplication keys and time windows
  - One-click setup for deduplicated data pipelines
  - Prevents duplicate data from reaching ClickHouse

- **Temporal Stream Joins**:
  - Join two Kafka streams in real-time
  - Configurable time windows up to 7 days for stream joins
  - Configure join keys and time windows through the UI
  - Simplified join setup process
  - Produce joined streams ready for ClickHouse ingestion

- **Built-in Kafka Connector**:  
  - Automatic data extraction from Kafka topics
  - Seamless integration with Kafka clusters
  - No manual data pulling required
  - Supports multiple Kafka topics and partitions
  - Native support for JSON data types

- **Optimized ClickHouse Sink**:
  - Native ClickHouse connection for maximum performance
  - Configurable batch sizes for efficient data ingestion
  - Adjustable wait times for optimal throughput
  - Built-in retry mechanisms
  - Automatic schema detection and management
  - Full support for JSON data types in ClickHouse

- **User-Friendly Interface**: Web-based UI for pipeline configuration and management
- **Local Development**: Includes demo setup with local Kafka and ClickHouse instances
- **Docker Support**: Easy deployment using Docker and docker-compose
- **Self-Hosted**: Open-source solution that can be self-hosted in your infrastructure

## Getting Started

To get started with GlassFlow, visit our main repository at [glassflow/clickhouse-etl](https://github.com/glassflow/clickhouse-etl). The repository contains:

- Complete documentation
- Quick start guide
- Example configurations
- Docker setup instructions
- API documentation

Clone the repository to get started:
```bash
git clone https://github.com/glassflow/clickhouse-etl.git
```