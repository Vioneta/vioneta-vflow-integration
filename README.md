# VFlow Companion Integration

[![vps][hacsbadge]][vps] [![releasebadge]][release] [![Build Status][buildstatus-shield]][buildstatus-link] [![License][license-shield]](LICENSE.md)

_Companion Component to [node-red-contrib-vioneta-agro-websocket](https://github.com/Vioneta/node-red-contrib-vioneta-agro-websocket) for seamless integration of VFlow with Vioneta Agro._

## Overview

The VFlow Companion Integration bridges VFlow and Vioneta Agro, allowing you to manage Vioneta Agro entities and automations directly from VFlow. This integration enhances your smart automation setup by enabling dynamic interaction between these two powerful tools.

## Key Features

- **Entity Management:**
  - Create and update Vioneta Agro entities from VFlow, including:
    - Binary Sensors
    - Buttons
    - Numbers
    - Selects
    - Sensors
    - Switches
    - Text fields
- **Flow Control:**
  - Enable or disable VFlow flows directly from the Vioneta Agro UI.
- **Webhooks:**
  - Create and manage Vioneta Agro webhooks, with handling in VFlow.
- **Device Automation:**
  - Utilize device triggers and actions within VFlow for advanced automation capabilities.

## Minimum Requirements

- [node-red-contrib-vioneta-agro-websocket](https://github.com/Vioneta/node-red-contrib-vioneta-agro-websocket) v0.57+
- [Vioneta Agro](https://github.com/Vioneta/core) 2024.5+

## Installation

### Option 1: VPS (Vioneta Agro Plugins Store)

To install via VPS:

1. Navigate to VPS -> Integrations -> "+ Explore & Download Repos".
2. Search for "VFlow Companion".
3. Click on the result and select "Download this Repository with VPS".
4. Refresh your browser (due to a known bug that may not update the integration list immediately).
5. Go to "Settings" in the Vioneta Agro sidebar, then select "Devices and Services".

### Option 2: Manual Installation

For manual installation:

1. Access your Vioneta Agro configuration directory (`configuration.yaml` location).
2. If it doesn’t already exist, create a `custom_components` directory.
3. Within `custom_components`, create a new folder named `nodered`.
4. Download all files from the `custom_components/nodered/` directory in this repository.
5. Place these files in the newly created `nodered` directory.
6. Restart Vioneta Agro.
7. Refresh your browser window.
8. From "Settings" in the Vioneta Agro sidebar, select "Devices and Services", click the blue [+ Add Integration] button, search for "VFlow", and install it.

## Configuration

Once the VFlow Companion Integration is installed and added via Vioneta Agro Integrations, all further configuration is managed from within VFlow.

[license-shield]: https://img.shields.io/github/license/Vioneta/vflow-vioneta-integration.svg?style=for-the-badge
[vps]: https://github.com/Vioneta/vflow-vioneta-integration
[hacsbadge]: https://img.shields.io/badge/VPS-Default-orange.svg?style=for-the-badge
[release]: https://github.com/Vioneta/vflow-vioneta-integration/releases
[releasebadge]: https://img.shields.io/github/v/release/Vioneta/vflow-vioneta-integration?style=for-the-badge
[buildstatus-shield]: https://img.shields.io/github/actions/workflow/status/Vioneta/vflow-vioneta-integration/push.yml?branch=main&style=for-the-badge
[buildstatus-link]: https://github.com/Vioneta/vflow-vioneta-integration/actions
