# How to Use This Canon

*Stunspot's Guide to Automotive Systems* is built for model-facing use first and human reading second. Treat it as a structured knowledge substrate for automotive reasoning: definitions, causal models, system boundaries, field diagnostics, lifecycle economics, and execution artifacts.

Use the canon to help an AI system reason more like a careful automotive systems analyst: mechanism-first, evidence-aware, repair-aware, cost-aware, safety-aware, and explicit about uncertainty.

---

## Directory Policy

This repository separates navigation from corpus material.

| Layer | Path | Role |
|---|---|---|
| GitHub Pages navigation | `docs/` | Landing page, canon map, usage guide, knowledge-pack guide, layout, CSS, and future brand assets. |
| Source reports | `knowledge-packs/by-report/` | Canonical individual report files. Best for precise retrieval, selective upload, citation, and auditing. |
| Compiled packs | `knowledge-packs/compiled-packs/` | Grouped upload files for AI projects and RAG workflows that prefer fewer files. |
| Omnibus | `knowledge-packs/omnibus/` | Whole-corpus bundle for one-file import, archive, or robust long-context systems. |

There is no `docs/reports/` directory. The source corpus lives in `knowledge-packs/by-report/`.

---

## Recommended Upload Strategy

| Situation | Use | Why |
|---|---|---|
| You want the safest default for an AI project with limited file slots | **Compiled packs** | Fewer files, coherent groupings, strong report boundaries. |
| You need precise citations or selective retrieval | **Source reports** | Each report remains an independent unit with a clear title and topic boundary. |
| You need one-file import or offline search | **Omnibus** | Entire corpus in one Markdown file. |
| You are building a production RAG pipeline | **Source reports + manifest.json** | Preserves metadata, source-to-output mappings, and report-level retrieval granularity. |
| You are running a long-context exploratory session | **Omnibus or targeted source reports** | Omnibus gives breadth; targeted reports reduce distraction and middle-context decay. |

This release includes compiled packs for **A-D**, **E-J**, and **N-O**. Reports **K-M** are available as individual source reports and are included in the omnibus, but they are not currently packaged as a separate compiled Vol. 3 bundle.

---

## How to Instruct an AI Model

Use a directive that makes the canon operational rather than decorative.

> Analyze the automotive question using *Stunspot's Guide to Automotive Systems* as governing reference material. Treat the canon as a systems model, not background reading. Retrieve and apply its vocabulary, causal frames, failure modes, lifecycle economics, diagnostic discipline, and artifact logic. Distinguish symptoms from causes, claims from evidence, components from systems, and ownership lore from measurable duty-cycle reality. When recommending action, make the reasoning testable, repair-aware, cost-aware, safety-aware, and explicit about uncertainty.

For diagnostic tasks, add:

> Do not treat a diagnostic trouble code as a parts-replacement instruction. Separate complaint, symptom, sign, measured abnormality, failure mode, failed component, causal mechanism, root cause, repair action, and repair verification. Prefer discriminating tests over pattern guessing.

For buying or ownership tasks, add:

> Evaluate the vehicle as a lifecycle object: acquisition cost, depreciation, duty cycle, maintenance behavior, insurance exposure, repair ecosystem, parts availability, known failure modes, regulatory constraints, and resale implications.

For modification or restoration tasks, add:

> Evaluate the build as an integrated system. Check whether power, braking, cooling, tires, chassis stiffness, drivetrain durability, legal compliance, budget reserve, serviceability, and intended duty cycle remain balanced.

---

## Suggested Human Reading Paths

### For vehicle purchase and ownership decisions

Start with:

1. [A. Automotive Systems Reality Model](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/a-automotive-systems-reality-model.md)
2. [J. Automotive Market, Ownership, and Lifecycle Economics](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/j-automotive-market-ownership-and-lifecycle-economics.md)
3. [N. Automotive Failure Modes and Diagnostic Logic](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/n-automotive-failure-modes-and-diagnostic-logic.md)
4. [O. Automotive Execution Artifacts and Practitioner Workflows](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/o-automotive-execution-artifacts-and-practitioner-workflows.md)

### For repair, troubleshooting, and service planning

Start with:

1. [H. Automotive Electrical, Electronic, and Software Systems](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/h-automotive-electrical-electronic-and-software-systems.md)
2. [E. Automotive Propulsion Systems](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/e-automotive-propulsion-systems.md)
3. [F. Automotive Chassis and Vehicle Dynamics Systems](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/f-automotive-chassis-and-vehicle-dynamics-systems.md)
4. [N. Automotive Failure Modes and Diagnostic Logic](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/n-automotive-failure-modes-and-diagnostic-logic.md)
5. [O. Automotive Execution Artifacts and Practitioner Workflows](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/o-automotive-execution-artifacts-and-practitioner-workflows.md)

### For vehicle design, architecture, and engineering trade-offs

Start with:

1. [B. Automotive Systems Physics](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/b-automotive-systems-physics.md)
2. [C. Automotive Systems Architecture](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/c-automotive-systems-architecture.md)
3. [E. Automotive Propulsion Systems](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/e-automotive-propulsion-systems.md)
4. [F. Automotive Chassis and Vehicle Dynamics Systems](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/f-automotive-chassis-and-vehicle-dynamics-systems.md)
5. [H. Automotive Electrical, Electronic, and Software Systems](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/h-automotive-electrical-electronic-and-software-systems.md)

### For EVs, hybrids, energy transition, and environmental claims

Start with:

1. [A. Automotive Systems Reality Model](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/a-automotive-systems-reality-model.md)
2. [E. Automotive Propulsion Systems](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/e-automotive-propulsion-systems.md)
3. [H. Automotive Electrical, Electronic, and Software Systems](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/h-automotive-electrical-electronic-and-software-systems.md)
4. [L. Automotive Energy Transition and Environmental Systems](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/l-automotive-energy-transition-and-environmental-systems.md)
5. [K. Automotive Safety, Regulation, and Compliance Systems](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/k-automotive-safety-regulation-and-compliance-systems.md)

### For modification, motorsport, and restoration planning

Start with:

1. [B. Automotive Systems Physics](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/b-automotive-systems-physics.md)
2. [F. Automotive Chassis and Vehicle Dynamics Systems](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/f-automotive-chassis-and-vehicle-dynamics-systems.md)
3. [M. Automotive Performance, Motorsport, and Modification Systems](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/m-automotive-performance-motorsport-and-modification-systems.md)
4. [N. Automotive Failure Modes and Diagnostic Logic](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/n-automotive-failure-modes-and-diagnostic-logic.md)
5. [O. Automotive Execution Artifacts and Practitioner Workflows](https://github.com/Stunspot/stunspots-guide-to-automotive-systems/blob/main/knowledge-packs/by-report/o-automotive-execution-artifacts-and-practitioner-workflows.md)

---

## Practical Guardrails

- Treat the canon as a reasoning aid, not a substitute for current service manuals, OEM procedures, safety standards, recall databases, or local law.
- Verify safety-critical, legal, financial, and repair decisions against primary sources and qualified professionals.
- Preserve report titles and file paths when citing or chunking the corpus.
- For RAG, keep provenance metadata tied to each source report so generated answers can trace claims back to the correct file.
- For diagnostics, require measured evidence before recommending parts replacement.
