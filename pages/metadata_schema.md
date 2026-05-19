---
title: Metadata Schema
summary: Standardised machine-readable metadata schema supporting FAIR publication, interoperability, and reuse of health research resources.
type: Tool_assembly
type_img: /assets/img/section-icons/tool-assembly.svg
permalink: /services/metadata-schema
---

# Metadata Schema

## What is this service?

The NFDI4Health Metadata Schema provides a structured framework for describing health research resources in a standardised, machine-readable, and FAIR-aligned way.

It supports the consistent description of:

- clinical studies
- epidemiological studies
- public health studies
- registries
- secondary data sources
- study documentation
- research instruments
- related health research resources

The schema enables metadata publication within the Health Study Hub and supports interoperability between health research infrastructures.

Its modular design allows adaptation to multiple research contexts while preserving semantic consistency.

---

## Quick Access

- [Metadata Schema (ART-DECOR)](https://art-decor.org/ad/#/nfdhtfcov19-/datasets/dataset)
- [FHIR Implementation (Simplifier)](https://simplifier.net)
- [NFDI4Health Helpdesk](https://www.nfdi4health.de/en/helpdesk.html)

---

## Why use this service?

Health research data are often difficult to discover, compare, integrate, and reuse because metadata are incomplete, inconsistent, or non-standardised.

The Metadata Schema helps research teams:

- describe datasets consistently
- improve discoverability
- enable machine readability
- support FAIR publication
- strengthen interoperability
- improve harmonisation readiness
- reduce metadata ambiguity
- support controlled data reuse

Without structured metadata, high-value health data remain difficult to find and assess.

---

## Key Features

### Standardised Metadata Framework

The schema provides a consistent metadata structure for describing health research resources.

This improves:

- metadata completeness
- semantic consistency
- standardised documentation
- cross-study comparability

---

### Modular Architecture

The schema uses a modular design.

This includes:

**Core module**

Captures metadata common across all health research resources.

Examples:

- title
- description
- acronym
- contributors
- identifiers
- provenance
- publication information

---

**Extended modules**

Support resource-specific or domain-specific metadata.

Examples:

- study design
- population
- recruitment
- outcomes
- eligibility criteria
- ethics information
- data sharing conditions

---

### Domain-Specific Extensions

Dedicated modules support domain-specific metadata requirements.

Current examples include:

- nutritional epidemiology
- chronic disease research
- record linkage metadata

Future modules may include:

- imaging
- radiomics
- clinical trials

---

### FAIR Publication Support

The schema enables structured publication of metadata in the Health Study Hub.

This improves:

- findability
- transparency
- structured access discovery
- metadata reuse

---

### Machine Readability

The schema is implemented in machine-readable formats.

Current implementations include:

- ART-DECOR
- HL7 FHIR mappings
- Simplifier FHIR profiles

This supports system interoperability and automated exchange.

---

### Local Data Hub Integration

The Metadata Schema is being implemented within Local Data Hubs.

This supports:

- distributed metadata preparation
- standardised submission
- consistent FAIR publication workflows

---

## How this service supports the research lifecycle

### Study Planning

Teams can define metadata requirements early.

This supports:

- documentation planning
- standardisation
- interoperability readiness
- governance preparation

---

### Study Setup

Researchers can align metadata capture structures before data collection begins.

This improves consistency.

---

### Data Collection

Structured metadata improve documentation of:

- study design
- populations
- instruments
- outcomes
- governance conditions

---

### Data Processing

Consistent metadata improve:

- harmonisation
- transformation documentation
- semantic consistency

---

### Data Sharing

The schema supports structured metadata publication and access discovery.

---

### Reuse

Secondary users can better assess:

- study suitability
- data comparability
- reuse potential
- governance constraints

---

## FAIR Alignment

### Findable

Structured metadata improve discoverability through standardised indexing and searchable descriptions.

---

### Accessible

Metadata describe access conditions even when participant-level data remain protected.

---

### Interoperable

FHIR mappings and standardised semantics support machine-readable interoperability.

---

### Reusable

Rich structured metadata improve interpretability and responsible reuse.

---

## Governance and Sensitive Data Considerations

Health metadata often describe sensitive research involving personal health data.

Important governance considerations include:

- GDPR compliance
- ethical approval context
- access restrictions
- consent conditions
- provenance documentation
- controlled reuse requirements

The schema supports metadata transparency without exposing protected participant-level data.

---

## Practical Workflow Example

### Example Scenario: Cohort Study Registration

A research team prepares a cardiovascular cohort study.

**Step 1 — Define metadata**

The team selects relevant schema modules.

---

**Step 2 — Capture study information**

Metadata are documented consistently using structured schema fields.

---

**Step 3 — Add governance information**

Ethics, access conditions, and provenance details are included.

---

**Step 4 — Export machine-readable metadata**

FHIR-compatible metadata are generated.

---

**Step 5 — Publish via Health Study Hub**

The study becomes discoverable.

---

**Step 6 — Support reuse**

External researchers can assess suitability and access pathways.

---

## Related NFDI4Health Services

This service connects closely with:

- Health Study Hub
- Local Data Hub
- Terminology Service
- Harmonisation
- Data Quality
- FAIR Training
- Helpdesk

---

## Technical Background

The Metadata Schema originated from NFDI4Health Task Force COVID-19 work.

Although initially tailored to COVID-19 studies, the schema was intentionally designed generically to support broader health research use cases.

Metadata concepts were adapted from established standards and resources including:

- DataCite
- ClinicalTrials.gov
- DRKS
- Maelstrom
- MIABIS

This strengthens interoperability and long-term maintainability.

---

## Support and External Resources

For support:

- [NFDI4Health Helpdesk](https://www.nfdi4health.de/en/helpdesk.html)

Technical resources:

- [ART-DECOR Metadata Schema](https://art-decor.org/ad/#/nfdhtfcov19-/datasets/dataset)
- [FHIR Profiles (Simplifier)](https://simplifier.net)
