# Anahita Shrestha's Clean & Green Website Portfolio Guide

PURPOSE
-------
This portfolio compiles three energy-system designs as part of Anahita Shrestha's Clean & Green Portfolio.
Each design is presented with a block diagram/architecture and a concise, technical
explanation that covers:
1) Source of energy, 
2) Conversion process, 
3) Output/Utilization, 
4) Real‑world relevance.

PROBLEM STATEMENT (COURSE BRIEF)
--------------------------------
“Choose three topics from the list and present a portfolio‑ready block diagram with a brief
explanation.” The objective is to show clear system thinking, appropriate technology selection,
and practical deployment considerations for decentralized/clean energy systems.

SELECTED ACTIVITIES (THIS PORTFOLIO)
------------------------------------
Activity 1: Biogas System for a 100‑Cattle Dairy Farm
- Goal: Convert manure into useful energy (biogas) and valuable fertilizer (digestate).
- Architecture focus: Mesophilic anaerobic digestion (~35 °C, 30–40 days HRT) with a
  gas‑conditioning train (moisture trap + H₂S scrubber), low‑pressure gas holder,
  and three utilization paths: (A) CHP (power + hot water), (B) direct burners,
  (C) upgrading to Bio‑CNG. Digestate management via solid–liquid separation.
- Explainer covers: Feedstock quantity and suitability; biogas composition/yield;
  conditioning steps; safety (PRV, flame arrestor, LEL detection); uses of gas;
  nutrient‑loop closure and farm economics.

Activity 2:  Hybrid Solar PV + Wind for a Rural Health Clinic
- Goal: Ensure reliable, low‑carbon power for clinic critical loads (vaccine fridge,
  lights, communications, lab) with minimal diesel dependence.
- Architecture focus: Complementary resources (PV day; wind evening/monsoon) on a
  common DC bus: PV via MPPT; wind via rectifier + controller (dump load). LiFePO₄
  battery for autonomy; hybrid inverter/charger for clean AC, islanding, and black‑start;
  ATS for grid/diesel fallback. AC board split into critical vs non‑critical circuits.
- Explainer covers: Resource complementarity; EMS scheduling (time‑shift heavy loads
  to solar noon; SoC thresholds); dispatch order; protections (SPDs, RCD/MCB, earthing);
  outcomes for cold‑chain reliability and OPEX/CO₂ reduction.

Activity 3: Geothermal Power Plant (Hot‑Water Wells)
- Goal: Produce baseload electricity by matching cycle to reservoir conditions.
- Architecture focus: Two conversion branches selected by measured temperature:
  Flash steam (>180 °C) to steam turbine, or Binary/ORC (120–180 °C) using a
  low‑boiling working fluid. Closed‑loop reinjection sustains reservoir pressure;
  chemistry management (H₂S, silica/scale) protects equipment; heat rejection via
  ACC or cooling tower per climate. Grid export via step‑up transformer + switchyard.
- Explainer covers: Resource type (liquid‑dominated brine); cycle selection logic;
  reinjection rationale; operational protections; baseload characteristics and land/water footprint.

WHAT EACH ACTIVITY PAGE CONTAINS
--------------------------------
1) Summary: One‑paragraph overview of the system’s intent and core idea.
2) Block Diagram: A single figure showing end‑to‑end flow.
3) “Why this Architecture?”: A short, high‑signal paragraph with bold highlights
   explaining the design choice and decision logic.
4) Explainer: Four sections, Source of energy, Conversion
   process, Output/Utilization, Real‑world relevance optimized for quick grading and clarity.
5) Quick Specs: Bullet list of key parameters and interfaces.
6) Legend: Visual key for Power/Energy, Heat, Control, and Safety elements.

AUDIENCE & READING GUIDE
------------------------
- For reviewers: Skim the Summary and “Why this Architecture?” to see decision quality,
  then check Explainer bullets for technical completeness.
- For non‑specialists: Use the Legend to decode the diagram first, then read the Explainer
  in order; bold phrases surface the key ideas quickly.

ASSUMPTIONS & SCOPE
-------------------
- Sizing values are representative and meant for portfolio exposition; real projects require
  site‑specific resource assessment, load profiling, and local code compliance.
- Safety and environmental controls are included at a conceptual level (final design needs
  standards‑based engineering and permitting).

LEARNING OUTCOMES DEMONSTRATED
------------------------------
- Mapping a resource to an appropriate conversion pathway (fit‑for‑resource).
- Designing energy paths, storage/conditioning, and safe operations (fit‑for‑use).
- Communicating complex systems with clean diagrams and concise, structured explanations.
---------------
