# Diego Prada-Gracia, PhD

**Theoretical Physicist · Computational Biologist · Scientific Software Architect**  
*Molecular Simulation • Statistical Mechanics • Scientific Computing • AI for Molecular Science*

> Co-directing computational biophysics research and architecting robust scientific software platforms: from non-equilibrium statistical mechanics to high-performance engines in Rust, Python, and TypeScript.

[![UIBCDF](https://img.shields.io/badge/Lab-UIBCDF.org-2b5b84?logo=google-chrome&logoColor=white)](https://www.uibcdf.org)
[![Google Scholar](https://img.shields.io/badge/Google-Scholar-4285F4?logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?user=RDB1Sc0AAAAJ)
[![ORCID](https://img.shields.io/badge/ORCID-0000--0003--3375--870X-A6CE39?logo=orcid&logoColor=white)](https://orcid.org/0000-0003-3375-870X)
[![GitHub Org](https://img.shields.io/badge/Organization-@uibcdf-181717?logo=github&logoColor=white)](https://github.com/uibcdf)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-diego--prada--gracia-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/diego-prada-gracia/)

---

### Executive Summary
I work at the intersection of theoretical physics, computational molecular science, and software platform architecture. I formulate physical models of biomolecular kinetics and construct the modular software abstractions required to translate mathematical theory into reproducible, high-throughput pipelines.

I co-direct the **Computational Biology and Drug Design Research Unit ([UIBCDF](https://www.uibcdf.org))** and lead the architecture of **[MolSysSuite](https://github.com/uibcdf/molsyssuite)**, an open-source scientific computing platform for molecular modeling, simulation, and AI-assisted workflows.

**Core Technical Foundation:**
* **Languages & Production Stack:** Libraries and platform built across **Python** (scientific stack, data science, biophysical modeling), **Rust** (memory-safe accelerated compute kernels), and **TypeScript** (modern web visualizers and frontends). Formative background in native **Fortran** for classical numerical physics.
* **Engineering & Delivery:** Automated CI/CD pipelines, agent-ready testing tooling, Linux environments, Conda packaging, and multi-platform distribution.

---

### 🏛️ The MolSysSuite Platform ([@uibcdf](https://github.com/uibcdf) • Permissive / MIT)
Rather than a loose collection of research scripts, MolSysSuite is engineered as an **agent-ready, layered scientific computing architecture** designed to reduce glue-code complexity and manage interoperability across heterogeneous molecular-science ecosystems:

* **[ AI & Orchestration ]** → `molsys-ai`
* **[ Domain & Modeling ]** → `MolSysMT` · `TopoMT` · `MolSysViewer` · `ElasNetMT`
* **[ Core Contracts & Telemetry ]** → `PyUnitWizard` · `ArgDigest` · `DepDigest` · `SMonitor`
* **[ Native Compute & Automation ]** → Rust Accelerated Kernels · TypeScript · `pytest-receptor` · Conda Packaging

#### Flagship Components
* **[MolSysMT](https://github.com/uibcdf/molsysmt):** Unified molecular systems toolkit providing syntactic consistency and transparent conversion across 10+ heterogeneous engines and formats (OpenMM, MDTraj, MDAnalysis, PDB, etc.), powered by accelerated compute backends in **Rust**.
* **[molsys-ai](https://github.com/uibcdf/molsys-ai):** Agentic interface translating high-level biophysical queries into structured, inspectable, and reproducible MolSysSuite execution pipelines.
* **[TopoMT](https://github.com/uibcdf/topomt):** Geometric and topographic characterization of molecular surfaces, binding pockets, cavities, and transport tunnels.
* **[MolSysViewer](https://github.com/uibcdf/molsysviewer):** High-performance 3D molecular visualization widget for Jupyter environments built on Mol* with a clean, programmatic API in **TypeScript** and **Python**.

#### Scientific Infrastructure & Core Contracts
* **[PyUnitWizard](https://github.com/uibcdf/PyUnitWizard):** Universal adapter and orchestration layer for physical quantities and unit libraries (Pint, OpenMM Units, Unyt), ensuring dimensional safety across codebases.
* **[ArgDigest](https://github.com/uibcdf/argdigest):** Contract-based argument auditing, type normalization, and introspection layer to decouple input validation from scientific logic and enable deterministic agent introspection.
* **[DepDigest](https://github.com/uibcdf/depdigest):** Lazy-loading dependency manager eliminating startup overhead when interfacing with heavy optional scientific libraries.
* **[SMonitor](https://github.com/uibcdf/smonitor):** Centralized telemetry, structured diagnostics, and event routing layer across heterogeneous Python libraries.
* **[pytest-receptor](https://github.com/uibcdf/pytest-receptor):** Specialized test reporter for CI/CD and coding agents—compact, root-cause-grouped verdicts optimized for reliable interpretation by coding agents.

---

### 📊 Selected Impact & Track Record
* **Peer-Reviewed Science:** Author of 30+ publications in computational biophysics and statistical mechanics with 1,000+ total citations.
* **Key Publications:**
  - *Conformational Markov Networks:* [Exploring the free energy landscape: from dynamics to networks and back](https://doi.org/10.1371/journal.pcbi.1000495) (*PLoS Comput. Biol.*, 2009) — Pioneering graph-theoretical framework mapping molecular trajectories into discrete kinetic networks.
  - *Allosteric & Receptor Dynamics:* [Conformational transitions and activation mechanisms in GPCRs](https://doi.org/10.1016/j.bpj.2014.11.1925) (*Biophys. J.*) — Kinetic decomposition of activation pathways and free energy landscape transitions.
* **Architecture & Interoperability:** Designed cross-engine bridges in MolSysMT connecting over 10 major structural biology formats without mandatory vendor lock-in.
* **Ecosystem Governance:** Maintainer of the **UIBCDF Conda channel**, orchestrating automated multi-platform builds, reproducible recipes, and environment deployment for open science.
* **Open Source Stewardship:** 10+ actively maintained repositories under `@uibcdf` distributed under permissive open-source licenses (MIT / LGPL).

---

### 🔬 Scientific Leadership & Team Direction
* **Unit Co-Direction:** Co-PI and Senior Researcher at the **[UIBCDF](https://www.uibcdf.org)** (Hospital Infantil de México Federico Gómez, Mexican National Institutes of Health).
* **People & Project Leadership:** Supervised and mentored graduate researchers, postdocs, and technical staff across molecular simulation, statistical physics, and scientific software engineering.
* **Research Program:** Focused on mechanistic computational biology:
  - **Statistical Mechanics & Molecular Kinetics:** Conformational Markov Networks, transition networks, metastable states, and non-equilibrium free energy surfaces.
  - **Computational Biophysics & Simulation:** Multiscale dynamics of allosteric regulation, GPCR activation pathways, and membrane biophysics.
  - **Molecular Modeling & Drug Discovery:** Quantitative thermodynamic binding validation, cell-penetrating peptides (CPPs), and structure-guided pharmacological design.

---

### ⚙️ Engineering Principles
- **Physics-Aware by Design:** Abstractions preserve physical units, structural semantics, conservation laws, and reproducible statistical sampling.
- **Contract-Driven & Agent-Ready:** Clean separation between validation contracts (`ArgDigest`), runtime performance, and business logic to ensure deterministic behavior for human developers and autonomous coding agents.
- **Reproducible Packaging & Delivery:** Automated multi-platform CI/CD testing, structured telemetry, and unified Conda distribution to eliminate setup barriers.

---

📍 **Laboratory:** [UIBCDF](https://www.uibcdf.org) — Hospital Infantil de México Federico Gómez (Mexico City)  
✉️ **Contact:** `diego.prada.gracia [at] gmail.com`
