# Ægis_v2

Reference testbed for *Obligation over Availability: Enforced Human Review and
Mandatory Provenance in Agentic Multimedia Verification* (MMM 2027).

Forensic capabilities (generated-content detection, reverse image/video search,
shot segmentation, feature and keyframe extraction) are exposed as MCP tools. An
LLM orchestrator runs one verification case per headless session, records every
finding in a shared evidence schema that requires a declared source, and reaches
a human through a blocking `ask_analyst` call on analyst-led dimensions.

> **Code is being prepared for release and will be added here shortly**,
> including the MCP server, the evidence schema, the verification protocol and
> the run-logging scripts.

## License

MIT, see `LICENSE`.
