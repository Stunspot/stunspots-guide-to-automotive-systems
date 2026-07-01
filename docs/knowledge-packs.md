# Knowledge Packs — Stunspot's Guide to Automotive Systems

This repository is organized for AI/RAG ingestion. The same canon is available in three packaging formats: individual source reports, grouped compiled packs, and a whole-corpus omnibus.

The right format depends on the target system’s file limits, retrieval behavior, context-window strength, and need for citation precision.

---

## Recommended Default

Use the **compiled packs** unless you have a specific reason not to.

They preserve major conceptual groupings while avoiding both extremes: fifteen separate files or one very large omnibus. For many AI projects, that is the best practical balance.

The compiled-pack set now covers **A-D**, **E-J**, **K-M**, and **N-O**, matching the full A-O source-report sequence.

---

## Pack Types

| Pack | Files | Path | Best Use |
|---|---:|---|---|
| Source reports | 15 | `knowledge-packs/by-report/` | Precise retrieval, selective upload, citation, auditing, editing, and production RAG chunking. |
| Compiled packs | 4 | `knowledge-packs/compiled-packs/` | Recommended default for many AI tools: grouped full-canon coverage with lower file count. |
| Omnibus | 1 | `knowledge-packs/omnibus/` | One-file import, local archive, broad search, or robust long-context/RAG systems. |

---

## Which Format Should I Upload?

### Use source reports when you need precision

Source reports are best when the AI system needs to cite, retrieve, or reason at report-level granularity. They are also the safest format for a production RAG pipeline because each file has a stable topic boundary and path.

Use source reports for:

- citation-aware answers
- selective upload by task
- document-level provenance
- retrieval indexes
- report editing or review
- tasks that need the narrowest possible report-level citation trail

### Use compiled packs when you need practical coverage with fewer files

Compiled packs are best for AI project knowledge slots, NotebookLM-style systems, and long-context workspaces where file count is limited but structure still matters.

Use compiled packs for:

- general automotive reasoning assistants
- model-facing project knowledge
- broad Q&A where citation precision is useful but not strict
- purchase guidance, repair planning, and ownership analysis workflows that need multiple domains at once
- full A-O coverage with fewer files than the source-report set

### Use the omnibus when the system handles large files well

The omnibus is the entire canon in one Markdown file. It is convenient, but it can be too large or too broad for weaker retrieval systems.

Use the omnibus for:

- one-file import
- local archive
- full-corpus search
- robust long-context systems
- systems where file-count limits matter more than retrieval precision

---

## Source Reports

The source reports are the canonical individual units of the corpus.

