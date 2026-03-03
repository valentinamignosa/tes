[← Back to Infrastructure Hub](/)

# TES — Tracing Eastern Sicily’s Networks (9th–6th centuries BCE) 

## Project Overview

**TES** (www.unive.it/tes) investigates the political, social, and economic dynamics shaping **southeastern Sicily** between the **10th and 6th centuries BCE**, a period preceding and accompanying processes traditionally associated with Greek colonization. 

Rather than analysing sites in isolation, the project approaches the region as an **interconnected landscape**, structured by mobility corridors, environmental constraints, and shared cultural practices.

TES explores how communities interacted within regional systems of exchange, production, and communication, combining archaeological, historical, and epigraphic evidence.

---

## Study Area

The research concentrates on the **Hyblean and southeastern Sicilian region**, defined through environmental connectivity rather than political borders.

River valleys, upland plateaus, and coastal corridors are treated as structuring elements shaping:

- settlement distribution  
- movement routes  
- access to raw materials  
- cultural interaction zones

Geographical limits are therefore analytical tools rather than fixed historical boundaries.

---

## Chronological Framework

TES adopts a **high-resolution chronological model** organised in **25-year intervals (1000–500 BCE)**.

This allows comparison across sites without forcing rigid archaeological periodization and preserves chronological uncertainty as part of historical interpretation.

---

## Data Model

The project database is structured around analytical domains representing observable social practices:

- **Resources** — stone, clay, metals, water systems  
- **Production** — workshops, technologies, craft activity  
- **Storage & circulation** — distribution and economic flows  
- **Cult places** — ritual landscapes and shared practices  
- **Funerary evidence** — markers of social differentiation  
- **Figurative culture** — visual communication and identity  
- **Epigraphy** — writing practices as social action

These categories function as **network indicators**, allowing relationships between sites to emerge from aggregated evidence.

---

## Digital Workflow

TES develops its datasets through a collaborative Digital Humanities workflow.

Data creation and editorial management are carried out using **Cadmus**, the scholarly data framework developed by **Daniele Fusi**, which enables:

- structured scholarly editing  
- controlled vocabularies  
- explicit recording of uncertainty  
- interoperability with external infrastructures

The dataset is designed to integrate with:

- GIS environments  
- spatial network analysis  
- OpenAtlas-compatible infrastructures  
- FAIR and Linked Open Data principles

---

## Research Data Architecture

TES is not structured as a conventional relational database, but as a modular research data environment designed to preserve semantic precision, uncertainty, and long-term sustainability.

### From Tables to Structured Research Objects

Initial datasets were developed in spreadsheet form (Sites, Production, Resources, Inscriptions, etc.). While operationally practical, tabular structures tend to:

- expand horizontally as research questions evolve  
- conceal semantic dependencies between fields  
- blur distinctions between site-level attributes and evidence-level observations  

The Cadmus implementation restructures this logic into:

- **Items (entities)** — autonomous research objects  
- **Parts (modular components)** — reusable analytical units  
- **Thesauri (controlled vocabularies)** — hierarchical or flat taxonomies  
- **Explicit links** — semantic relations between entities  

This architecture allows each analytical observation to remain internally coherent while contributing to broader regional patterns.

---

### Entry-Based Evidence Modeling

A central methodological decision concerns how archaeological evidence is recorded.

Rather than assigning broad categories to sites, TES models:

- each production activity  
- each resource exploitation  
- each inscription  
- each cultic element  

as a **distinct evidence entry**, each with:

- type and classification  
- chronology (25-year resolution)  
- degree of certainty  
- spatial reference (when available)  
- bibliographic source  
- commentary  

This preserves the association between evidence, time, and interpretation, avoiding data flattening.

---

### Chronological Precision and Uncertainty

Chronology is structured in 25-year intervals (1000–500 BCE), enabling:

- cross-site comparability  
- fine-grained temporal analysis  
- preservation of chronological uncertainty  

Uncertainty is recorded explicitly rather than normalised away, reflecting archaeological reality rather than forcing artificial precision.

---

### Spatial Modeling

Spatial data are stored as:

- point coordinates  
- optional radius of approximation  
- polygon geometries (when required)  

This enables:

- export to GIS environments (e.g., PostGIS, QGIS)  
- spatial network analysis  
- preservation of locational precision and approximation  

Spatial uncertainty is treated as analytical information, not as error.

---

### Controlled Vocabularies and External Ontologies
  
Whenever possible, controlled vocabularies are aligned with established international standards and domain ontologies.

This ensures:

- semantic interoperability  
- FAIR compliance  
- reusability beyond the TES environment  
- compatibility with Linked Open Data ecosystems  

Key alignments include:

- **Mapping Ancient Polytheism (MAP)** — for divine entities and cultic references  
- **Getty Art & Architecture Thesaurus (AAT)** — for archaeological materials, object types, technologies, and production categories  
- **Iconographic vocabularies and typological systems** — for figurative representations and visual culture classification  
- **EAGLE vocabularies and FAIR Epigraphy standards** — for epigraphic metadata and inscription typologies  
- **BCP47 language tags** — for linguistic encoding  

Where appropriate, TES maintains local hierarchical thesauri that remain interoperable with these external systems while preserving project-specific analytical nuance.

The goal is not duplication of existing ontologies, but structured alignment and semantic compatibility.

---

### Content–Presentation Separation

Cadmus functions as a structured content creation and research management environment, not as a final publication interface.

This separation ensures:

- long-term data persistence  
- frontend independence  
- interoperability with future platforms  
- sustainability beyond project funding cycles  

The TES editor therefore represents the working scholarly environment in which data are curated, structured, and validated.

---

## Current Development

The project is actively building:

- a structured regional research database  
- interoperable archaeological and epigraphic datasets  
- workflows linking field observation, archival research, and digital modelling

The TES editor and API exposed through this infrastructure represent the **working research environment** rather than a finished publication platform.

---

## Collaboration

TES operates as an **open research environment** and welcomes scholarly exchange with projects addressing ancient connectivity, landscape archaeology, epigraphy, and digital infrastructures.

Ongoing intellectual exchanges connect TES with several international research initiatives and ERC projects working on Mediterranean networks and material culture (see www.unive.it/tes)
