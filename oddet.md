---
title: ODDET
---

# ODDET — Origin–Destination Data Evaluation Tool

## Overview

ODDET is a graph-based computational framework for large-scale Origin–Destination (OD) matrix analysis and metropolitan mobility diagnostics.

The framework operates on real road-network topology structured as a weighted graph, where multi-source and multi-target shortest-path computations (based on Dijkstra’s algorithm) are used to derive interzonal traversal structures and edge-level flow allocation patterns.

ODDET originates from the research project:

**APQ-04889-24 — “Inferring Modal Split from Mobile Phone–Derived Origin–Destination Matrices”**, under the general coordination of **Prof. Dr. Guilherme de Castro Leiva**.

The project seeks to evaluate and propose methodological alternatives for qualifying mobile phone-derived OD matrices, particularly regarding modal split inference for metropolitan transport planning in the Belo Horizonte Metropolitan Region (RMBH).

Within this initiative, my role focuses on:

- Graph-model architecture design  
- Multi-source shortest-path analytical structure  
- Traversal-flow diagnostics  
- Percentile-based OD filtering strategies  
- Structured computational pipelines for large OD datasets  

ODDET v1.0 constitutes the analytical infrastructure layer supporting structural diagnostics and network-based evaluation of OD matrices.

Institutional deployment is planned on a dedicated server to enable controlled remote research access.

---

## Research Context

The broader project investigates the methodological limitations of mobile phone-derived OD datasets for operational transport planning, particularly concerning modal split inference.

Preliminary assessments indicate that while CDR-based OD matrices support strategic-level urban analysis (e.g., centralities, behavioral patterns), their applicability to operational transport planning remains limited due to structural data constraints related to data collection, aggregation, and base structure.

ODDET addresses this gap by providing a network-theoretic diagnostic layer capable of evaluating:

- Interzonal traversal structures  
- Network connectivity patterns  
- Edge-level load distributions  
- Structural biases in OD matrices  

Multiple conference papers derived from the ODDET analytical architecture are currently under peer review.

---

## Development Status

- Version: ODDET v1.0 (analytical infrastructure consolidation)
- Institutional server deployment planned
- INPI software registration in preparation
- Technical manual (book format, DOI and ISBN) in development

---

## Publications Related to ODDET

### Under Review

- International conference paper on interzonal traversal diagnostics and percentile-based OD filtering (under review).
- Journal manuscript on structural analysis of metropolitan OD systems derived from mobile phone data (under review).

---

## Future Goals — ODDET v2.0 (Feb 2027)

ODDET v2.0 aims to incorporate modal inference capabilities consistent with the objectives of APQ-04889-24.

Planned developments include:

- Statistical and probabilistic models for transport mode inference from CDR-derived OD matrices  
- Integration of auxiliary datasets (network topology, zoning characteristics, calibration datasets)  
- Sensitivity analysis under spatial aggregation and privacy constraints  
- Development of a meso-scale modal attribution layer associated with network traversal structures  
- Extension toward macro–meso–micro analytical integration  

The objective is to evolve ODDET from structural OD diagnostics toward enriched metropolitan mobility characterization capable of supporting operational transport planning.
