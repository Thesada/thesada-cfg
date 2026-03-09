# thesada-cfg

ESPHome configurations and Home Assistant dashboards/blueprints for the Thesada
property monitoring platform.

## Licence

SPDX-License-Identifier: Apache-2.0

## Structure

- [`esphome/`](esphome/) — ESPHome YAML configs, one file per node
- [`ha/dashboards/`](ha/dashboards/) — Home Assistant dashboard YAML files
- [`ha/blueprints/`](ha/blueprints/) — Home Assistant automation blueprints

## Getting Started

1. Copy `esphome/secrets.yaml.example` to `esphome/secrets.yaml`
2. Fill in your credentials — this file is gitignored
3. Run `esphome compile esphome/owb-monitor.yaml` to verify
4. Run `esphome upload esphome/owb-monitor.yaml` to flash
