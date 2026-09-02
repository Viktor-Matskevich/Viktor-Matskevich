# Viktor Matskevich

### AI Systems Architect · Industrial AI · IoT · Multi-Agent Systems

**Building intelligent systems for the physical world — from machines and sensors to data platforms and AI workflows.**

25+ years in IT · 10+ years in data analytics · industrial automation · manufacturing intelligence · end-to-end product architecture

---

## Proof of Work

| System | What it demonstrates | Core engineering stack |
|---|---|---|
| **[CypCut → OPC UA Gateway](https://github.com/Viktor-Matskevich/cypcut-opcua-gateway)** | Field-driven machine connectivity: vendor-specific laser-controller telemetry → normalized OPC UA for MDC/MES/SCADA | .NET 8 · OPC UA · TCP · protocol analysis · Windows Service |
| **HiveAngel** | Full edge-to-cloud IoT product: hardware → telemetry → time-series data → SaaS | ESP32-S3 · MQTT · FastAPI · PostgreSQL/TimescaleDB · Next.js · TypeScript |
| **AI-Team** | Multi-agent architecture, declarative agent definitions, validation and lifecycle management | Python · FastAPI · YAML · agent registry · CLI |
| **Industrial AI** | Connecting factory equipment, production data and decision systems | CNC/PLC · MDC/MES · OEE · telemetry · analytics |

➡️ **[Technical systems overview, architecture and implementation details](./SYSTEMS.md)**

---

## CypCut → OPC UA Gateway

A public, independent integration project for translating vendor-specific laser-controller telemetry into a stable OPC UA interface for manufacturing systems.

```text
Laser Controller → Collector / Protocol Layer → Normalized Data → OPC UA → MDC / MES / SCADA
```

**Implemented in the public prototype:**
- configurable HTTP/JSON collector;
- structured OPC UA address space;
- multiple machine endpoints;
- configuration validation and self-tests;
- Windows Service deployment workflow.

**Field evidence:** a separate clean-room investigation established a live CypCut/PCUI TCP connection on port `20112`, received and decoded binary frames, extracted tag/value data, and validated CRCs. One observed run processed **14,892 frames with 0 CRC errors**. Semantic mapping of physical machine states is still in progress and is not claimed as completed.

This project demonstrates practical machine connectivity: separating observed evidence from assumptions, analyzing an unfamiliar industrial interface, and normalizing trustworthy data for higher-level systems.

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

**Implemented engineering:**
- MQTT-first ESP32 telemetry with HTTP fallback;
- per-device identity and authentication;
- device capability and hardware-profile registry;
- telemetry ingestion and time-series persistence;
- backend APIs;
- Next.js / TypeScript SaaS application;
- authentication, device binding and telemetry UX.

This project demonstrates the ability to build across **embedded hardware, networking, backend, data architecture and product UI** as one system.

---

## Industrial AI & Manufacturing Intelligence

My core industrial work is focused on connecting **machines → data → operational intelligence**.

I work with CNCs, PLCs, industrial controllers, machine-data collection, MDC/MES architectures, OEE analytics, telemetry pipelines and AI-ready manufacturing data layers.

Typical engineering problems include heterogeneous equipment connectivity, normalization of machine states and events, production telemetry, alarms, loads, tool/program data, and preparing factory data for analytics and predictive intelligence.

---

## Engineering Domains

`AI Systems` · `Multi-Agent Systems` · `Industrial AI` · `IoT` · `Edge Devices` · `Machine Connectivity` · `OPC UA` · `Industrial Protocols` · `Telemetry` · `Data Architecture` · `MDC` · `MES` · `OEE` · `Manufacturing Intelligence`

**Backend & AI:** Python · FastAPI · APIs · agent architectures · configuration-driven systems  
**Industrial connectivity:** .NET · OPC UA · TCP/IP · CNC/PLC integration · protocol analysis  
**Data:** PostgreSQL · TimescaleDB · time-series telemetry · analytical pipelines  
**Edge & IoT:** ESP32 / ESP32-S3 · MQTT · sensors · device identity  
**Product:** Next.js · TypeScript · Docker · end-to-end system architecture

---

## How I Build

**Problem → Architecture → Working Prototype → Real-World Deployment → Data & Feedback → Iteration**

I am most interested in systems that can be validated against the physical world, not only demonstrated in a slide deck.

---

> **Portfolio note:** some implementation repositories are currently private while credentials, environment-specific deployment details, and reusable public showcase code are being separated. Public technical repositories expose architecture and representative implementation without publishing production secrets.
