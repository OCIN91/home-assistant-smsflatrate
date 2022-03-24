![smsflatrate.net Logo](https://com.smsflatrate.net/assets/images/smsflatrate-logo.gif "smsflatrate Logo")

# Official Home Assistant SMS Component for SMSFLATRATE

## Installation

Clone the repository to a folder called "custom_components" in your Home
Assistant root directory, e.g. `git clone https://github.com/OCIN91/home-assistant-smsflatrate ~/.homeassistant/custom_components/smsflatrate`

## Configuration

Add to `configuration.yaml` - usually in `~/.homeassistant/`:

```yaml
smsflatrate_sms:

notify:
  - platform: smsflatrate_sms
    sender: HomeAssist # defaults to hass
    name: smsflatrate_sms
    api_key: INSERT_YOUR_SMS77_API_KEY_HERE
    recipient: 01716992343 # or specify multiple numbers eg. [01771783130, 01716992343]
```

Check out the [example](./screenshots/automation_action_call_service.png) on how to
configure a service call on automation.

## Support

Need help? Feel free to write me

[![MIT](https://img.shields.io/badge/License-MIT-teal.svg)](LICENSE)
