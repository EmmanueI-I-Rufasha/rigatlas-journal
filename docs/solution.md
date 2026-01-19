---
title: Solution Approach
---

# Solution Approach

RigAtlas is built as a **clarity layer** for offshore and industrial environments.

It does **not** aim to replace enterprise platforms like IBM Maximo, SAP PM/EAM, AVEVA/PI, Honeywell Forge, Emerson AMS, Drogos, or custom in house systems.

Instead, RigAtlas focuses on one thing:  
**making complex environments easier to understand through rig centric visual clarity.**

---

## 🧭 What RigAtlas Does

RigAtlas provides:

- **Rig-centric asset visibility in context**  
  Map devices to **Rig → Deck → Area**, and to security **Zones/Conduits (IEC 62443)**.

- **A visual layer for relationships**  
  Show how assets, networks, and systems relate to each other so engineers can understand impact faster.

- **Vulnerability posture linked to real assets**  
  Ingest data (e.g., **NVD/MSRC**), normalize names, link CVEs to devices, and roll up exposure by area/zone.

- **Self-audit preparation workflows**  
  A lightweight control library (IEC 62443 / IMO / USCG-inspired), evidence capture, sampling support, and audit readiness tracking.

- **Offline-first thinking**  
  Designed for intermittent connectivity (sync queues + conflict handling), reflecting the reality of offshore environments.

---

## 🎯 What RigAtlas Intentionally Avoids

To stay focused and avoid becoming “everything software”, RigAtlas avoids:

- trying to replace EAM/CMMS tooling
- becoming a full digital twin platform
- expanding into broad operational control
- becoming a “general OT platform”

RigAtlas stays narrow on purpose because its advantage is clarity, not breadth.

---

## 🧱 Tech Stack Direction

RigAtlas is being designed as a full learning project with production style architecture:

- **C# / ASP.NET Core**
- **Clean Architecture + DDD**
- **TDD with xUnit**
- **EF Core + SQL Server** (relational domain modeling)
- **Electron** (offline first desktop direction)
- **React** (front-end UI)
- **Swagger**
- **Azure DevOps Pipelines + Terraform**
- **MongoDB** (diagram versioning)

---

## ✅ The Goal

RigAtlas is built on the belief that:

> Better visibility leads to better decisions.

By giving engineers and non technical stakeholders a clear way to see:
- what exists
- what connects to what
- what is affected by changes
- what risk exists where

…RigAtlas aims to reduce ambiguity and support safer, more informed work.
