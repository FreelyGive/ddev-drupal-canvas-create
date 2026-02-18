[![add-on registry](https://img.shields.io/badge/DDEV-Add--on_Registry-blue)](https://addons.ddev.com)
[![tests](https://github.com/FreelyGive/ddev-drupal-canvas-create/actions/workflows/tests.yml/badge.svg?branch=main)](https://github.com/FreelyGive/ddev-drupal-canvas-create/actions/workflows/tests.yml?query=branch%3Amain)
[![last commit](https://img.shields.io/github/last-commit/FreelyGive/ddev-drupal-canvas-create)](https://github.com/FreelyGive/ddev-drupal-canvas-create/commits)
[![release](https://img.shields.io/github/v/release/FreelyGive/ddev-drupal-canvas-create)](https://github.com/FreelyGive/ddev-drupal-canvas-create/releases/latest)

# DDEV Drupal Canvas Create

## Overview

This add-on integrates @drupal-canvas/create into your [DDEV](https://ddev.com/) project.

## Installation

```bash
ddev add-on get FreelyGive/ddev-drupal-canvas-create
ddev restart
```

After installation, make sure to commit the `.ddev` directory to version control.

## Usage

| Command           | Description                                                |
|-------------------|------------------------------------------------------------|
| `ddev npm-canvas` | Run npm commands in the Drupal Canvas Storybook directory. |

## Credits

**Contributed and maintained by [@FreelyGive](https://github.com/FreelyGive)**
