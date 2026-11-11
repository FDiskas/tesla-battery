# Tesla Battery and Range Calculator

A browser-based calculator for estimating Tesla battery health, degradation, and real-world range from the vehicle's displayed range, state of charge, mileage, and optional energy consumption.

## Model selection and WLTP

Choose a vehicle configuration from the dropdown. It includes Model 3, Model Y, Model S, and Model X variants, with WLTP ranges based on [Tesla's official power consumption specifications](https://www.tesla.com/lt_lt/support/power-consumption). For trims with multiple published ranges, wheel options are listed separately where provided.

The calculator estimates displayed range at 100% charge, then compares it with the selected configuration's WLTP range:

- **Estimated battery health** = displayed range at 100% ÷ selected WLTP range, capped at 100%.
- **Estimated degradation** = 100% − estimated battery health.

These are estimates based on the vehicle's displayed range, not a direct battery-capacity measurement. Actual range varies with wheel size, equipment, driving conditions, and vehicle configuration.
