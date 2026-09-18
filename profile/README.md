# Janssen Lab — Materials Informatics

We are the **Materials Informatics Group** at the [Max Planck Institute for Sustainable Materials](https://www.mpie.de/5013829/matinf), led by **Jan Janssen**.

Our group brings together **computational materials science, thermodynamics, machine learning, scientific software, high-performance computing, and AI for science**. We develop methods and open-source infrastructure that make materials simulations **reproducible, scalable, interoperable, and increasingly autonomous**.

> **Materials science → workflows → HPC → machine learning → agentic science**

## Research

Our research spans several complementary areas:

- **Atomistic simulation & thermodynamics** — from electronic structure and atomistic simulation to free energies and phase stability
- **Machine learning for materials** — interatomic potentials, statistical sampling, and data-driven materials discovery
- **Uncertainty & validation** — convergence studies and propagation of computational uncertainties
- **Scientific workflows & HPC** — reusable workflows, interoperability, provenance, and scalable execution
- **AI for science** — LLM-based agents that construct, execute, and validate scientific workflows

This diversity allows us to connect methodological developments across the full computational research process rather than treating simulation, machine learning, and computing infrastructure as isolated problems.

## Software

We treat **scientific software as a research output**. Automated testing, reproducibility, interoperability, and sustainable software engineering are integral parts of our work. Many projects intentionally live in community organizations rather than under `janssenlab`.

| Project | Purpose | Publication | Coverage | GitHub Stars |
|---|---|---|---|---|
| [pyiron/pysqa](https://github.com/pyiron/pysqa) (2026) | HPC queuing system adapter | [JOSS](https://doi.org/10.21105/joss.10961) | [![codecov](https://codecov.io/gh/pyiron/pysqa/graph/badge.svg?token=N753OWIAUW)](https://codecov.io/gh/pyiron/pysqa) | ![GitHub Repo stars](https://img.shields.io/github/stars/pyiron/pysqa) |
| [pyiron/executorlib](https://github.com/pyiron/executorlib) (2025) | Scale Python functions to HPC | [JOSS](https://doi.org/10.21105/joss.07782) | [![codecov](https://codecov.io/gh/pyiron/executorlib/graph/badge.svg?token=KFIO3R08H3)](https://codecov.io/gh/pyiron/executorlib) | ![GitHub Repo stars](https://img.shields.io/github/stars/pyiron/executorlib) |
| [pythonworkflow/python-workflow-definition](https://github.com/pythonworkflow/python-workflow-definition) (2025) | Workflow interoperability | [Digital Discovery](https://doi.org/10.1039/D5DD00231A) | [![codecov](https://codecov.io/github/pythonworkflow/python-workflow-definition/graph/badge.svg?token=3JXD1GN8LG)](https://codecov.io/github/pythonworkflow/python-workflow-definition) | ![GitHub Repo stars](https://img.shields.io/github/stars/pythonworkflow/python-workflow-definition) |
| [jan-janssen/LangSim](https://github.com/jan-janssen/LangSim) (2025) | LLM agents for atomistic simulation | [MLST](http://doi.org/10.1088/2632-2153/ae011a) | — | ![GitHub Repo stars](https://img.shields.io/github/stars/jan-janssen/LangSim) |
| [pyiron/pyiron](https://github.com/pyiron/pyiron) (2019) | Computational materials science environment | [CMS](https://doi.org/10.1016/j.commatsci.2018.07.043) | — | ![GitHub Repo stars](https://img.shields.io/github/stars/pyiron/pyiron) |

## Teaching & community

**Training the next generation of computational materials scientists is an integral part of our work.**

We develop open teaching material and regularly contribute lectures and hands-on tutorials covering the spectrum from **programming and DFT to machine learning, atomistic simulation, scientific workflows, and HPC**.

**📝 Event · 📚 Material · 📦 Source · 📺 Video**

### Tutorials

| Tutorial | Year | Event | Material | Source | Video |
|:---|:---:|:---:|:---:|:---:|:---:|
| NFDI-MatWerk Summer School — pyiron | 2026 | [📝](https://www.eusmat.net/research/other-events/nfdi-matwerk-summer-school-2026/) | [📚](http://workshop.pyiron.org/NFDI-summerschool-2026/) | [📦](https://github.com/pyiron-workshop/NFDI-summerschool-2026) | |
| LANL — executorlib / HPC workflows | 2026 | | [📚](https://workshop.pyiron.org/lanl-executorlib-tutorial) | [📦](https://github.com/pyiron-workshop/lanl-executorlib-tutorial) | |
| LANL — pyiron | 2025 | | [📚](http://workshop.pyiron.org/lanl-tutorial-2025/) | [📦](https://github.com/pyiron-workshop/lanl-tutorial-2025) | |
| IMSI — Data-Driven Materials Informatics | 2024 | [📝](https://www.imsi.institute/activities/data-driven-materials-informatics/) | [📚](https://workshop.pyiron.org/imsi-tutorial/) | [📦](https://github.com/pyiron-workshop/imsi-tutorial) | |
| LAMMPS Virtual Workshop | 2023 | [📝](https://www.lammps.org/workshops/Aug23/) | [📚](http://workshop.pyiron.org/lammps-workshop-2023) | [📦](https://github.com/pyiron-workshop/lammps-workshop-2023) | |
| Simulation Workflows in Materials Modelling (SWiMM) | 2021 | [📝](https://www.cecam.org/workshop-details/27) | [📚](http://workshop.pyiron.org/swimm-workshop-2021/) | [📦](https://github.com/pyiron-workshop/swimm-workshop-2021) | [📺](https://www.youtube.com/playlist?list=PL7AkGfbmuLRQeJ-Koq_6m99Lq4mueF2L-) |
| Software Tools from Atomistics to Phase Diagrams | 2020 | | [📚](https://workshop.pyiron.org/phasediagram-workshop-2020/) | [📦](https://github.com/pyiron-workshop/phasediagram-workshop-2020) | [📺](https://www.youtube.com/playlist?list=PL7AkGfbmuLRReeaQmsTl-vaDyEZR8ROkx) |
| Atomistic Simulations for Industrial Needs | 2020 | [📝](https://www.nist.gov/news-events/events/2020/08/atomistic-simulations-industrial-needs) | | [📦](https://github.com/pyiron-workshop/NIST-workshop-2020) | [📺](https://www.youtube.com/watch?v=jQGYUgJK3Ug) |

Additional workshop material is maintained in the [pyiron-workshop](https://github.com/pyiron-workshop) organization.

### Lectures

| Lecture | Year | Material | Source |
|:---|:---:|:---:|:---:|
| Heinrich Heine University — Density Functional Theory | 2026 | [📚](https://janssenlab.github.io/2026-HHU-lecture/) | [📦](https://github.com/janssenlab/2026-HHU-lecture) |
| Ruhr University Bochum — Programming Concepts in Materials Science | 2025 | | [📦](https://github.com/janssenlab/2025-RUB-Programming-Concepts-in-Materials-Science-Lecture) |
| SusMet — Machine Learning in Materials Science | 2025 | [📚](https://janssenlab.github.io/2025-SusMet-Machine-Learning-Workshop/) | [📦](https://github.com/janssenlab/2025-SusMet-Machine-Learning-Workshop) |
| University of Birmingham — Atomistic Simulation | 2025 | [📚](https://janssenlab.github.io/2025-Birmingham-University-Atomistic-Simulation-Lecture/) | [📦](https://github.com/janssenlab/2025-Birmingham-University-Atomistic-Simulation-Lecture) |
| SusMet — Density Functional Theory | 2024 | [📚](https://janssenlab.github.io/2024-SusMet-Density-Functional-Theory-Lecture/) | [📦](https://github.com/janssenlab/2024-SusMet-Density-Functional-Theory-Lecture) |

## Collaboration

We collaborate across **experimental and computational materials science, machine learning, AI for science, HPC, and research software engineering**.

Our contribution is often to connect scientific expertise with computational infrastructure — turning methods into **reusable, scalable, and inspectable workflows** and transferring these capabilities to collaborators and students.

More about our research and team: [Materials Informatics at MPI SusMat](https://www.mpie.de/5013829/matinf)
