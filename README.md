# Viktor Matskevich

### AI Systems Architect · Industrial AI · IoT · Multi-Agent Systems

I build intelligent systems that connect **software, machines, sensors, data, and AI** to real-world operations.

My background spans **25+ years in IT**, industrial automation and digital transformation, with **10+ years in data analytics and manufacturing intelligence**. I focus on turning complex technical environments into working end-to-end systems — from device connectivity and telemetry to backend architecture, data models, analytics, and AI-driven workflows.

---

## Selected Systems

### AI-Team — Multi-Agent AI Platform

A modular platform for managing specialized AI agents as a coordinated system.

**Current engineering work includes:**
- declarative YAML-based agent definitions;
- central agent registry and lifecycle management;
- configurable personality, skills, tools, memory, and agent-to-agent relations;
- automated validation of agent definitions and registry consistency;
- management CLI for listing, inspecting, validating, enabling, and disabling agents;
- foundation for orchestration, persistent memory, and future LLM routing.

**Engineering focus:** multi-agent architecture · AI orchestration · memory systems · configuration-driven design · Python · FastAPI

---

### HiveAngel — IoT + AI Platform for Smart Beekeeping

A real-world IoT system designed to answer a simple question: **What is happening in the apiary right now?**

```text
ESP32-S3 + sensors
        ↓
MQTT telemetry
        ↓
Ingestion API
        ↓
PostgreSQL / TimescaleDB
        ↓
Application API
        ↓
SaaS dashboard
        ↓
Analytics / AI insights
```

**Implemented engineering components include:**
- ESP32-S3 firmware with MQTT-first telemetry and HTTP fallback;
- per-device identity and authentication tokens;
- device capabilities and hardware-profile registry;
- telemetry ingestion and persistence;
- PostgreSQL / TimescaleDB time-series data model;
- backend APIs for devices, apiaries, telemetry, and capabilities;
- Next.js / TypeScript SaaS frontend;
- authentication, device binding, dashboard, and telemetry views.

**Engineering focus:** ESP32 · MQTT · IoT · FastAPI · PostgreSQL · TimescaleDB · Next.js · TypeScript · telemetry systems

---

### Industrial AI & Manufacturing Intelligence

My core industrial work is at the intersection of equipment, production data, analytics, and decision systems.

I work with architectures that connect **CNCs, PLCs, industrial controllers, MES/MDC systems, telemetry pipelines, OEE analytics, and AI-ready data layers**.

Typical problems I solve:
- connecting heterogeneous industrial equipment to a unified data layer;
- collecting machine states, production events, alarms, loads, and process signals;
- designing MDC / MES / OEE data flows;
- turning raw machine telemetry into operational intelligence;
- building foundations for anomaly detection, predictive analytics, and AI-assisted manufacturing decisions.

---

## Engineering Focus

`AI Systems` · `Multi-Agent Systems` · `Industrial AI` · `IoT` · `Edge Devices` · `Machine Connectivity` · `Telemetry` · `Data Architecture` · `MDC` · `MES` · `OEE` · `Manufacturing Intelligence`

### Technologies & Platforms

**AI / Backend**  
Python · FastAPI · agent architectures · LLM systems · API design · configuration-driven systems

**Data**  
PostgreSQL · TimescaleDB · time-series telemetry · analytics pipelines · structured event data

**IoT / Edge**  
ESP32 / ESP32-S3 · MQTT · sensors · device identity · edge telemetry

**Industrial Systems**  
CNC / PLC connectivity · machine data collection · MES / MDC · OEE · industrial telemetry

**Product & Infrastructure**  
Docker · backend services · system architecture · production-oriented design · end-to-end product development

---

## How I Build

```text
Real problem
    ↓
System architecture
    ↓
Working prototype
    ↓
Real-world deployment
    ↓
Data & feedback
    ↓
Iteration and improvement
```

I prefer systems that can be tested against the physical world rather than architectures that exist only on diagrams.

---

## Current Portfolio Direction

This GitHub is being structured as a **proof-of-work portfolio**. Public technical showcases are being prepared from working private repositories with production credentials and sensitive deployment details removed.

The goal is simple: make the architecture, engineering decisions, implementation depth, and real-world results visible.
