[![add-on registry](https://img.shields.io/badge/DDEV-Add--on_Registry-blue)](https://addons.ddev.com)
[![tests](https://github.com/FreelyGive/ddev-drupal-canvas-create/actions/workflows/tests.yml/badge.svg?branch=main)](https://github.com/FreelyGive/ddev-drupal-canvas-create/actions/workflows/tests.yml?query=branch%3Amain)
[![last commit](https://img.shields.io/github/last-commit/FreelyGive/ddev-drupal-canvas-create)](https://github.com/FreelyGive/ddev-drupal-canvas-create/commits)
[![release](https://img.shields.io/github/v/release/FreelyGive/ddev-drupal-canvas-create)](https://github.com/FreelyGive/ddev-drupal-canvas-create/releases/latest)

# DDEV Drupal Canvas Create

## Overview

This add-on integrates Drupal Canvas Create into your [DDEV](https://ddev.com/) project.

## Installation

```bash
ddev add-on get FreelyGive/ddev-drupal-canvas-create
ddev restart
```

After installation, make sure to commit the `.ddev` directory to version control.

## Usage

| Command | Description |
| ------- | ----------- |
| `ddev describe` | View service status and used ports for Drupal Canvas Create |
| `ddev logs -s drupal-canvas-create` | Check Drupal Canvas Create logs |

## Advanced Customization

To change the Docker image:

```bash
ddev dotenv set .ddev/.env.drupal-canvas-create --drupal-canvas-create-docker-image="ddev/ddev-utilities:latest"
ddev add-on get FreelyGive/ddev-drupal-canvas-create
ddev restart
```

Make sure to commit the `.ddev/.env.drupal-canvas-create` file to version control.

All customization options (use with caution):

| Variable | Flag | Default |
| -------- | ---- | ------- |
| `DRUPAL_CANVAS_CREATE_DOCKER_IMAGE` | `--drupal-canvas-create-docker-image` | `ddev/ddev-utilities:latest` |

## Credits

**Contributed and maintained by [@FreelyGive](https://github.com/FreelyGive)**
