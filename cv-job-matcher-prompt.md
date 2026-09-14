# Project Brief: CV-to-Company Job Matcher

## Overview
Build an app or website that takes a user's CV and checks a curated list of target companies for open roles that match their profile. It should surface relevant vacancies without the user having to manually search each company's careers page.

## Core Flow
1. **Upload CV** — user uploads their CV (PDF/DOCX).
2. **Keyword capture** — the app asks the user what keywords/roles they're looking for (e.g. job titles, technologies, seniority level).
3. **Keyword suggestions** — based on the CV content, the app suggests additional relevant keywords the user may not have thought to include (e.g. "early career," "graduate programme," "AI/ML," "computer vision," "embedded systems").
4. **Matching** — the app searches the careers pages / job boards of the target companies below and returns roles that match the combined keyword set (user-provided + CV-derived).
5. **Results** — display matching roles, ranked or grouped by company, with a direct link to apply.

## Target Companies (by tier)

**Tier 1 — Big Tech**
Google (Dublin), Apple (Cork), Meta (Dublin), Microsoft (Dublin), Amazon (Dublin), Nvidia (Santa Clara/EU), Waymo, Tesla (Autopilot/AI), DeepMind (London), OpenAI (Dublin/London)

**Tier 2 — Semiconductor & Hardware**
Qualcomm (Cork), Intel (Leixlip/EU), ASML (Eindhoven), Analog Devices (Limerick), Texas Instruments, ARM (Cambridge), Mobileye (Jerusalem/EU), TSMC (EU expansion), Synopsys, Cadence

**Tier 3 — Robotics & Autonomous Systems**
Boston Dynamics, Sanctuary AI, Agility Robotics, Figure AI, Physical Intelligence, Cruise (GM), Motional, Zoox (Amazon), Continental (ADAS), Bosch (ADAS/CV)

**Tier 4 — Computer Vision & AI Startups/Scale-ups**
Valeo (Tuam), Everseen (Cork), Zenseact, Orca AI, Tractable, Innoviz Technologies, Prophesee, Seeing Machines, DeepRec (Dublin), Asio Technologies

**Tier 5 — Aerospace & Defence Tech**
Leonardo, BAE Systems, L3Harris, Elbit Systems, Thales, MBDA, Airbus (AI/data teams), Safran, Cobalt Intelligence, Shield AI

**Tier 6 — Medical Device & Biotech**
Boston Scientific (Galway/Cork), Stryker (Cork), Medtronic (Dublin/Galway), Becton Dickinson, Siemens Healthineers, Philips Healthcare, GE HealthCare, Smith+Nephew, Intuitive Surgical, Hologic

**Tier 7 — Industrial Automation & Manufacturing Tech**
Rockwell Automation, Cognex (machine vision), Keyence, FANUC, KUKA, ABB Robotics, Omron, Teradyne (MiR), Zebra Technologies, Datalogic

**Tier 8 — Research Labs & National Institutes**
Tyndall National Institute, ADAPT Centre, Insight Centre (UCD), Lero (UL), SFI/IRCSET-funded labs, Fraunhofer (Germany), IMEC (Belgium), CEA-Leti (France), CERN (Geneva), Alan Turing Institute (London)

**Tier 9 — Software/Cloud with ML Infrastructure Teams**
Palantir (London/Dublin), Databricks, Hugging Face, Mistral AI, Cohere, Scale AI, Weights & Biases, Qdrant, Modal, Groq

**Tier 10 — Irish Tech & Emerging**
Teamwork (Cork), Intercom, Wayflyer, Verizon Connect (Dublin), Workday (Dublin), Stripe (Dublin), Zendesk (Dublin), Xperi, Sensata Technologies, Jabil (Blue Sky Innovation)

## Open Questions to Resolve Before Building
- How will the app actually check each company's openings — scraping career pages, using a job-board API (e.g. LinkedIn, Indeed), or a mix?
- Should matches refresh automatically (e.g. daily) or only on-demand when the user runs a search?
- Web app, mobile app, or both?
- Should it store/track applications the user has already made?
