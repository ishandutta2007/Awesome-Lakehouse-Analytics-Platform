# Awesome-Lakehouse-Analytics-Platform

# Top Lakehouse Analytics Platform Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Open Table Formats, Unified Analytics, Data Lake + Warehouse Capabilities, ACID Transactions & Multi-Engine Querying*
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Lakehouse Analytics**. These systems combine the low-cost, flexible storage of data lakes with the reliability, governance, and performance of data warehouses—typically using open table formats (Iceberg, Delta Lake, Hudi) and supporting SQL, Spark, streaming, and AI workloads on the same data.

**Examples** include Azure Databricks, Databricks, Snowflake, Google Cloud BigLake, AWS Lake Formation, Cloudera Data Platform, Dremio, Starburst Galaxy, Onehouse, and Upsolver (the category leaders).

**Open-source emphasis**: The lakehouse paradigm is built on open standards. **Apache Iceberg**, **Delta Lake**, **Apache Hudi**, **Apache Spark**, **Trino**, and related projects form the core open-source foundation. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Azure Databricks](https://azure.microsoft.com/products/databricks/)**  
  Microsoft’s managed Databricks service on Azure, delivering a full lakehouse platform for engineering, analytics, ML, and AI with Unity Catalog and Delta Lake.

- **[Databricks](https://www.databricks.com/)**  
  The original lakehouse platform combining data engineering, SQL analytics, machine learning, and generative AI on open formats (Delta Lake / Iceberg).

- **[Snowflake](https://www.snowflake.com/)**  
  Cloud data platform with strong lakehouse capabilities, support for open formats, and unified storage/compute for analytics and AI.

- **[Google Cloud BigLake](https://cloud.google.com/biglake)**  
  Google’s lakehouse storage engine that unifies data lakes and warehouses, with support for open table formats and BigQuery integration.

- **[AWS Lake Formation](https://aws.amazon.com/lake-formation/)**  
  AWS service for building, securing, and managing data lakes, often paired with Athena, Redshift, and open table formats for lakehouse architectures.

- **[Cloudera Data Platform](https://www.cloudera.com/)**  
  Enterprise data platform offering open data lakehouse capabilities with hybrid and multi-cloud support.

- **[Dremio](https://www.dremio.com/)**  
  SQL lakehouse platform focused on high-performance querying of data lakes and open formats with self-service analytics.

- **[Starburst Galaxy](https://www.starburst.io/platform/starburst-galaxy/)**  
  Managed Trino-based lakehouse and federated analytics platform supporting Iceberg and multi-source SQL.

- **[Onehouse](https://www.onehouse.ai/)**  
  Lakehouse platform specialized in optimizing open table formats (Hudi, Iceberg, Delta) and continuous data ingestion.

- **[Upsolver](https://www.upsolver.com/)**  
  Data lakehouse platform focused on continuous ingestion, transformation, and preparation of data for analytics on open formats.

## Open-Source GitHub Projects
- **[Apache Iceberg](https://github.com/apache/iceberg)**  
  Leading open table format for huge analytic datasets—brings ACID transactions, schema evolution, and time travel to data lakes, usable by Spark, Trino, Flink, and more.

- **[Delta Lake](https://github.com/delta-io/delta)**  
  Open-source storage layer (Linux Foundation) that brings reliability and ACID transactions to data lakes, tightly integrated with Apache Spark and widely used in lakehouse architectures.

- **[Apache Hudi](https://github.com/apache/hudi)**  
  Open-source data lake platform providing incremental processing, upserts, and efficient change data capture on top of data lakes.

- **[Apache Spark](https://github.com/apache/spark)**  
  The foundational unified analytics engine for large-scale data processing, batch, streaming, SQL, and ML—central to most lakehouse stacks.

- **[Trino](https://github.com/trinodb/trino)**  
  Fast distributed SQL query engine (formerly PrestoSQL) designed for interactive analytics across data lakes and multiple sources.

- **[Apache Flink](https://github.com/apache/flink)**  
  Powerful open-source stream processing framework frequently used for real-time lakehouse ingestion and processing.

- **[Unity Catalog (open-source efforts)](https://github.com/unitycatalog/unitycatalog)**  
  Open governance and catalog initiatives related to multi-engine lakehouse metadata management.

- **[Documentation and Iceberg / Delta / Hudi guides](https://iceberg.apache.org/)**  
  Resources for adopting open table formats, configuring catalogs, and building multi-engine lakehouses.

- **[Lakehouse playground and reference architectures](https://github.com/)**  
  Community repositories demonstrating end-to-end open lakehouse stacks with Spark, Trino, Iceberg, Hudi, and orchestration tools.

- **[dbt + open lakehouse integrations](https://github.com/dbt-labs/dbt-core)**  
  Transformation layer commonly used on top of open lakehouse tables for analytics engineering.

### Additional Strong Open-Source Options
- Building lakehouses on **Apache Iceberg** or **Delta Lake** as the table format.
- Querying with **Trino** or **Spark SQL** against open formats stored in object storage.
- Using **Apache Hudi** for incremental and CDC-heavy workloads.
- Combining **Spark + Flink + Trino** for a multi-engine open lakehouse.
- Accepting that fully managed platforms (Databricks, Snowflake, Dremio Cloud, Starburst Galaxy, Onehouse) still dominate for ease of operations, governance, and enterprise support.
- Focusing open-source efforts on format openness, engine choice, and avoiding proprietary lock-in of storage and compute.

**Frameworks for building custom systems**: Store data in open formats (Iceberg/Delta/Hudi) on object storage → process with Spark/Flink → query with Trino → transform with dbt → catalog and govern with open metadata tools. Suitable for organizations that want full control and multi-engine flexibility. Many teams use commercial lakehouse platforms for operational simplicity while keeping data in open formats.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Lakehouse architectures involve storage costs, compute sizing, and data governance considerations. Open-source stacks require operational expertise. This list is not architecture or cost advice.

---
**Made for data engineers, analytics teams, and open data platform advocates.**
Let's keep analytics flexible, reliable, and as open as practical.
