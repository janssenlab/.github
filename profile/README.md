# Janssen Lab — Materials Informatics

We are the **Materials Informatics group** at the [Max Planck Institute for Sustainable Materials](https://www.mpie.de/5013829/matinf), led by **Jan Janssen**.

Our research focuses on the computational infrastructure that connects **materials simulation, machine learning, high-performance computing, and scientific workflows**. We develop methods and open-source tools that turn expert computational procedures into **reproducible, scalable, interoperable, and increasingly autonomous research workflows**.

> **Materials science → Scientific workflows → HPC → Machine learning → Agentic science**

## What we research

Our goal is to make computational materials science easier to automate, reproduce, scale, and integrate across methods.

Key research directions include:

- **Automated atomistic simulation and thermodynamics** — from electronic-structure calculations and atomistic simulations to free energies and phase stability.
- **Uncertainty and convergence** — systematic convergence studies and propagation of computational uncertainties through simulation workflows.
- **Machine learning for materials science** — machine-learned interatomic potentials, statistical sampling, and data-driven exploration of materials.
- **Scientific workflows and interoperability** — reusable workflow components, provenance, portability, and interfaces between workflow systems.
- **High-performance computing** — scaling Python-based scientific workflows from local computers to HPC and exascale environments.
- **Agentic science** — enabling LLM-based agents to construct, execute, inspect, and validate scientific workflows using trusted computational building blocks.

## What we build

The projects below are developed, led, or substantially contributed to by members of the Materials Informatics group. Many intentionally live in community organizations rather than under `janssenlab`.

| Project | Purpose | Publication | Coverage | GitHub Stars |
|---|---|---|---|---|
| [pyiron/pysqa](https://github.com/pyiron/pysqa) (2026) | Simple HPC queuing system adapter | [Journal of Open Source Software](https://doi.org/10.21105/joss.10961) | [![codecov](https://codecov.io/gh/pyiron/pysqa/graph/badge.svg?token=N753OWIAUW)](https://codecov.io/gh/pyiron/pysqa) | ![GitHub Repo stars](https://img.shields.io/github/stars/pyiron/pysqa) |
| [pyiron/executorlib](https://github.com/pyiron/executorlib) (2025) | Scale Python functions from local execution to HPC | [Journal of Open Source Software](https://doi.org/10.21105/joss.07782) | [![codecov](https://codecov.io/gh/pyiron/executorlib/graph/badge.svg?token=KFIO3R08H3)](https://codecov.io/gh/pyiron/executorlib) | ![GitHub Repo stars](https://img.shields.io/github/stars/pyiron/executorlib) |
| [pythonworkflow/python-workflow-definition](https://github.com/pythonworkflow/python-workflow-definition) (2025) | Workflow interoperability standard | [Digital Discovery](https://doi.org/10.1039/D5DD00231A) | [![codecov](https://codecov.io/github/pythonworkflow/python-workflow-definition/graph/badge.svg?token=3JXD1GN8LG)](https://codecov.io/github/pythonworkflow/python-workflow-definition) | ![GitHub Repo stars](https://img.shields.io/github/stars/pythonworkflow/python-workflow-definition) |
| [jan-janssen/LangSim](https://github.com/jan-janssen/LangSim) (2025) | LLM agents for atomistic simulation | [Machine Learning: Science and Technology](http://doi.org/10.1088/2632-2153/ae011a) | | ![GitHub Repo stars](https://img.shields.io/github/stars/jan-janssen/LangSim) |
| [pyiron/pyiron](https://github.com/pyiron/pyiron) (2019) | Integrated development environment for computational materials science | [Computational Materials Science](https://doi.org/10.1016/j.commatsci.2018.07.043) | | ![GitHub Repo stars](https://img.shields.io/github/stars/pyiron/pyiron) |

## What we enable

Rather than treating individual simulation codes, machine-learning models, and computing resources as isolated tools, we connect them into reusable computational research processes.

Typical workflows include:

**Electronic structure → atomistic models → free energies → phase stability**

**Scientific method → automated convergence → uncertainty-aware result**

**Python function → workflow → remote execution → HPC**

**Scientific hypothesis → agent → simulation workflow → validation**

This infrastructure allows collaborators to focus on the scientific question while retaining transparency and control over the underlying computational methodology.

## Collaboration

We are interested in collaborations at the interface between **materials science, scientific computing, machine learning, and research software engineering**.

In particular, our group can contribute:

- **Method integration** — connecting electronic structure, atomistics, thermodynamics, machine learning, and experimental data.
- **Workflow automation** — translating expert computational procedures into reusable and inspectable workflows.
- **HPC scaling** — moving scientific workflows from notebooks and workstations to distributed computing resources.
- **Reproducibility and provenance** — making computational procedures and their results traceable and reusable.
- **Interoperability** — connecting scientific tools and workflow systems without requiring a monolithic software stack.
- **AI-ready scientific infrastructure** — exposing validated scientific components to LLM-based agents while preserving explicit workflows and provenance.
- **Knowledge transfer** — providing tutorials, workshops, and teaching materials that help collaborators adopt the resulting methods.

We are particularly interested in working with groups that bring complementary expertise in **experimental materials science, electronic-structure theory, atomistic simulation, thermodynamics, machine learning, AI for science, or high-performance computing**.

## Tutorials

We regularly provide hands-on tutorials on scientific workflows, atomistic simulation, and HPC.

| Workshop Title | Year | Workshop | Website | Repository | Videos |
|:---------------|:-----|:--------:|:-------:|:----------:|:------:|
| NFDI MatWerk Summer School — pyiron Tutorial | 2026 | [:memo:](https://www.eusmat.net/research/other-events/nfdi-matwerk-summer-school-2026/) | [:books:](http://workshop.pyiron.org/NFDI-summerschool-2026/) | [:package:](https://github.com/pyiron-workshop/NFDI-summerschool-2026) | |
| Los Alamos National Laboratory — Executorlib Tutorial | 2026 | | [:books:](https://workshop.pyiron.org/lanl-executorlib-tutorial) | [:package:](https://github.com/pyiron-workshop/lanl-executorlib-tutorial) | |
| Los Alamos National Laboratory — pyiron Tutorial | 2025 | | [:books:](http://workshop.pyiron.org/lanl-tutorial-2025/) | [:package:](https://github.com/pyiron-workshop/lanl-tutorial-2025) | |
| IMSI: Data-Driven Materials Informatics | 2024 | [:memo:](https://www.imsi.institute/activities/data-driven-materials-informatics/) | [:books:](https://workshop.pyiron.org/imsi-tutorial/) | [:package:](https://github.com/pyiron-workshop/imsi-tutorial) | |
| LAMMPS Virtual Workshop and Symposium | 2023 | [:memo:](https://www.lammps.org/workshops/Aug23/) | [:books:](http://workshop.pyiron.org/lammps-workshop-2023) | [:package:](https://github.com/pyiron-workshop/lammps-workshop-2023) | |
| Simulation Workflows in Materials Modelling (SWiMM) | 2021 | [:memo:](https://www.cecam.org/workshop-details/27) | [:books:](http://workshop.pyiron.org/swimm-workshop-2021/) | [:package:](https://github.com/pyiron-workshop/swimm-workshop-2021) | [:tv:](https://www.youtube.com/playlist?list=PL7AkGfbmuLRQeJ-Koq_6m99Lq4mueF2L-) |
| Software Tools from Atomistics to Phase Diagrams | 2020 | | [:books:](https://workshop.pyiron.org/phasediagram-workshop-2020/) | [:package:](https://github.com/pyiron-workshop/phasediagram-workshop-2020) | [:tv:](https://www.youtube.com/playlist?list=PL7AkGfbmuLRReeaQmsTl-vaDyEZR8ROkx) |
| Atomistic Simulations for Industrial Needs | 2020 | [:memo:](https://www.nist.gov/news-events/events/2020/08/atomistic-simulations-industrial-needs) | | [:package:](https://github.com/pyiron-workshop/NIST-workshop-2020) | [:tv:](https://www.youtube.com/watch?v=jQGYUgJK3Ug) |

## Teaching

While the Materials Informatics group is not affiliated with a specific university, we regularly give guest lectures introducing students to computational materials science, scientific programming, and machine learning.

| Title | Year | Website | Repository |
|:------|:-----|:-------:|:----------:|
| Heinrich Heine University: Density Functional Theory | 2026 | [:books:](https://janssenlab.github.io/2026-HHU-lecture/) | [:package:](https://github.com/janssenlab/2026-HHU-lecture) |
| Ruhr University Bochum: Programming Concepts in Materials Science | 2025 | | [:package:](https://github.com/janssenlab/2025-RUB-Programming-Concepts-in-Materials-Science-Lecture) |
| SusMet: Machine Learning in Materials Science | 2025 | [:books:](https://janssenlab.github.io/2025-SusMet-Machine-Learning-Workshop/) | [:package:](https://github.com/janssenlab/2025-SusMet-Machine-Learning-Workshop) |
| Birmingham University: Atomistic Simulation | 2025 | [:books:](https://janssenlab.github.io/2025-Birmingham-University-Atomistic-Simulation-Lecture/) | [:package:](https://github.com/janssenlab/2025-Birmingham-University-Atomistic-Simulation-Lecture) |
| SusMet: Density Functional Theory | 2024 | [:books:](https://janssenlab.github.io/2024-SusMet-Density-Functional-Theory-Lecture/) | [:package:](https://github.com/janssenlab/2024-SusMet-Density-Functional-Theory-Lecture) |

## Learn more

For more information about our research, publications, team, and current activities, visit the [Materials Informatics group at the Max Planck Institute for Sustainable Materials](https://www.mpie.de/5013829/matinf).
