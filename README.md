# OPENROCKET

![license](https://img.shields.io/badge/license-license-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-space_aerotech-lightgrey)

> Anticloud-hardened packaging of the upstream project `OPENROCKET` in category **SPACE AEROTECH**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** SPACE AEROTECH · **Upstream:** https://github.com/openrocket/openrocket · **Upstream pin:** `259ba462a4bfeda676af9f9cf018ad3f1a9148c8` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

![OpenRocket banner](.github/banner.png)

![Build Status](https://github.com/openrocket/openrocket/actions/workflows/build.yml/badge.svg)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
![GitHub release](https://img.shields.io/github/release/openrocket/openrocket.svg)
[![Github Releases (by release)](https://img.shields.io/github/downloads/openrocket/openrocket/latest/total.svg)](https://GitHub.com/openrocket/openrocket/releases/)
[![Read the Docs](https://readthedocs.org/projects/openrocket/badge/?version=latest)](https://openrocket.readthedocs.io/en/latest/)
[![snap release](https://snapcraft.io/openrocket/badge.svg)](https://snapcraft.io/openrocket)
![Chocolatey release](https://img.shields.io/chocolatey/v/openrocket)
[![Maven Central](https://maven-badges.sml.io/sonatype-central/info.openrocket/core/badge.svg)](https://maven-badges.sml.io/sonatype-central/info.openrocket/core/)
[![Crowdin](https://badges.crowdin.net/openrocket/localized.svg)](https://crowdin.com/project/openrocket)
[![Join our Discord server!](https://img.shields.io/discord/1073297014814691328?logo=discord)](https://discord.gg/qD2G5v2FAw)

OpenRocket is a free, fully featured model rocket simulator that allows you to design and simulate your rockets before actually building and flying them.

![Four designs rendered in OpenRocket: Atemis, Vortikon, a parallel-booster rocket, and a tube-fin rocket](docs/source/img/showcase/rocket-gallery.jpg)

Explore scale models, detailed decals, pods, staging, and unusual fin shapes. [Browse the gallery](docs/source/introduction/gallery.rst) or [watch Vortikon rotate](docs/source/_static/media/vortikon-rotation.mp4).

--------

## 💾 Installers

You can find the OpenRocket installers [here](https://openrocket.info/downloads.html).

Release notes are available on each [release's page](https://github.com/openrocket/openrocket/releases) or on [our website](https://openrocket.info/release_notes.html).

## 🛠️ Design, Visualize, and Analyze

1. **Design** your rockets using a rich selection of built-in components:
   ![Three-stage rocket - 2D](.github/OpenRocket_home_2D.png)

2. **Visualize** your masterpiece in 3D:
   ![Three-stage rocket - 3D Finished view](.github/OpenRocket_home_3D.png)

3. **Plot & Analyze** your simulation results for precision and improvements:
   ![Three-stage rocket - sustainer altitude and vertical velocity during ascent](.github/OpenRocket_sim.png)

### Choose your theme

![The same three-stage rocket shown in OpenRocket's Light, Dark, and Dark High Contrast themes](docs/source/img/showcase/themes.gif)

## 🌟 Features

- **Six-degree-of-freedom flight simulation**
- **Automatic design optimization**
- **Realtime simulated altitude, velocity, and acceleration display**
- **Staging and clustering support**
- **Export to other simulation programs (RockSim, RASAero II)**
- **Export component(s) to OBJ file for 3D printing or SVG for laser cutting**
- **Cross-platform (Java-based)**

... plus many more

📖 Read more on [our website](https://openrocket.info/).

OpenRocket does not collect telemetry or upload rocket designs. It makes network requests for user-facing functions such as checking for application and motor-database updates, opening online resources, and submitting a bug report when requested by the user. Internet access can be disabled in the application preferences.

## 📖 Documentation

You can find our documentation on [ReadTheDocs](https://openrocket.readthedocs.io/en/latest/).

## 🚀 Getting started

**Check out [our documentation](https://openrocket.readthedocs.io/en/latest/setup/getting_started.html) for a detailled guide on how to get started.**

The easiest way to get familiar with OpenRocket is to open one of our in-program example designs:

<img src=".github/getting-started.png" alt="OpenRocket workspace with File → Open example expanded" width="800">

Dive into the essentials: adjust component dimensions, plot a simulation, swap out motors, and more. Explore the impact of your changes and, most importantly, enjoy the process! 😊

---

## 📐 OpenRocket-related Projects & Tools
*Note: If you have an OpenRocket-related project you would like included in the list, you can file a new issue for it.*

### Core Projects
| Project                                                                               | Type             | Description                                                    |
|---------------------------------------------------------------------------------------|------------------|----------------------------------------------------------------|
| [openrocket/openrocket](https://github.com/openrocket/openrocket)                     | Core project     | Main simulator (Java)                                          |
| [openrocket/openrocket.github.io](https://github.com/openrocket/openrocket.github.io) | Website source   | Website content (Jekyll)                                       |
| [openrocket/openrocket-database](https://github.com/openrocket/openrocket-database)   | Data enhancement | Expanded parts catalog (originally [dbcook/openrocket-database](https://github.com/dbcook/openrocket-database)) |

### Integration & Scripting
| Project                                                                                 | Type                       | Description                                                                         |
|-----------------------------------------------------------------------------------------|----------------------------|-------------------------------------------------------------------------------------|
| [openrocket/orhelper](https://github.com/openrocket/orhelper)                           | Integration (Python)       | Python scripting/module for OpenRocket (via JPype) (forked from [SilentSys/orhelper](https://github.com/SilentSys/orhelper)) |
| [RocketPy-Team/RocketSerializer](https://github.com/RocketPy-Team/RocketSerializer)     | Integra

*(excerpt; full text in `UPSTREAM_CLONE/`)*

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Java / Gradle** (manifests: build.gradle; scanned in UPSTREAM_CLONE)
- Top-level source layout: `config/`, `core/`, `doc/`, `gradle/`, `install4j/`, `snap/`, `swing/`, `test-writing/`
- Snapshot size: **2073 files**, **254662 lines of code** (measured; see Benchmarks)
- Primary languages: `.java` (1346), `.png` (241), `.gz` (77), `.svg` (70), `.csv` (66), `.jpg` (50)
- Upstream commit pinned for this packaging: `259ba462a4bfeda676af9f9cf018ad3f1a9148c8`

---

## Installation

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
![GitHub release](https://img.shields.io/github/release/openrocket/openrocket.svg)
[![Github Releases (by release)](https://img.shields.io/github/downloads/openrocket/openrocket/latest/total.svg)](https://GitHub.com/openrocket/openrocket/releases/)
[![Read the Docs](https://readthedocs.org/projects/openrocket/badge/?version=latest)](https://openrocket.readthedocs.io/en/latest/)
[![snap release](https://snapcraft.io/openrocket/badge.svg)](https://snapcraft.io/openrocket)
![Chocolatey release](https://img.shields.io/chocolatey/v/openrocket)
[![Maven Central](https://maven-badges.sml.io/sonatype-central/info.openrocket/core/badge.svg)](https://maven-badges.sml.io/sonatype-central/info.openrocket/core/)
[![Crowdin](https://badges.crowdin.net/openrocket/localized.svg)](https://crowdin.com/project/openrocket)
[![Join our Discord server!](https://img.shields.io/discord/1073297014814691328?logo=discord)](https://discord.gg/qD2G5v2FAw)

OpenRocket is a free, fully featured model rocket simulator that allows you to design and simulate your rockets before actually building and flying them.

![Four designs rendered in OpenRocket: Atemis, Vortikon, a parallel-booster rocket, and a tube-fin rocket](docs/source/img/showcase/rocket-gallery.jpg)

Explore scale models, detailed decals, pods, staging, and unusual fin shapes. [Browse the gallery](docs/source/introduction/gallery.rst) or [watch Vortikon rotate](docs/source/_static/media/vortikon-rotation.mp4).

--------

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

**Check out [our documentation](https://openrocket.readthedocs.io/en/latest/setup/getting_started.html) for a detailled guide on how to get started.**

The easiest way to get familiar with OpenRocket is to open one of our in-program example designs:

<img src=".github/getting-started.png" alt="OpenRocket workspace with File → Open example expanded" width="800">

Dive into the essentials: adjust component dimensions, plot a simulation, swap out motors, and more. Explore the impact of your changes and, most importantly, enjoy the process! 😊

---

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

The upstream API surface is defined by the `OPENROCKET` source tree vendored in `UPSTREAM_CLONE/` (Java / Gradle ecosystem). Public entry points:

- Source modules: `config/`, `core/`, `doc/`, `gradle/`, `install4j/`, `snap/`, `swing/`, `test-writing/`
- Overlay API: `anticloud/cli.py` exposes 13 subcommands with JSON stdout; `anticloud/bench/runner.py` runs the 16-check suite; `anticloud/provenance/chain.py` exposes the SHA3-256 + Ed25519 provenance chain.

---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Java / Gradle |
| Manifests detected | build.gradle |
| Files in snapshot | 2073 |
| Lines of code | 254662 |
| Dependency references | 0 |
| Upstream license | GPL-3.0 |
| Overlay license | Anticommons 0.1.0 |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

No configuration section was found in the upstream readme. Configuration-relevant files detected in this project directory:

- `config`

Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

*Excerpt from upstream `CONTRIBUTING.md`:*

# Contributing to OpenRocket 🚀
Hi, thank you for your interest in OpenRocket! 😊

I will guide you to contributing to OpenRocket, be it as a developer, tester or any other type of help that will launch - *pun intended* - OpenRocket to the next level.

Before I move on: time is money, so to save you time, get used to how OpenRocket is abbreviated with _OR_.

#### Table Of Contents
[Testing](#testing)
* [Reporting bugs](#reporting-bugs)
* [Suggesting new features](#suggesting-new-features)

[Development](#development)
* [Git workflow](#git-workflow)
* [Commit etiquette](#commit-etiquette)
* [Verified commits](#verified-commits)
* [Pull requests](#pull-requests)

[Translation](#translation)

[Documentation](#documentation)

[Anything else](#anything-else)

## Testing
OpenRocket is not perfect, but we need people to discover and clearly document all of its imperfections. The job of a tester is to discover bugs, formulate new feature requests and to test out software updates. 📝

### Reporting bugs
Please be very concise when you post a new issue. Give a short and appropriate title, preferably with the '[Bug]'-tag in the beginning to indicate a bug.

When explaining the issue, the following elements are important:
* Explain how you expected OpenRocket to behave, and how it behaved instead
* Go through the different steps that you took to (re)create the issue
* Include information about your operating system (e.g. 'macOS Monterey version 12.1') and which version of OpenRocket you are using (e.g. 'the latest unstable branch')
* If applicable, include a Bug Report (preferably in a separate .txt file) of the exception that OpenRocket threw

Providing extra information like a screenshot, a screen recording, the .ork file that produced an error etc. really help understand and solve the issue more quickly.

### Suggesting new features
If you would like to see a new feature implemented in OR, make a new issue for it. Preferably include the tag '[Feature Request]' in the issue's title.

Explain the new feature in detail:
* Which new behavior would you like OR to have
* Why is this new feature important

## Development
Please read our [Developer's Guide](https://openrocket.readthedocs.io/en/latest/dev_guide/development_overview.html). If you still have questions about how to set up your environment, with which issues you should start etc., then don't be afraid to send us a message on [Discord](https://discord.gg/qD2G5v2FAw).

Developing OpenRocket may be daunting at first,

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: GPL-3.0** (evidence: `LICENSE.txt` in the upstream snapshot).

License file excerpt:

```text
OpenRocket - A model rocket simulator

Copyright (C) 2007-2025 Sampo Niskanen and others

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 3 of the License, or (at
your option) any later version.

This program is distributed in the hope that it will be useful, but
WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU
General Public License (below) for more details.

Additional permission under GNU GPL version 3 section 7:

The licensors grant additional permission to package this Program, or
any covered work, along with any non-compilable data files (such as
thrust curves or component databases) and convey the resulting work.
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original GPL-3.0 terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `GPL-3.0` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `OPENROCKET` (category: SPACE AEROTECH)
- **Upstream URL:** https://github.com/openrocket/openrocket
- **Pinned commit (SHA):** `259ba462a4bfeda676af9f9cf018ad3f1a9148c8`
- **Branch:** unstable
- **Pin provenance:** resolved during the second documentation pass. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`029eab9142d4027fd7d89137fdccf17260c3d8d03570763bdf8a8f2c9785463b`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| DANS (KNAW/NWO, Netherlands) | 10.17026/PT | EU-recognised archive |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe
and Mail, Business Insider, National Post, Financial Post, StreetInsider,
Digital Journal, Barchart, International Business Times, and Fox News.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

