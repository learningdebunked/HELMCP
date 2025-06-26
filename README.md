# HELMCP
Healthcare Event Logging for MCP. Emphasizes healthcare-specific logging and auditing for model context

Built using Apache NIFI , Flink , Ranger along with Kafka this framework **HELMCP** is an open-source framework for **auditing, redacting, and rate-limiting Model Context Protocol (MCP) requests** in AI-driven healthcare systems.

AI agents in healthcare increasingly rely on **contextual memory** from MCP servers to summarize records, make recommendations, or drive decisions. But this introduces risk:

- ⚠️ Unchecked exposure of **PHI/PII**
- 💸 Unbounded token consumption in LLMs
- 🔍 No visibility into **what context was used and why**

 **HELMCP provides a policy-driven middleware layer** that brings **governance, transparency, and control** over every request to an MCP server.


