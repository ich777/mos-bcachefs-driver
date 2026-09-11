# MOS bcachefs

mos-bcachefs provides a **MOS plugin** for managing bcachefs and its tools.

---

## Overview

This repository contains the **MOS plugin implementation**, optional helper
functions, and configuration files (such as `settings.json`) required to
integrate bcachefs management into MOS.

The plugin enables MOS to download and install bcachefs and its tools on demand
directly onto the system.

### Source

- bcachefs-tools: [https://github.com/koverstreet/bcachefs-tools](https://github.com/koverstreet/bcachefs-tools)

No binaries are included in this repository.

---

## Build & Automation

This repository includes a **GitHub Actions workflow** used to build and package
the plugin for MOS.

The build process is fully automated and produces artifacts that can be consumed
by the MOS Hub or MOS release tooling.

---

## Licensing

The contents of this repository (plugin code, scripts, and configuration)
are licensed under **GPL-3.0**.

Downloaded bcachefs packages remain licensed under their respective upstream
licenses and are not part of this repository.
