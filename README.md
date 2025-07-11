# Home Assistant JSON Utilities

A collection of helper files for use with Home Assistant, including:

- Time-of-use energy rate plans
- Sensor value mappings
- Device-specific configurations

## Structure

```
home-assistant-json/
├── energy/
│   └── tou_rates/
│       └── pge_e_elec.json
├── sensors/
│   └── dyson-air-quality-levels.json
```

## Usage

These files are intended to support automations, template sensors, and dashboards in Home Assistant. Use them as:

- Value maps in template sensors
- External references for energy monitoring
- Starting points for custom integrations

## Notes

- `tou_rates/` includes PG&E E-ELEC time-of-use rates and periods
- `sensors/` includes air quality level mappings for Dyson devices

---

🛠️ More files coming as I expand my Home Assistant setup.
