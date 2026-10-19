<div align="center">

<img src="voltera_logo.png" alt="VoltEra" width="150">

# VoltEra

### Renewable-powered edge computing, from idea to feasibility

The product, architecture and feasibility dossier for modular nodes that combine solar generation,
LiFePO4 storage and edge-compute capacity — sized for creators, e-sports and small operators in Brazil.

[![Dashboard](https://img.shields.io/badge/operational%20demo-voltera--dash.vercel.app-16A34A?style=for-the-badge&logo=vercel&logoColor=white)](https://voltera-dash.vercel.app)
[![Website](https://img.shields.io/badge/n3xus.dev-0B1220?style=for-the-badge&logo=googlechrome&logoColor=14B8A6)](https://n3xus.dev)
[![Status](https://img.shields.io/badge/status-concept%20%26%20feasibility-F59E0B?style=for-the-badge)](#current-status)
[![License](https://img.shields.io/badge/License-CC%20BY%204.0-EF9421?style=for-the-badge&logo=creativecommons&logoColor=white)](LICENSE)

[![PRD](https://img.shields.io/badge/PRD-architecture-111827?style=flat-square&logo=markdown&logoColor=white)](VolTera_PRD_and_Architecture.md)
[![BOM](https://img.shields.io/badge/BOM-xlsx-217346?style=flat-square&logo=microsoftexcel&logoColor=white)](VolTera_BOM.xlsx)
[![Financial model](https://img.shields.io/badge/financial%20model-xlsx-217346?style=flat-square&logo=microsoftexcel&logoColor=white)](VolTera_Financial_Model.xlsx)
[![Risk register](https://img.shields.io/badge/risk%20register-xlsx-217346?style=flat-square&logo=microsoftexcel&logoColor=white)](VolTera_Risk_Register.xlsx)
[![Docs](https://img.shields.io/badge/docs-Portuguese-111827?style=flat-square)](#repository-map)

</div>

---

## Table of Contents

- [Overview](#overview)
- [System concept](#system-concept)
- [Repository map](#repository-map)
- [Concept art](#concept-art)
- [Responsible use](#responsible-use)
- [Current status](#current-status)

---

## Overview

**VoltEra** asks a simple question: *could a creator or a small team run its own always-on compute, powered by
the sun, instead of renting it from a hyperscaler?* This repository is the planning work behind
that question — what to build, what it costs, what can go wrong and what the law says.

It is built for:

- founders and investors evaluating renewable edge infrastructure;
- engineers who want a starting PRD, BOM and risk register to challenge;
- anyone studying how energy, storage and compute fit in one cabinet.

<p align="center">
  <img src="voltera_blueprint.png" alt="VoltEra node concept: solar array, energy cabinet and compute cabinet" width="520">
</p>

---

## System concept

```mermaid
flowchart LR
  SUN["Solar panels<br/>1–2 kWp"] --> BAT["LiFePO4 5–10 kWh<br/>+ hybrid inverter"]
  GRID["Grid (optional)"] -.-> BAT
  BAT --> NODE["Edge compute node"]
  NODE --> NET["Secure networking<br/>+ orchestration"]
  NET --> OPS["Monitoring · capacity planning<br/>· resource allocation"]
  OPS -. "visualized in" .-> GP["GreenPulse dashboard"]
```

---

## Repository map

| Document | What it covers |
|---|---|
| [Executive Summary](VolTera_Executive_Summary.md) | Mission, market, business model |
| [PRD and Architecture](VolTera_PRD_and_Architecture.md) | Requirements and proposed system design |
| [Operations Manual](VolTera_Operations_Manual.md) | Operating assumptions and procedures |
| [Compliance and Regulation](VolTera_Compliance_and_Regulation.md) | Initial Brazilian regulatory research |
| [Risk and Mitigation](VolTera_Risk_and_Mitigation.md) | Technical and operational risks |
| [Startup Guide](VolTera_Startup_Guide.md) | Steps to take the concept to a company |
| `VolTera_BOM.xlsx` | Preliminary bill of materials |
| `VolTera_Financial_Model.xlsx` | Scenario-based financial model |
| `VolTera_Compliance_Register.xlsx` · `VolTera_Risk_Register.xlsx` | Structured trackers |
| `VolTera_Roadmap.csv` | Month-by-month delivery plan |

The documents are written in Portuguese.

---

## Concept art

<p align="center">
  <img src="docs/concepts/concept-01.png" width="32%" alt="Concept 1">
  <img src="docs/concepts/concept-02.png" width="32%" alt="Concept 2">
  <img src="docs/concepts/concept-03.png" width="32%" alt="Concept 3">
</p>
<p align="center">
  <img src="docs/concepts/concept-04.png" width="32%" alt="Concept 4">
  <img src="docs/concepts/concept-05.png" width="32%" alt="Concept 5">
  <img src="docs/concepts/concept-06.png" width="32%" alt="Concept 6">
</p>

AI-generated concept renders, not photos of built hardware.

---

## Responsible use

Electrical systems, batteries, renewable generation and datacenter equipment carry safety and regulatory risk.
Nothing here replaces licensed electrical, structural, environmental, legal or financial professionals.
Hardware specs, financial projections and regulatory assumptions need specialist validation before any purchase.

Related: [GreenPulse](https://github.com/Samurai33/GreenPulse) (dashboard prototype) ·
[VoltEra Nexus](https://github.com/Samurai33/VoltEra-Nexus-The-Energy-Consciousness-Protocol) (digital-art companion).

---

## Current status

| | |
|---|---|
| **Concept & architecture** | Documented |
| **Dashboard** | Public demo |
| **Hardware** | Not built; renders only |
| **Regulatory & ROI** | Pending qualified review; numbers are illustrative |

---

<div align="center">

**Need something built, secured or kept online?** → [samurai@n3xus.dev](mailto:samurai@n3xus.dev) · [n3xus.dev](https://n3xus.dev)

© Thiago "Samurai" Rangel · [N3XUS](https://n3xus.dev)

</div>
