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

| Platform | Description | Pricing (Starting Tier) | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Ampcontrol](https://www.ampcontrol.io/)** | AI-driven EV charging and energy management platform specialized in depot charging optimization, load management, and OCPP-compliant charger integration. | Starts at ~$2,000/month for depot energy management & CSMS cloud platform | No free-forever plan; Guided demo & tailored pilot evaluation available upon request |
| **[ChargePoint Fleet](https://www.chargepoint.com/)** | Fleet-focused charging software and hardware ecosystem for managing depot and workplace charging sessions, energy use, and driver policies. | Starts at ~$360 – $1,630/port/year (~$30 – $135/port/month depending on Core vs. Enterprise Fleet tier) | No free-forever plan; Free site assessment & custom fleet pilot upon consultation |
| **[Geotab EV](https://www.geotab.com/)** | Telematics platform with deep EV data support (300+ models), battery state-of-charge/health monitoring, suitability analysis, and electrification planning tools. | Starts at ~$30 – $40/vehicle/month (GO Core / GO tier via authorized resellers) | No free-forever plan; 30-day free pilot program (e.g. Geotab Vitality) with GO tracker hardware |
| **[Samsara Fleet Electrification](https://www.samsara.com/)** | Unified fleet platform offering EV suitability scoring, charging analytics, battery insights, and mixed-fleet visibility for organizations transitioning to electric. | Starts at ~$27 – $33/vehicle/month (telematics tier; hardware ~$99–$148 upfront; 3-year contract) | 30-day free trial (includes test hardware units with full platform access; return before 30 days to avoid charges) |
| **[Volteras](https://www.volteras.com/)** | Unified OEM connected-vehicle API and EV fleet charging platform for direct vehicle telematics and energy optimization without aftermarket hardware. | Starts at ~$2 – $5/connected vehicle/month for direct OEM API data access | Free developer sandbox tier with unlimited test calls for simulated/mock vehicle VINs |
| **[EVenergi (BetterFleet)](https://www.evenergi.com/)** | Electrification planning, digital twin depot modeling, and fleet transition simulation platform for public transit and commercial fleets. | Starts at ~$15 – $30/vehicle/month for digital twin modeling & transition planning tools | No free-forever plan; Free demo and preliminary electrification feasibility assessment |
| **[Optiwatt Fleet](https://www.optiwatt.com/)** | Smart charging and energy management platform aimed at optimizing EV charging costs and utility grid interaction for fleets and drivers. | **Free** for standard vehicle tracking & automated charge scheduling (utility-funded model) | Free forever for unlimited vehicles and automated charging schedule optimization |
| **[AMPECO Fleet](https://www.ampeco.com/)** | Hardware-agnostic EV charging network management platform (CPMS) with fleet-oriented charging controls, dynamic tariffs, and roaming. | Starts at ~$10 – $25/charging point/month (plus initial onboarding & setup fee) | No free-forever plan; Live interactive demo & sandbox environment upon sales inquiry |
| **[Driivz Fleet / InSite](https://driivz.com/)** | Comprehensive EV charging management system (CSMS) supporting depot operations, smart energy optimization, and driver billing. | Starts at ~$600 – $800/port/year (~$50 – $67/port/month for cloud management) | No free-forever plan; Free interactive demo and custom ROI calculation consultation |
| **[Hitachi ZeroCarbon](https://www.hitachi.com/)** | Enterprise solutions for zero-carbon mobility and fleet electrification, combining BatteryManager analytics, depot charging, and TCO financing. | Custom managed service packages starting from ~$50/vehicle/month (or financed per-kWh/charger infrastructure models) | No free-forever plan; Free access to HGV Carbon & Cost Calculator and fleet readiness assessment |



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
