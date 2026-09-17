# Viktor Matskevich

### Independent Industrial IT Product Architect · Industrial Connectivity · Edge/IoT · AI-Assisted Engineering

**Building reliable IT systems for the physical world — from industrial equipment and edge devices to data platforms, diagnostics and AI-assisted workflows.**

industrial IT · product architecture · machine connectivity · manufacturing intelligence · edge systems

---

## Proof of Work

| Area | What it demonstrates | Core engineering themes |
|---|---|---|
| **Industrial Machine Connectivity Research** | Field-driven connectivity, telemetry validation, reusable diagnostics and AI-assisted engineering workflows | CNC / PLC · industrial protocols · OPC UA · evidence-driven integration |
| **Engineering Knowledge Experiment** | Turning accumulated engineering material into reusable patterns with explicit evidence, gaps and confidence | knowledge engineering · provenance · AI-assisted retrieval · validation |
| **HiveAngel** | Full edge-to-cloud IoT product: hardware → telemetry → time-series data → SaaS | ESP32-S3 · MQTT · FastAPI · PostgreSQL/TimescaleDB · Next.js · TypeScript |
| **AI-Team** | Multi-agent architecture, declarative agent definitions, validation and lifecycle management | Python · FastAPI · YAML · agent registry · CLI |
| **Industrial IT & Manufacturing Intelligence** | Connecting factory equipment, production data and decision systems | CNC/PLC · MDC/MES · OEE · telemetry · analytics |

➡️ **[Technical systems overview and selected architecture notes](./SYSTEMS.md)**  
➡️ **[Industrial Machine Connectivity — sanitized case study](./case-studies/industrial-machine-connectivity/README.md)**  
➡️ **[Engineering Knowledge Experiment — sanitized proof of work](./case-studies/engineering-knowledge-experiment/README.md)**

---

## Industrial Machine Connectivity Research

A field-driven investigation into a recurring industrial problem: **how to connect heterogeneous equipment, determine whether acquired telemetry is trustworthy, and turn each successful field investigation into reusable engineering knowledge.**

```text
Industrial Equipment
        ↓
Network & Service Discovery
        ↓
Protocol / Source Identification
        ↓
Read-only Acquisition
        ↓
Telemetry Validation
        ↓
Normalized Observations
        ↓
Diagnostics / Evidence / Higher-Level Systems
```

The public material intentionally focuses on **methodology, architectural reasoning, validation principles and sanitized lessons learned**. Production code, field configurations, proprietary protocol details, customer information and internal product architecture remain private.

A longer-term question behind the work is whether machine connectivity can move from an engineer-dependent craft toward a **reproducible, machine-readable and eventually AI-assisted engineering workflow**.

---

## Engineering Knowledge & AI-Assisted Workflows

A current engineering experiment explores how accumulated source code, documentation, architectures, notes and field evidence can be converted into reusable problem-solving knowledge rather than remaining a passive archive.

The public example demonstrates the output discipline — **known approaches → implementation patterns → trade-offs → evidence → gaps**, with conclusions classified by confidence instead of treating AI-generated synthesis as fact. The underlying corpus, indexing/retrieval implementation, internal taxonomy, prompts and proprietary material remain private.

---

## AI-Team

A modular platform for managing specialized AI agents as parts of a coordinated system.

**Implemented now:**
- declarative YAML agent definitions;
- central agent registry;
- configurable skills, tools, personality, memory and agent relations;
- automated validation;
- lifecycle management and CLI operations.

**Direction:** orchestration · persistent memory · task delegation · LLM routing · observability

---

## HiveAngel

An IoT + AI platform for remote beehive monitoring and intelligent decision support.

```text
Sensors → ESP32-S3 → MQTT → Ingestion API → TimescaleDB → API → SaaS Dashboard → Analytics / AI
```

This project demonstrates engineering across physical sensors, embedded firmware, device identity, networking, backend services, time-series data and product UI as one end-to-end system.

---

## Industrial IT & Manufacturing Intelligence

My industrial work focuses on turning heterogeneous factory equipment into reliable, structured data and reusable IT capabilities for operational and analytical systems.

I work with CNCs, PLCs, industrial controllers, machine-data collection, MDC/MES architectures, OEE analytics, telemetry pipelines, edge devices and AI-ready manufacturing data layers.

The emphasis is not only on getting data out of equipment, but on establishing **provenance, completeness, timing, semantic confidence and reproducible diagnostics** before higher-level software consumes it.

AI is used as an engineering accelerator where it adds decision value: diagnostics, knowledge capture, protocol investigation, semantic mapping and workflow assistance — not as a substitute for verified industrial evidence.

---

## Engineering Domains

`Industrial IT` · `Product Architecture` · `Machine Connectivity` · `Knowledge Engineering` · `Industrial AI` · `IoT` · `Edge Devices` · `OPC UA` · `Industrial Protocols` · `Telemetry` · `Data Architecture` · `MDC` · `MES` · `OEE` · `Manufacturing Intelligence` · `AI-Assisted Engineering`

**Backend & AI:** Python · FastAPI · APIs · agent architectures · configuration-driven systems  
**Industrial connectivity:** .NET · OPC UA · TCP/IP · CNC/PLC integration · protocol analysis  
**Data:** PostgreSQL · TimescaleDB · time-series telemetry · analytical pipelines  
**Edge & IoT:** ESP32 / ESP32-S3 · MQTT · sensors · device identity  
**Product:** product architecture · Next.js · TypeScript · Docker · end-to-end system design

---

## How I Build

**Problem → Architecture → Working Prototype → Real-World Validation → Evidence → Reusable Capability**

I am most interested in systems that can be validated against the physical world, not only demonstrated in a slide deck.

---

> **Disclosure note:** some implementation repositories and field systems are intentionally private. Public material exposes engineering reasoning and sanitized proof of work without publishing proprietary implementation details, credentials, customer data or internal product architecture.
