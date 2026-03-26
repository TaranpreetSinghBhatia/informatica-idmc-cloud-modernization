# informatica-idmc-cloud-modernization
End-to-end data integration pipeline using Informatica IDMC and Secure Agent for hybrid cloud architecture.

# Informatica IDMC: Hybrid Cloud Data Integration Pipeline

## Project Overview
This project demonstrates a functional "Ground-to-Cloud" data integration using **Informatica Intelligent Data Management Cloud (IDMC)**. The architecture focuses on securely synchronizing on-premise flat-file data with cloud-managed targets, simulating a real-world enterprise modernization scenario.

## Architecture & Componentry


* **Platform:** Informatica IDMC (Spring 2026 Release)
* **Runtime Environment:** Local Secure Agent (Windows/Linux)
* **Source:** Flat-File Ingestion (.csv)
* **Integration Logic:** Mapping Task Wizard with 1:1 Field Mapping & Data Validation
* **Target:** Demo-Target-FlatFile (Local Storage)

## Implementation Highlights
1.  **Secure Agent Configuration:** Successfully deployed and registered a local Secure Agent to act as the processing engine, ensuring data remains behind the firewall during execution which is a critical requirement for **Public Sector/Federal** compliance.
2.  **Mapping Task Design:** Developed a validated Mapping Task to handle metadata synchronization and field-level mapping for core entity data.
3.  **Data Integrity:** Validated 100% success rate across 5+ data fields, ensuring zero data loss during the transformation lifecycle.
4.  **Operational Monitoring:** Leveraged the IDMC Monitor service to analyze session logs, troubleshooting runtime performance and ensuring job success.

## 📊 Results
* **Job Status:** Success
* **Throughput:** 5/5 Rows Processed
* **Log Level:** Verbose Initialization for granular debugging

## 🔑 Key Skills Demonstrated
* Cloud Data Integration (CDI)
* Infrastructure Administration (Secure Agent Setup)
* Hybrid Cloud Architecture
* Data Validation & Troubleshooting
