# BGH Smart integration for Home Assistant
[![hacs_badge](https://img.shields.io/badge/HACS-Custom-orange.svg?style=for-the-badge)](https://github.com/custom-components/hacs)

This integration will let you control your BGH Smart HVAC from Home Assistant.

## Installation

### Manual

Copy the `bgh_smart` folder to `<config_dir>/custom_components/bgh_smart/`.

### HACS

1. Go to the Home Assistant Community Store (HACS)
2. Go to Integrations
3. Click in the menu with 3 dots on the top right of the screen and select
   "Custom repositories"
4. Add `mool/home-assistant-bgh-smart` as a custom repository and select the
   `Integration` category
5. Search for "BGH Smart"
6. Install the integration

## Configuration

Add the following entry in your `configuration.yaml`:

```yaml
climate:
  - platform: bgh_smart
    username: your_username
    password: your_secret_password
```
