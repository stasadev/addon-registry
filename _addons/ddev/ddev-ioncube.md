---
title: ddev/ddev-ioncube
github_url: https://github.com/ddev/ddev-ioncube
description: "Enable ionCube PHP loaders for encoded files in DDEV"
user: ddev
repo: ddev-ioncube
repo_id: 697741707
ddev_version_constraint: ">= v1.24.3"
dependencies: []
type: official
created_at: 2023-09-28
updated_at: 2025-04-17
stars: 1
---

[![add-on registry](https://img.shields.io/badge/DDEV-Add--on_Registry-blue)](https://addons.ddev.com)
[![tests](https://github.com/ddev/ddev-ioncube/actions/workflows/tests.yml/badge.svg?branch=main)](https://github.com/ddev/ddev-ioncube/actions/workflows/tests.yml?query=branch%3Amain)
[![last commit](https://img.shields.io/github/last-commit/ddev/ddev-ioncube)](https://github.com/ddev/ddev-ioncube/commits)
[![release](https://img.shields.io/github/v/release/ddev/ddev-ioncube)](https://github.com/ddev/ddev-ioncube/releases/latest)

# DDEV ionCube

## Overview

The [ionCube PHP Encoder](https://www.ioncube.com/loaders.php) is a widely used tool that allows developers to protect their PHP files with powerful encryption and security features.

This add-on integrates ionCube Loaders into your [DDEV](https://ddev.com/) project.

## Features

- ✅ ionCube Loaders for all supported PHP versions
- ✅ Multi-arch support (Will detect your system architecture and install the correct loader version)
- ✅ Plays nice with your existing DDEV configuration
- ✅ Works with other web container customizations
- ✅ Set-and-forget workflow

## Installation

```bash
ddev add-on get ddev/ddev-ioncube
ddev restart
```

## Configuration

None. Add-on works out-of-the-box.

## Credits

**Developed and maintained by [Oblak Studio](https://github.com/oblakstudio)**
