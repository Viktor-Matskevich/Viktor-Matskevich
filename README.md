# Viktor Matskevich

### AI Systems Architect · Industrial AI · IoT · Multi-Agent Systems

**Building intelligent systems for the physical world — from machines and sensors to data platforms and AI workflows.**

25+ years in IT · 10+ years in data analytics · industrial automation · manufacturing intelligence · end-to-end product architecture

---

## Proof of Work

| System | What it demonstrates | Core engineering stack |
|---|---|---|
| **AI-Team** | Multi-agent architecture, declarative agent definitions, validation and lifecycle management | Python · FastAPI · YAML · agent registry · CLI |
| **HiveAngel** | Full edge-to-cloud IoT product: hardware → telemetry → time-series data → SaaS | ESP32-S3 · MQTT · FastAPI · PostgreSQL/TimescaleDB · Next.js · TypeScript |
| **Industrial AI** | Connecting factory equipment, production data and decision systems | CNC/PLC · MDC/MES · OEE · telemetry · analytics |

➡️ **[Technical systems overview, architecture and implementation details](./SYSTEMS.md)**

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

`AI Systems` · `Multi-Agent Systems` · `Industrial AI` · `IoT` · `Edge Devices` · `Machine Connectivity` · `Telemetry` · `Data Architecture` · `MDC` · `MES` · `OEE` · `Manufacturing Intelligence`

**Backend & AI:** Python · FastAPI · APIs · agent architectures · configuration-driven systems  
**Data:** PostgreSQL · TimescaleDB · time-series telemetry · analytical pipelines  
**Edge & IoT:** ESP32 / ESP32-S3 · MQTT · sensors · device identity  
**Product:** Next.js · TypeScript · Docker · end-to-end system architecture

---

## How I Build

**Problem → Architecture → Working Prototype → Real-World Deployment → Data & Feedback → Iteration**

I am most interested in systems that can be validated against the physical world, not only demonstrated in a slide deck.

---

> **Portfolio note:** some implementation repositories are currently private while credentials, environment-specific deployment details, and reusable public showcase code are being separated. Public technical repositories will expose architecture and representative implementation without publishing production secrets.
