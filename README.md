# Awesome-Multi-Tenant-Data-Governance

# Top Multi-Tenant Data Governance Tools Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Tenant Isolation, Policy Enforcement & Cross-Tenant Data Access Control*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Multi-Tenant Data Governance Tools**. These tools enforce data access policies, isolate tenant data, classify sensitive information, track data lineage, and ensure compliance across shared infrastructure — supporting row-level security, column masking, consent management, and audit trails.

**Examples** include Salesforce Data Spaces, Collibra, Alation, Atlan, Privacera, Immuta, Apache Ranger, BigID, Securiti.ai, and OneTrust Data Governance (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom policy engines, and transparent tenant isolation — ideal for SaaS providers, platform teams, and organizations building data-sovereign governance infrastructure.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Salesforce Data Spaces](https://www.salesforce.com/)**  
  Multi-tenant data isolation feature within Salesforce for segregating data by business unit, region, or brand with sharing rules.

- **[Collibra](https://www.collibra.com/)**  
  Enterprise data governance and catalog platform with policy management, lineage, and multi-tenant data stewardship.

- **[Alation](https://www.alation.com/)**  
  Data intelligence platform with governance, lineage, and policy enforcement across multi-tenant data estates.

- **[Atlan](https://atlan.com/)**  
  Modern data catalog and governance platform with column-level lineage, access control, and tenant-aware policies.

- **[Privacera](https://privacera.com/)**  
  Unified data security and governance platform with fine-grained access control, masking, and multi-tenant policy enforcement.

- **[Immuta](https://www.immuta.com/)**  
  Data security platform with attribute-based access control, dynamic masking, and tenant isolation for analytics.

- **[Apache Ranger Cloud](https://ranger.apache.org/)**  
  Cloud-managed version of Apache Ranger for centralized authorization, auditing, and policy enforcement across Hadoop and cloud data services.

- **[BigID](https://bigid.com/)**  
  Data intelligence platform for discovery, classification, and governance of sensitive data across multi-tenant environments.

- **[Securiti.ai](https://securiti.ai/)**  
  Data command center for privacy, security, and governance with multi-tenant policy orchestration.

- **[OneTrust Data Governance](https://www.onetrust.com/)**  
  Privacy and data governance platform with data mapping, consent management, and cross-tenant policy enforcement.

## Open-Source GitHub Projects

- **[Apache Ranger](https://github.com/apache/ranger)**  
  Leading open-source framework for centralized data security and governance across Hadoop, Hive, HBase, Kafka, and cloud services. Provides fine-grained authorization, row-level filtering, column masking, and audit trails with multi-tenant policy support. Apache 2.0 licensed.

- **[Apache Atlas](https://github.com/apache/atlas)**  
  Open-source metadata management and data governance platform with lineage tracking, classification, and policy enforcement across multi-tenant data estates. Apache 2.0 licensed.

- **[OpenMetadata](https://github.com/open-metadata/OpenMetadata)**  
  Open-source metadata platform with data discovery, lineage, governance, and role-based access control for multi-tenant environments. Apache 2.0 licensed.

- **[DataHub](https://github.com/datahub-project/datahub)**  
  LinkedIn's open-source metadata platform with data discovery, lineage, governance, and policy management for multi-tenant data ecosystems. Apache 2.0 licensed.

- **[Amundsen](https://github.com/amundsen-io/amundsen)**  
  Lyft's open-source data discovery and metadata engine with governance features and multi-tenant catalog support. Apache 2.0 licensed.

- **[Apache Sentry](https://github.com/apache/sentry)**  
  Open-source authorization framework for Hadoop with role-based access control and multi-tenant policy enforcement. Apache 2.0 licensed.

- **[OPA (Open Policy Agent)](https://github.com/open-policy-agent/opa)**  
  Open-source policy engine with Rego language for fine-grained, multi-tenant authorization across cloud-native applications. Apache 2.0 licensed.

- **[Oso](https://github.com/osohq/oso)**  
  Open-source authorization framework with policy-as-code for multi-tenant data access control. Apache 2.0 licensed.

- **[Casbin](https://github.com/casbin/casbin)**  
  Open-source authorization library with ACL, RBAC, ABAC models for multi-tenant access control. Apache 2.0 licensed.

- **[Keycloak](https://github.com/keycloak/keycloak)**  
  Open-source identity and access management with fine-grained authorization, tenant realms, and policy enforcement. Apache 2.0 licensed.

- **[OpenFGA](https://github.com/openfga/openfga)**  
  Open-source fine-grained authorization system inspired by Google Zanzibar, ideal for multi-tenant relationship-based access. Apache 2.0 licensed.

- **[SpiceDB](https://github.com/authzed/spicedb)**  
  Open-source Zanzibar-inspired permissions database for multi-tenant authorization and data governance. Apache 2.0 licensed.

- **[Permify](https://github.com/Permify/permify)**  
  Open-source authorization service with relationship-based access control for multi-tenant applications. Apache 2.0 licensed.

- **[Apache Knox](https://github.com/apache/knox)**  
  Open-source gateway for Hadoop with authentication, authorization, and multi-tenant access control. Apache 2.0 licensed.

- **[Great Expectations](https://github.com/great-expectations/great_expectations)**  
  Open-source data quality and validation framework with governance hooks for multi-tenant data pipelines. Apache 2.0 licensed.

- **[OpenLineage](https://github.com/OpenLineage/OpenLineage)**  
  Open-source lineage collection framework for tracking data flow and governance across multi-tenant systems. Apache 2.0 licensed.

- **[Marquez](https://github.com/MarquezProject/marquez)**  
  Open-source metadata service for data lineage and governance with multi-tenant namespace support. Apache 2.0 licensed.

- **[DataHub](https://github.com/acryldata/datahub)**  
  Acryl Data's distribution of DataHub with enhanced governance and multi-tenant features. Apache 2.0 licensed.

- **[Cloud Custodian](https://github.com/cloud-custodian/cloud-custodian)**  
  Open-source rules engine for cloud security, compliance, and governance across multi-tenant cloud accounts. Apache 2.0 licensed.

- **[OpenPolicyAgent Gatekeeper](https://github.com/open-policy-agent/gatekeeper)**  
  Kubernetes-native policy controller for multi-tenant cluster governance and admission control. Apache 2.0 licensed.

### Additional Strong Open-Source Options

- **[Apache Griffin](https://github.com/apache/griffin)** — Open-source data quality and governance solution for multi-tenant big data environments.
- **[DataHub](https://github.com/datahub-project/datahub)** — Metadata platform with governance, lineage, and access control.
- **[Metacat](https://github.com/Netflix/metacat)** — Netflix's metadata service for multi-tenant data governance.
- **[Apache Airflow](https://github.com/apache/airflow)** — Workflow orchestration with governance hooks for multi-tenant pipelines.
- **[Dagster](https://github.com/dagster-io/dagster)** — Data orchestrator with asset lineage and governance features.
- **[Great Expectations](https://github.com/great-expectations/great_expectations)** — Data validation with governance integration.
- **[Soda Core](https://github.com/sodadata/soda-core)** — Open-source data quality and governance framework.
- **[OpenMetadata](https://github.com/open-metadata/OpenMetadata)** — Metadata platform with governance and multi-tenant support.
- **Secrets Management** (HashiCorp Vault, OpenBao) for tenant-isolated credential governance.
- **Audit Logging** (Apache Kafka, Fluentd, OpenSearch) for multi-tenant audit trails.

**Frameworks for building custom systems**: Combine **Apache Ranger** for policy enforcement, **OpenMetadata** or **DataHub** for cataloging, **OPA** for policy-as-code, **Keycloak** for tenant identity, and **OpenSearch + Grafana** for audit analytics to build a complete self-hosted multi-tenant governance stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Data governance tools must comply with data protection regulations (GDPR, CCPA, HIPAA), industry standards (SOC 2, ISO 27001), and tenant contractual obligations.
- Self-hosted open-source solutions require proper security hardening, key management, and compliance verification.

---

**Made for data governance officers, platform engineers, compliance teams, and developers building multi-tenant data platforms.**  
Let's make multi-tenant data governance more open, transparent, and developer-friendly.
