# VPO2

![license](https://img.shields.io/badge/license-license-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-clothing_manufacturing-lightgrey)

> Anticloud-hardened packaging of the upstream project `VPO2` in category **CLOTHING MANUFACTURING**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** CLOTHING MANUFACTURING · **Upstream:** https://github.com/YChuan1115/vpo2-saved · **Upstream pin:** `e31cbf7311ac1bdbde5f99dc58b85375666abe23` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

Valentina
=========
Valentina is a cross-platform patternmaking program which allows designers complete control of the patternmaking process. Patterns can be created using either standard sizing tables or an individual’s set of measurements. Valentina enables haute couture and bespoke patternmaking techniques for creating digital, scalable, sharable patterns with perfect fit. 

Supported platforms:  
   * Windows XP SP2 (32-bit) or later   
   * Ubuntu Linux 14.04 (32-bit/64-bit) or later   
   * OpenSUSE 13.02 (32-bit/64-bit) or later   
   * Fedora 24 (32-bit/64-bit) or later    
   * Mac OS X 10.8 (64-bit) or later  

Homepage and downloads     https://valentina-project.org   
Wiki & User Manual         https://wiki.valentinaproject.org    
Forum                      https://forum.valentina-project.org/       
Translations               https://www.transifex.com/organization/valentina   
PPA for Ubuntu (develop)
PPA for Ubuntu (test) 
IRC channel                #valentina on irc.freenode.net  
Main project            https://github.com/valentina-project/vpo2    

Compiling Valentina
====================
Prerequisites:   
   * Qt 5.2.0 or later (On Unix development packages needed)   
   * git (only for working with project)   
   * On Unix:     
     - g++ (at least GCC 4.7 is needed and GCC 4.8 is recommended) or
       clang (clang 3.4 recommended)
     - xpdf package (tool pdftops).    
   * On Windows:   
     - MinGW  
     - Xpdf is an open source viewer for Portable Document Format (PDF) 
     files. Website http://www.foolabs.com/xpdf/. Put tool pdftops.exe 
     in the same directory with Valentina's binary file.

The installed toolchains have to match the one Qt was compiled with.

You can build Valentina with

    cd $SOURCE_DIRECTORY\build
    qmake ..\Valentina.pro -r CONFIG+=noDebugSymbols CONFIG+=no_ccache
    make (or mingw32-make or nmake or jom, depending on your platform)

Note: On some platforms e.g. Fedora, all Qt-tools come as qmake-qt5, etc. In this case you should install qtchooser. This wrapper resolves the Qt version with respect to QT_SELECT. So run 

    export QT_SELECT=5

prior to qmake. You will not come along with just using qmake-qt5 here.

Note: In order to build and use Valentina, the PATH environment variable needs to be extended to locate qmake, moc and other Qt tools. This is done by adding your Qt's installation path (eg c:\Qt\%VERSION%\bin) to the PATH variable. Check your Qt installation to find the correct path to enter. 

For newer versions of Windows, PATH can be extended through this menu:

     Control Panel|System|Advanced|Environment

You may also need to ensure that the locations of your compiler and other build tools are listed in the PATH variable. This will depend on your choice of software development environment.

Unix systems:
Default prefix for command "make install" is /usr. For using another prefix build with qmake command:

    qmake PREFIX=/usr/local PREFIX_LIB=/usr/lib/i386-linux-gnu Valentina.pro -r CONFIG+=noDebugSymbols CONFIG+=no_ccache

where /usr/local is a new prefix for installation binary files and /usr/lib/i386-linux-gnu is new prefix for install libraries.

LICENSING
==========
Valentina is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

Valentina is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

See LICENSE_GPL.txt file for further information

Other components released under:
* QMuParser - BSD license
* VPropertyExplorer - LGPLv2.1 license
© 2017 GitHub, Inc.
Terms
Privacy
Security
Status
Help
Contact GitHub
API
Training
Shop
Blog
About

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Unknown (no standard manifest detected)** (manifests: none detected; scanned in UPSTREAM_CLONE)
- Top-level source layout: `dist/`, `scripts/`, `share/`, `src/`
- Snapshot size: **2882 files**, **5121690 lines of code** (measured; see Benchmarks)
- Primary languages: `.ts` (1083), `.h` (478), `.cpp` (416), `.png` (375), `.svg` (160), `.ui` (73)
- Upstream commit pinned for this packaging: `e31cbf7311ac1bdbde5f99dc58b85375666abe23`

---

## Installation

You can build Valentina with

    cd $SOURCE_DIRECTORY\build
    qmake ..\Valentina.pro -r CONFIG+=noDebugSymbols CONFIG+=no_ccache
    make (or mingw32-make or nmake or jom, depending on your platform)

Note: On some platforms e.g. Fedora, all Qt-tools come as qmake-qt5, etc. In this case you should install qtchooser. This wrapper resolves the Qt version with respect to QT_SELECT. So run 

    export QT_SELECT=5

prior to qmake. You will not come along with just using qmake-qt5 here.

Note: In order to build and use Valentina, the PATH environment variable needs to be extended to locate qmake, moc and other Qt tools. This is done by adding your Qt's installation path (eg c:\Qt\%VERSION%\bin) to the PATH variable. Check your Qt installation to find the correct path to enter. 

For newer versions of Windows, PATH can be extended through this menu:

     Control Panel|System|Advanced|Environment

You may also need to ensure that the locations of your compiler and other build tools are listed in the PATH variable. This will depend on your choice of software development environment.

Unix systems:
Default prefix for command "make install" is /usr. For using another prefix build with qmake command:

    qmake PREFIX=/usr/local PREFIX_LIB=/usr/lib/i386-linux-gnu Valentina.pro -r CONFIG+=noDebugSymbols CONFIG+=no_ccache

where /usr/local is a new prefix for installation binary files and /usr/lib/i386-linux-gnu is new prefix for install libraries.

LICENSING
==========
Valentina is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

Valentina is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

See LICENSE_GPL.txt file for further information

Other components released under:
* QMuParser - BSD license
* VPropertyExplorer - LGPLv2.1 license
© 2017 GitHub, Inc.
Terms
Privacy
Security
Status
Help
Contact GitHub
API
Training
Shop
Blog
About

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

* Fedora 24 (32-bit/64-bit) or later    
   * Mac OS X 10.8 (64-bit) or later  

Homepage and downloads     https://valentina-project.org   
Wiki & User Manual         https://wiki.valentinaproject.org    
Forum                      https://forum.valentina-project.org/       
Translations               https://www.transifex.com/organization/valentina   
PPA for Ubuntu (develop)
PPA for Ubuntu (test) 
IRC channel                #valentina on irc.freenode.net  
Main project            https://github.com/valentina-project/vpo2    

Compiling Valentina
====================
Prerequisites:   
   * Qt 5.2.0 or later (On Unix development packages needed)   
   * git (only for working with project)   
   * On Unix:     
     - g++ (at least GCC 4.7 is needed and GCC 4.8 is recommended) or
       clang (clang 3.4 recommended)
     - xpdf package (tool pdftops).    
   * On Windows:   
     - MinGW  
     - Xpdf is an open source viewer for Portable Document Format (PDF) 
     files. Website http://www.foolabs.com/xpdf/. Put tool pdftops.exe 
     in the same directory with Valentina's binary file.

The installed toolchains have to match the one Qt was compiled with.

You can build Valentina with

    cd $SOURCE_DIRECTORY\build
    qmake ..\Valentina.pro -r CONFIG+=noDebugSymbols CONFIG+=no_ccache
    make (or mingw32-make or nmake or jom, depending on your platform)

Note: On some platforms e.g. Fedora, all Qt-tools come as qmake-qt5, etc. In this case you should install qtchooser. This wrapper resolves the Qt version with respect to QT_SELECT. So run 

    export QT_SELECT=5

prior to qmake. You will not come along with just using qmake-qt5 here.

Note: In order to build and use Valentina, the PATH environment variable needs to be extended to locate qmake, moc and other Qt tools. This is done by adding your Qt's installation path (eg c:\Qt\%VERSION%\bin) to the PATH variable. Check your Qt installation to find the correct path to enter. 

For newer versions of Windows, PATH can be extended through this menu:

     Control Panel|System|Advanced|Environment

You may also need to ensure that the locations of your compiler and other build tools are listed in the PATH variable. This will depend on your choice of software development environment.

Unix systems:
Default prefix for command "make install" is /usr. For using another prefix build with qmake command:

    qmake PREFIX=/usr/local PREFIX_LIB=/usr/lib/i386-linux-gnu Valentina.pro -r CONFIG+=noDebugSymbols CONFIG+=no_ccache

where /usr/local is a new prefix for installation binary files and /usr/lib/i386-linux-gnu is new prefix for install libraries.

LICENSING
==========
Valentina is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

Valentina is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

See LICENSE_GPL.txt file for further information

Other components released under:
* QMuParser - BSD license
* VPropertyExplorer - LGPLv2.1 license
© 2017 GitHub, Inc.
Terms
Privacy
Security
Status
Help
Contact GitHub
API
Training
Shop
Blog
About

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

The upstream API surface is defined by the `VPO2` source tree vendored in `UPSTREAM_CLONE/` (Unknown (no standard manifest detected) ecosystem). Public entry points:

- Source modules: `dist/`, `scripts/`, `share/`, `src/`
- Overlay API: `anticloud/cli.py` exposes 13 subcommands with JSON stdout; `anticloud/bench/runner.py` runs the 16-check suite; `anticloud/provenance/chain.py` exposes the SHA3-256 + Ed25519 provenance chain.

---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Unknown (no standard manifest detected) |
| Manifests detected | none |
| Files in snapshot | 2882 |
| Lines of code | 5121690 |
| Dependency references | 0 |
| Upstream license | No license file present in the upstream snapshot |
| Overlay license | Anticommons 0.1.0 |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

make (or mingw32-make or nmake or jom, depending on your platform)

Note: On some platforms e.g. Fedora, all Qt-tools come as qmake-qt5, etc. In this case you should install qtchooser. This wrapper resolves the Qt version with respect to QT_SELECT. So run 

    export QT_SELECT=5

prior to qmake. You will not come along with just using qmake-qt5 here.

Note: In order to build and use Valentina, the PATH environment variable needs to be extended to locate qmake, moc and other Qt tools. This is done by adding your Qt's installation path (eg c:\Qt\%VERSION%\bin) to the PATH variable. Check your Qt installation to find the correct path to enter. 

For newer versions of Windows, PATH can be extended through this menu:

     Control Panel|System|Advanced|Environment

You may also need to ensure that the locations of your compiler and other build tools are listed in the PATH variable. This will depend on your choice of software development environment.

Unix systems:
Default prefix for command "make install" is /usr. For using another prefix build with qmake command:

    qmake PREFIX=/usr/local PREFIX_LIB=/usr/lib/i386-linux-gnu Valentina.pro -r CONFIG+=noDebugSymbols CONFIG+=no_ccache

where /usr/local is a new prefix for installation binary files and /usr/lib/i386-linux-gnu is new prefix for install libraries.

LICENSING
==========
Valentina is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

Valentina is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

See LICENSE_GPL.txt file for further information

Other components released under:
* QMuParser - BSD license
* VPropertyExplorer - LGPLv2.1 license
© 2017 GitHub, Inc.
Terms
Privacy
Security
Status
Help
Contact GitHub
API
Training
Shop
Blog
About

*Section quoted from the upstream readme.*
Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

*Excerpt from upstream `CONTRIBUTING.md`:*

# Before pull request

This page describes how to create a pull request. We highly recommend you to read this page before you will decide to send us your changes.

## Named branches

First you should know little bit about our workflow. Right now we work with several named branches (https://www.mercurial-scm.org/wiki/NamedBranches).

* *default* - used only for releases.
* *develop* - branch that contains a code for the next major release. Code in this branch good enough for testing and sharing among developers.
* *feature* - branch that contains a code for unfinished features.
* *release* - used for feature freeze state before the next major release. And for preparing the next minor release.

These are the main branches you should know about. There are several long term task specific branches in project too. But we will not discuss them in this document.

## Check yourself

There are several things you should know for successful creating a pull request.

- Please, read carefully official tutorial from Atlassian Making a Pull Request (https://www.atlassian.com/git/tutorials/making-a-pull-request).
- Normally you are not allowed create new named branches. You should use **develop**, **feature** or **release** depend on a purpose.
- Be sure you use correct branch for your changes. **This is the most popular mistake.**
- - For very small/trivial patches (contains only one commit) use the **develop** named branch directly.
- - For regular patches (contains several commits) you should use the branch **feature (recommended way)**. Don't worry if project already contains one. We can have as many as we need.
- Add correct description for your pull request. It should contain string "Resolved (or Fixed) issue #XXX. <Text of an issue description>". Where XXX is a number of issue in the Issue Tracker. Read more about Resolving issues automatically when push code (https://confluence.atlassian.com/bitbucket/resolve-issues-automatically-when-users-push-code-221451126.html).
- Don't forget to add your changes to file ChangeLog.txt.
- Merge your **develop/feature** branch with **develop** branch.

# Reviewing 
Most likely we will ask you to fix some issues in a code. In this case you will add your changes to the **feature** branch and update your pull request. No need to create new one each time.

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: No license file present in the upstream snapshot** (evidence: `LICENSE` in the upstream snapshot).

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original No license file present in the upstream snapshot terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `No license file present in the upstream snapshot` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `VPO2` (category: CLOTHING MANUFACTURING)
- **Upstream URL:** https://github.com/YChuan1115/vpo2-saved
- **Pinned commit (SHA):** `e31cbf7311ac1bdbde5f99dc58b85375666abe23`
- **Branch:** develop
- **Pin provenance:** resolved during the second documentation pass. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`d6e1c05218d180018cf11a84006d497ebeec8b7433d67aa600a15b9927f7be0e`.

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
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

