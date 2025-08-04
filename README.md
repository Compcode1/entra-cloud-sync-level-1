# Initial Hybrid Identity Integration via Microsoft Entra Cloud Sync (Level 1)

## 📘 Project Overview

This project simulates a real-world onboarding scenario for a small-to-medium business beginning its transition from a traditional on-premises Windows Server Active Directory environment to the Microsoft cloud ecosystem. Using **Microsoft Entra Cloud Sync**, it demonstrates how lightweight identity synchronization can enable secure Microsoft 365 sign-ins without requiring the complexity of full Azure AD Connect (now Connect Sync).

The project models a facsimile deployment at **Level 1** — focused on understanding the business case, core architectural components, and introductory configuration requirements for Microsoft Entra Cloud Sync.

---

## 💼 Business Scenario: Acme Finance Group

- A regional accounting firm with on-premises Active Directory infrastructure
- Seeks to enable Microsoft 365 access using cloud identity
- Has a small IT team with minimal customization needs
- Chooses **Microsoft Entra Cloud Sync** to begin its hybrid identity journey

This mirrors a **very common real-world scenario** for SMBs looking to modernize access management while avoiding high implementation overhead.

---

## 🧠 Learning Objectives (Level 1)

- Understand the role of Cloud Sync vs. Connect Sync
- Identify core components: AD Domain Controllers, sync agents, Microsoft Entra ID
- Map out the cloud-first synchronization flow
- Simulate key setup phases using facsimile architecture
- Develop a mental model for hybrid identity orchestration

---

## 🧭 Project Structure

- `entra_cloud_sync.ipynb`: Core Jupyter notebook simulating project design
- `diagram.png`: Visual layout of sync architecture and data flow
- `README.md`: This project overview and roadmap

---

## 🔁 Roadmap: Multi-Level Progression

| Level | Focus Area | Description |
|-------|------------|-------------|
| **Level 1** | Orientation & Business Fit | Understand when and why to use Entra Cloud Sync |
| **Level 2** | Technical Configuration | Deep dive into firewall rules, sync agents, attribute mapping, logs |
| **Level 3** | Custom Use Cases | Explore exclusions, OUs, attribute transformations |
| **Level 4** | Troubleshooting & Monitoring | Simulate failures, alerting, diagnostics |
| **Level 5** | Migration & Advanced Integration | Migrate to/from Connect Sync, integrate with Defender, Conditional Access, Identity Governance |

---

## 📚 Vision: Building a Cloud Identity Knowledge Base

This project is part of a larger effort to build a **multi-level, facsimile-driven knowledge base** for cloud identity, detection engineering, and Microsoft security architecture. Each level adds new complexity while grounding concepts in practical context and business relevance.

The long-term goal is to create a repeatable framework for mastering identity solutions through simulation, inquiry, and layered technical depth — without relying on unstable lab configurations.

---

## 🔗 Next Steps

- Proceed to Level 2 by detailing each configuration step
- Introduce synthetic logs and telemetry simulation
- Expand project series to include Microsoft Entra Connect Sync for comparison

---
