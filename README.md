# HELMCP

**H**ealthcare **E**vent **L**ogging for **MCP**

HELMCP is an open-source framework for **auditing, redacting, and rate-limiting Model Context Protocol (MCP) requests** in AI-driven healthcare systems.

## Overview

AI agents in healthcare increasingly rely on **contextual memory** from MCP servers to summarize records, make recommendations, or drive decisions. But this introduces risk:

- ⚠️ Unchecked exposure of **PHI/PII**
- 💸 Unbounded token consumption in LLMs
- 🔍 No visibility into **what context was used and why**

HELMCP provides a **policy-driven middleware layer** that brings **governance, transparency, and control** over every request to an MCP server.

## Why It Matters to the US Healthcare System

| Challenge | HELMCP Solution |
|-----------|-----------------|
| **HIPAA and Data Sensitivity** | Audits context payloads for PHI before LLM processing |
| **Cost Control for AI in Cloud** | Enforces token and API rate caps to avoid runaway costs |
| **Model Hallucination Risks** | Tracks provenance and relevance of MCP data fed into LLMs |
| **Multi-agent Coordination** | Regulates MCP traffic across agents (e.g., scheduling, EHRs) |

## Technologies Used

| Component | Technology |
|-----------|------------|
| **Ingestion** | Apache Kafka |
| **Flow Routing** | Apache NiFi |
| **Redaction** | Microsoft Presidio / Philter |
| **Stream Analysis** | Apache Flink |
| **Policy Engine** | Apache Ranger |
| **Audit Storage** | Elasticsearch / OpenSearch |
| **LLM Integration** | LangServe / FastAPI / OpenAI |

## Getting Started

*Documentation and setup instructions coming soon.*

## License

*License information will be added here.*