- [A. Automotive Systems Reality Model - Mobility, Machines, Markets, and Institutions as One Causal System.md](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/a-automotive-systems-reality-model.md)
- [B. Automotive Systems Physics - Motion, Energy, Traction, Heat, Structure, and Control.md](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/b-automotive-systems-physics.md)
- [C. Automotive Systems Architecture - Platforms, Packaging, Interfaces, Modularity, and Design Constraint Logic.md](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/c-automotive-systems-architecture.md)
- [D. Automotive Systems Evolution - Design Eras, Technology Diffusion, Cultural Meaning, and Industrial Change.md](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/d-automotive-systems-evolution.md)
- [E. Automotive Propulsion Systems - Internal Combustion, Hybrid, Electric, Fuel, Air, Heat, and Drivetrain Logic.md](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/e-automotive-propulsion-systems.md)
- [F. Automotive Chassis and Vehicle Dynamics Systems - Suspension, Steering, Brakes, Tires, Handling, Ride, and Road Feel.md](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/f-automotive-chassis-and-vehicle-dynamics-systems.md)
- [G. Automotive Body, Cabin, and Human Interface Systems - Exterior Design, Interior Ergonomics, Safety Space, Visibility, Comfort, and Meaning.md](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/g-automotive-body-cabin-and-human-interface-systems.md)
- [H. Automotive Electrical, Electronic, and Software Systems - Sensors, Networks, Control Modules, Diagnostics, ADAS, Infotainment, and Software-Defined Vehicles.md](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/h-automotive-electrical-electronic-and-software-systems.md)
- [I. Automotive Manufacturing, Supply Chain, and Quality Systems - Factories, Suppliers, Materials, Tolerances, Cost Structures, and Production Reality.md](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/i-automotive-manufacturing-supply-chain-and-quality-systems.md)
- [J. Automotive Market, Ownership, and Lifecycle Economics - Buying, Selling, Depreciation, Financing, Insurance, Maintenance Cost, and Residual Value.md](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/j-automotive-market-ownership-and-lifecycle-economics.md)
- [K. Automotive Safety, Regulation, and Compliance Systems - Crashworthiness, Emissions, Homologation, Liability, Recalls, and Public Risk.md](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/k-automotive-safety-regulation-and-compliance-systems.md)
- [L. Automotive Energy Transition and Environmental Systems - EV Adoption, Hybridization, Fuels, Charging, Batteries, Emissions, and Infrastructure Burdens.md](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/l-automotive-energy-transition-and-environmental-systems.md)
- [M. Automotive Performance, Motorsport, and Modification Systems - Speed, Durability, Rulesets, Tuning, Aftermarket Engineering, and Competitive Trade-Offs.md](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/m-automotive-performance-motorsport-and-modification-systems.md)
- [N. Automotive Failure Modes and Diagnostic Logic - Breakdowns, Wear, Noise, Leaks, Codes, Misfires, Vibrations, Intermittents, and Root Cause Discipline.md](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/n-automotive-failure-modes-and-diagnostic-logic.md)
- [O. Automotive Execution Artifacts and Practitioner Workflows - Inspection Systems, Service Plans, Buying Checklists, Restoration Maps, Build Sheets, and Decision Tools.md](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/o-automotive-execution-artifacts-and-practitioner-workflows.md)

---

## Compiled Packs

- [[KNOWLEDGE] - Automotive Systems - Vol. 1 A-D Automotive Systems Foundations - How the Field Becomes Legible.md](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/compiled-packs/knowledge-automotive-systems-vol-1-a-d-automotive-systems-foundations-how-the-field-becomes-legible.md)  
  Covers the foundational model: automotive reality, physics, architecture, and evolution.

- [[KNOWLEDGE] - Automotive Systems - Vol. 2 E-J Automotive Systems Operating Domains - Where the Real Work Happens.md](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/compiled-packs/knowledge-automotive-systems-vol-2-e-j-automotive-systems-operating-domains-where-the-real-work-happens.md)  
  Covers major operating domains: propulsion, chassis, body/cabin/interface, electrical/software, manufacturing, supply chain, and ownership economics.

- [[KNOWLEDGE] - Automotive Systems - Vol. 3 K-M Automotive Systems Constraints and Specialized Modes - Where Conditions Change the Rules.md](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/compiled-packs/knowledge-automotive-systems-vol-3-k-m-automotive-systems-constraints-and-specialized-modes.md)  
  Covers safety, regulation, compliance, energy transition, environmental systems, performance, motorsport, and modification systems.

- [[KNOWLEDGE] - Automotive Systems - Vol. 4 N-O Automotive Systems Failure, Diagnosis, and Execution - How Knowledge Becomes Judgment.md](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/compiled-packs/knowledge-automotive-systems-vol-4-n-o-automotive-systems-failure-diagnosis-and-execution-how-knowledge-becomes-judgment.md)  
  Covers field judgment: diagnostic logic, failure modes, repair verification, inspection artifacts, service plans, build sheets, restoration maps, and decision tools.

---

## Omnibus

- [[KNOWLEDGE] - Automotive Systems - Omnibus.md](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/omnibus/knowledge-automotive-systems-omnibus.md)
