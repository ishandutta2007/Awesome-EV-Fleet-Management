# Awesome-EV-Fleet-Management

## Top EV Fleet Management Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Electric Vehicle Fleet Telematics, Depot Charging Optimization, Battery Health, Energy Management, Route Planning & Electrification Analytics*

**Last updated: August 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **EV Fleet Management**. These tools help organizations monitor electric vehicles, optimize charging schedules, manage energy costs, track battery health, plan routes with range constraints, and support the transition from ICE to electric fleets.



**Examples** include Ampcontrol, ChargePoint Fleet, Geotab EV, Samsara Fleet Electrification, Volteras, EVenergi, Optiwatt Fleet, AMPECO Fleet, Driivz Fleet, and Hitachi ZeroCarbon (the category leaders).



**Open-source emphasis**: Full commercial-grade open-source EV fleet platforms are still emerging. This section is expanded with the strongest available open-source projects for charging management (OCPP), energy optimization, simulation/RL environments, telematics research, and self-hosted CSMS solutions that fleets and researchers can adapt.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Ampcontrol](https://www.ampcontrol.io/)**  

  AI-driven EV charging and energy management platform specialized in depot charging optimization, load management, and OCPP-compliant charger integration.



- **[ChargePoint Fleet](https://www.chargepoint.com/)**  

  Fleet-focused charging software and hardware ecosystem for managing depot and workplace charging sessions, energy use, and driver policies.



- **[Geotab EV](https://www.geotab.com/)**  

  Telematics platform with deep EV data support (300+ models), battery state-of-charge/health monitoring, suitability analysis, and electrification planning tools.



- **[Samsara Fleet Electrification](https://www.samsara.com/)**  

  Unified fleet platform offering EV suitability scoring, charging analytics, battery insights, and mixed-fleet visibility for organizations transitioning to electric.



- **[Volteras](https://www.volteras.com/)**  

  EV fleet and charging management solution focused on operational visibility and energy optimization.



- **[EVenergi](https://www.evenergi.com/)**  

  Electrification planning and fleet transition platform helping organizations model and manage the shift to electric vehicles.



- **[Optiwatt Fleet](https://www.optiwatt.com/)**  

  Smart charging and energy management tools aimed at optimizing EV charging costs and grid interaction for fleets.



- **[AMPECO Fleet](https://www.ampeco.com/)**  

  EV charging network management platform with fleet-oriented features for operators and large charging deployments.



- **[Driivz Fleet / InSite](https://driivz.com/)**  

  Comprehensive EV charging management system supporting depot operations, session control, energy optimization, and fleet workflows.



- **[Hitachi ZeroCarbon](https://www.hitachi.com/)**  

  Enterprise solutions for zero-carbon mobility and fleet electrification, combining energy and vehicle management capabilities.



## Open-Source GitHub Projects

- **[evcc](https://github.com/evcc-io/evcc)**  

  Popular open-source solar-aware EV charging controller that optimizes charging based on PV production, battery storage, and dynamic electricity prices.



- **[OpenCPO](https://github.com/opencpo/opencpo)**  

  Open-source EV charging platform (CSMS) with OCPP 1.6/2.0.1 support, admin dashboard, driver app, and charger simulator.



- **[Open EMS / open energy management systems](https://github.com/)**  

  Self-hosted energy management projects that monitor solar, battery, and EV charging, often with day-ahead price optimization.



- **[FleetRL](https://github.com/EnzoCording/FleetRL)**  

  Open-source reinforcement-learning environment specifically designed for realistic EV fleet charging optimization research.



- **[Open-EV-Fleet](https://github.com/erc-fhv/open-ev-fleet)**  

  Research monorepo with Python and Julia packages for EV fleet optimization algorithms, simulation, and data processing.



- **[OCPP implementations and libraries](https://github.com/)**  

  Multiple open-source OCPP 1.6/2.0.1 stacks in Go, Python, and other languages that form the foundation of custom CSMS solutions.



- **[Green Software / carbon-aware charging tools](https://github.com/)**  

  Projects that shift EV charging to lower-carbon grid periods using real-time or forecasted carbon intensity data.



- **[Fleet route optimizers with EV constraints](https://github.com/)**  

  Open-source vehicle routing tools that incorporate range, charging stops, and energy consumption models.



- **[Telematics and CAN-bus open tools](https://github.com/)**  

  Community projects for reading EV battery and charging data from vehicles or charging stations.



- **[Simulation and digital-twin frameworks](https://github.com/)**  

  Academic and open frameworks for modeling depot charging, load management, and fleet electrification scenarios.



### Additional Strong Open-Source Options

- MQTT + InfluxDB + Grafana stacks for real-time charger and vehicle telemetry dashboards.

- Custom load-management algorithms (static and dynamic) published by research groups.

- Integration examples connecting open CSMS platforms to existing fleet telematics.

- Battery degradation models and SoC estimation libraries.

- Open data pipelines for electricity prices, carbon intensity, and weather forecasts used in charging optimization.



**Frameworks for building custom systems**: Deploy an open **OCPP CSMS** (OpenCPO or similar) for charger control, use **evcc** or custom logic for price- and solar-aware charging, collect vehicle data via telematics APIs or open readers, and optimize schedules with **FleetRL**-style algorithms or classic MILP solvers. Visualize everything in Grafana or a custom dashboard. This combination gives fleets full ownership of charging infrastructure and optimization logic while remaining interoperable with commercial hardware.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- EV fleet management involves safety-critical charging, grid constraints, and vehicle warranties. Open-source tools are excellent for research, prototyping, and cost-sensitive deployments but require thorough testing, electrical expertise, and compliance with local energy regulations before production use.

- Always validate charging strategies against vehicle OEM recommendations and site electrical capacity.



---

**Made for fleet managers, energy teams, and organizations accelerating the transition to electric mobility.**

Let's make EV fleet operations more open, optimized, and data-driven.
