# 21energy Heater Control Blueprints for Home Assistant

These blueprints are designed to enhance the `21energy_heater_control` integration for Home Assistant with flexible and intelligent automations.
They are developed and maintained by 21energy GmbH.

Repository: [github.com/21energy/21energy_heater_control](https://github.com/21energy/21energy_heater_control)

## Available Blueprints

| Blueprint Name               | Description                                                                 |
|-----------------------------|-----------------------------------------------------------------------------|
| Temperature-Based Control   | Turns the heater on or off based on configured min/max temperature.         |
| Solar Power Availability    | Enables the heater when solar power generation exceeds a configured value.  |
| Time-Based Schedule         | Automatically switches the heater on and off at specific times.             |
| Thermal Curve Device Control| Dynamically adjusts heating level from 0–4 based on a temperature curve.    |
| Presence-Based Control      | Turns the heater on when anyone is home, off when everyone leaves.          |

## How to Import a Blueprint

Each blueprint can be imported directly into your Home Assistant instance using the "Import Blueprint" feature.

### Steps

1. In Home Assistant, go to: `Settings` → `Automations & Scenes` → `Blueprints`.
2. Click on the top-right `Import Blueprint` button.
3. Paste the raw URL of the desired blueprint from the table below and press `Preview`.
4. Confirm and save to add it to your blueprints list.

### Import URLs

| Blueprint Name               | Raw URL                                                                                                          |
|-----------------------------|------------------------------------------------------------------------------------------------------------------|
| Temperature-Based Control   | `https://raw.githubusercontent.com/21energy/21energy_heater_control/main/blueprints/automation/21energy_heater_control/temperature_based.yaml`   |
| Solar Power Availability    | `https://raw.githubusercontent.com/21energy/21energy_heater_control/main/blueprints/automation/21energy_heater_control/solar_based.yaml`         |
| Time-Based Schedule         | `https://raw.githubusercontent.com/21energy/21energy_heater_control/main/blueprints/automation/21energy_heater_control/time_based.yaml`          |
| Thermal Curve Device Control| `https://raw.githubusercontent.com/21energy/21energy_heater_control/main/blueprints/automation/21energy_heater_control/thermal_curve.yaml`       |
| Presence-Based Control      | `https://raw.githubusercontent.com/21energy/21energy_heater_control/main/blueprints/automation/21energy_heater_control/presence_based.yaml`      |

## Requirements

These blueprints require the [21energy Heater Control](https://github.com/21energy/21energy_heater_control) integration to be installed via HACS or manually.

Make sure the integration is fully set up and your devices are available in Home Assistant before using the blueprints.

## Feedback and Contributions

Feel free to [open an issue](https://github.com/21energy/21energy_heater_control/issues) for bugs or feature requests. Contributions are welcome.
